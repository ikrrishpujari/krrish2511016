# krrish2511016Microsoft Windows [Version 10.0.26100.4652]
(c) Microsoft Corporation. All rights reserved.

C:\Users\BCA\Desktop\BLISS251107\xyz>echo .> waiting.txt

C:\Users\BCA\Desktop\BLISS251107\xyz>echo .> tracking.txt

C:\Users\BCA\Desktop\BLISS251107\xyz>dir
 Volume in drive C has no label.
 Volume Serial Number is 7090-A6DF

 Directory of C:\Users\BCA\Desktop\BLISS251107\xyz

24-07-2025  11:40    <DIR>          .
24-07-2025  11:17    <DIR>          ..
24-07-2025  11:40                 3 tracking.txt
24-07-2025  11:40                 3 waiting.txt
               2 File(s)              6 bytes
               2 Dir(s)  421,772,468,224 bytes free

C:\Users\BCA\Desktop\BLISS251107\xyz>git config --global user.name “Blisshacks"

C:\Users\BCA\Desktop\BLISS251107\xyz>git config --global user.email “blisscoutinho37@gmail”

C:\Users\BCA\Desktop\BLISS251107\xyz>git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\Users\BCA\Desktop\BLISS251107\xyz>git init
Initialized empty Git repository in C:/Users/BCA/Desktop/BLISS251107/xyz/.git/

C:\Users\BCA\Desktop\BLISS251107\xyz>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        tracking.txt
        waiting.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\BCA\Desktop\BLISS251107\xyz>git add tracking.txt

C:\Users\BCA\Desktop\BLISS251107\xyz>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   tracking.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        waiting.txt


C:\Users\BCA\Desktop\BLISS251107\xyz>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   tracking.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        waiting.txt


C:\Users\BCA\Desktop\BLISS251107\xyz>
