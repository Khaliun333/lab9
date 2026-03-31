User@DESKTOP-QA5HAO2 MINGW64 ~
$ cd ~/Desktop/lab9

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/lab9/.git/

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "version1"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@DESKTOP-QA5HAO2.(none)')

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git config user.email "hb7708669@gmail.com"

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git config user.name "Khaliun333"

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "version1"
[master (root-commit) 4c5a3d4] version1
 1 file changed, 1 insertion(+)
 create mode 100644 hello

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "version2"
[master ede714e] version2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "version3"
[master adc2ce5] version3
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (HEAD -> master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git branch feature1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (HEAD -> master, feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit 187b8189e1030dcecc473679272cf74f80eb1dad (HEAD -> feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1
(END)...skipping...
* commit 187b8189e1030dcecc473679272cf74f80eb1dad (HEAD -> feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
* commit 187b8189e1030dcecc473679272cf74f80eb1dad (HEAD -> feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
* commit 187b8189e1030dcecc473679272cf74f80eb1dad (HEAD -> feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
(END)
* commit 187b8189e1030dcecc473679272cf74f80eb1dad (HEAD -> feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3
|
* commit ede714eec6551e57286f625d173369b0a0d4ca09
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:53:40 2026 +0800
|
|     version2
|
* commit 4c5a3d4e75dd269a1497925e1c32477a49a7eff6
  Author: Khaliun333 <hb7708669@gmail.com>
  Date:   Tue Mar 31 16:52:42 2026 +0800

      version1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git commit -m "feature commit 2"
[feature1 6fc0398] feature commit 2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        feature
Please commit your changes or stash them before you switch branches.
Aborting

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git checkout master
error: Your local changes to the following files would be overwritten by checkout:
        feature
Please commit your changes or stash them before you switch branches.
Aborting

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git commit -m "feature commit 3"
[feature1 57866f7] feature commit 3
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:04:16 2026 +0800
|
|     feature commit 3
|
* commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:01:53 2026 +0800
|
|     feature commit 2
|
* commit 187b8189e1030dcecc473679272cf74f80eb1dad
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:58:53 2026 +0800
|
|     feature commit 1
|
* commit adc2ce5d3483b704b23ce6baa7e41ed8d2219139 (HEAD -> master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 16:54:08 2026 +0800
|
|     version3

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "bug fix"
[master 35735b1] bug fix
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 bugfix

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit 35735b1a2f0f5008d6ee5a5ae5dcbb464d29a440 (HEAD -> master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:05:41 2026 +0800
|
|     bug fix
|
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |
| |     feature commit 3
| |
| * commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:01:53 2026 +0800
| |
| |     feature commit 2
| |
| * commit 187b8189e1030dcecc473679272cf74f80eb1dad
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 16:58:53 2026 +0800
|
|       feature commit 1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git checkout feature1
Switched to branch 'feature1'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git log --all --graph
* commit 35735b1a2f0f5008d6ee5a5ae5dcbb464d29a440 (master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:05:41 2026 +0800
|
|     bug fix
|
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (HEAD -> feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |
| |     feature commit 3
| |
| * commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:01:53 2026 +0800
| |
| |     feature commit 2
| |
| * commit 187b8189e1030dcecc473679272cf74f80eb1dad
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 16:58:53 2026 +0800
|
|       feature commit 1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit 35735b1a2f0f5008d6ee5a5ae5dcbb464d29a440 (HEAD -> master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:05:41 2026 +0800
Merge branch 'feature1'























Merge made by the 'ort' strategy.
 feature | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git merge feature -m "Merge feature1"
merge: feature - not something we can merge

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
*   commit fc68c02174787627bb63b2c40872a407f0bf273b (HEAD -> master)
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:14:14 2026 +0800
| |
| |     Merge branch 'feature1'
| |
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |
| |     feature commit 3
| |
| * commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:01:53 2026 +0800
| |
| |     feature commit 2
| |
| * commit 187b8189e1030dcecc473679272cf74f80eb1dad
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 16:58:53 2026 +0800
| |
407f0bf273b (HEAD -> master)

com>
00



c68e1064cda (feature1)
com>
00



6c2352dc583
com>
00



74f80eb1dad
com>
00


User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git branch conflict

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
*   commit fc68c02174787627bb63b2c40872a407f0bf273b (HEAD -> master, conflict)
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:14:14 2026 +0800
| |
| |     Merge branch 'feature1'
| |
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |
| |     feature commit 3
| |
| * commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:01:53 2026 +0800
| |
| |     feature commit 2
| |
| * commit 187b8189e1030dcecc473679272cf74f80eb1dad
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 16:58:53 2026 +0800
| |

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git checkout conflict
Switched to branch 'conflict'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (conflict)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (conflict)
$ git commit -m "conflict1"
[conflict 3b9c563] conflict1
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (conflict)
$ git log --all --graph
* commit 3b9c5638ec1eee6ee94155fcf1bf30114d6d8386 (HEAD -> conflict)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:24:43 2026 +0800
|
|     conflict1
|
*   commit fc68c02174787627bb63b2c40872a407f0bf273b (master)
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:14:14 2026 +0800
| |
| |     Merge branch 'feature1'
| |
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |
| |     feature commit 3
| |
| * commit 6fc0398d646ec3a3e966385429f6d6c2352dc583
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:01:53 2026 +0800
| |

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (conflict)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "conflict2"
On branch master
nothing to commit, working tree clean

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git commit -m "conflict2"
[master a5b2e83] conflict2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
* commit a5b2e8352393bc8aa72c745a77fd9ffe818275ce (HEAD -> master)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:26:26 2026 +0800
|
|     conflict2
|
| * commit 3b9c5638ec1eee6ee94155fcf1bf30114d6d8386 (conflict)
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:24:43 2026 +0800
|
|       conflict1
|
*   commit fc68c02174787627bb63b2c40872a407f0bf273b
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:14:14 2026 +0800
| |
| |     Merge branch 'feature1'
| |
| * commit 57866f7235d2ab936a39547c6bb5fc68e1064cda (feature1)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:04:16 2026 +0800
| |

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git merge conflict -m "Merge conflict"
Auto-merging feature
CONFLICT (content): Merge conflict in feature
Automatic merge failed; fix conflicts and then commit the result.

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master|MERGING)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master|MERGING)
$ git commit -m "Merge conflict"
[master 13f723a] Merge conflict

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
*   commit 13f723a05477ec1ed1d24ad47598762d359a4945 (HEAD -> master)
|\  Merge: a5b2e83 3b9c563
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:31:16 2026 +0800
| |
| |     Merge conflict
| |
| * commit 3b9c5638ec1eee6ee94155fcf1bf30114d6d8386 (conflict)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:24:43 2026 +0800
| |
| |     conflict1
| |
* | commit a5b2e8352393bc8aa72c745a77fd9ffe818275ce
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:26:26 2026 +0800
|
|       conflict2
|
*   commit fc68c02174787627bb63b2c40872a407f0bf273b
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:14:14 2026 +0800

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git branch new-feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git log --all --graph
*   commit 13f723a05477ec1ed1d24ad47598762d359a4945 (HEAD -> master, new-feature)
|\  Merge: a5b2e83 3b9c563
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:31:16 2026 +0800
| |
| |     Merge conflict
| |
| * commit 3b9c5638ec1eee6ee94155fcf1bf30114d6d8386 (conflict)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:24:43 2026 +0800
| |
| |     conflict1
| |
* | commit a5b2e8352393bc8aa72c745a77fd9ffe818275ce
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:26:26 2026 +0800
|
|       conflict2
|
*   commit fc68c02174787627bb63b2c40872a407f0bf273b
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$  git checkout new-feature
Switched to branch 'new-feature'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git log --all --grapht
fatal: unrecognized argument: --grapht

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git log --all --graph
*   commit 13f723a05477ec1ed1d24ad47598762d359a4945 (HEAD -> new-feature, master)
|\  Merge: a5b2e83 3b9c563
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:31:16 2026 +0800
| |
| |     Merge conflict
| |
| * commit 3b9c5638ec1eee6ee94155fcf1bf30114d6d8386 (conflict)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:24:43 2026 +0800
| |
| |     conflict1
| |
* | commit a5b2e8352393bc8aa72c745a77fd9ffe818275ce
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:26:26 2026 +0800
|
|       conflict2
|
*   commit fc68c02174787627bb63b2c40872a407f0bf273b
|\  Merge: 35735b1 57866f7
| | Author: Khaliun333 <hb7708669@gmail.com>

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git commit -m "new feature"
[new-feature f057f65] new feature
 1 file changed, 1 insertion(+)
 create mode 100644 new-feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git remote add origin https://github.com/Khaliun333/lab9.git

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 32, done.
Counting objects: 100% (32/32), done.
Delta compression using up to 10 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (32/32), 2.59 KiB | 2.59 MiB/s, done.
Total 32 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/Khaliun333/lab9.git
 * [new branch]      master -> master

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git checkout new-feature
Switched to branch 'new-feature'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git push origin new-feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 283 bytes | 283.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'new-feature' on GitHub by visiting:
remote:      https://github.com/Khaliun333/lab9/pull/new/new-feature
remote:
To https://github.com/Khaliun333/lab9.git
 * [new branch]      new-feature -> new-feature

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git fetch
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 889 bytes | 296.00 KiB/s, done.
From https://github.com/Khaliun333/lab9
   13f723a..0d85359  master     -> origin/master

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git log --all --graph
*   commit 0d85359c834f903a81e91eb504d678789851a51a (origin/master, origin/HEAD)
|\  Merge: 13f723a f057f65
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:45:02 2026 +0800
| |
| |     Merge pull request #1 from Khaliun333/new-feature
| |
| |     new feature
| |
| * commit f057f65f893a0aa59931f403220c243fe6e04a82 (HEAD -> new-feature, origin/new-feature)
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:35:00 2026 +0800
|
|       new feature
|
*   commit 13f723a05477ec1ed1d24ad47598762d359a4945 (master)
|\  Merge: a5b2e83 3b9c563
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:31:16 2026 +0800
| |
| |     Merge conflict
| |

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git branch feature1
fatal: a branch named 'feature1' already exists

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git branch -D feature1
Deleted branch feature1 (was 57866f7).

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git branch feature1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git log --all --graph
*   commit 0d85359c834f903a81e91eb504d678789851a51a (origin/master, origin/HEAD)
|\  Merge: 13f723a f057f65
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:45:02 2026 +0800
| |
| |     Merge pull request #1 from Khaliun333/new-feature
| |
| |     new feature
| |
| * commit f057f65f893a0aa59931f403220c243fe6e04a82 (HEAD -> new-feature, origin/new-feature, feature1)
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:35:00 2026 +0800
|
|       new feature
|
*   commit 13f723a05477ec1ed1d24ad47598762d359a4945 (master)
|\  Merge: a5b2e83 3b9c563
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:31:16 2026 +0800
| |
| |     Merge conflict
| |

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git commit -m "feature1"
[new-feature 1f51e39] feature1
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git log --all --graph
* commit 1f51e395f0df1140af992bb1f9e952b20ef053d4 (HEAD -> new-feature)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:49:18 2026 +0800
|
|     feature1
|
| *   commit 0d85359c834f903a81e91eb504d678789851a51a (origin/master, origin/HEAD)
| |\  Merge: 13f723a f057f65
| |/  Author: Khaliun333 <hb7708669@gmail.com>
|/|   Date:   Tue Mar 31 17:45:02 2026 +0800
| |
| |       Merge pull request #1 from Khaliun333/new-feature
| |
| |       new feature
| |
* | commit f057f65f893a0aa59931f403220c243fe6e04a82 (origin/new-feature, feature1)
|/  Author: Khaliun333 <hb7708669@gmail.com>
|   Date:   Tue Mar 31 17:35:00 2026 +0800
|
|       new feature
|

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (new-feature)
$ git checkout master
Switched to branch 'master'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git branch feature2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (master)
$ git checkout feature2
Switched to branch 'feature2'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature2)
$ git add .

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature2)
$ git commit -m "feature2"
[feature2 36bbf49] feature2
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature2)
$ git log --all --graph
* commit 36bbf4974472a7cd6086414255b806cac54647a2 (HEAD -> feature2)
| Author: Khaliun333 <hb7708669@gmail.com>
| Date:   Tue Mar 31 17:51:12 2026 +0800
|
|     feature2
|
| * commit 1f51e395f0df1140af992bb1f9e952b20ef053d4 (new-feature)
| | Author: Khaliun333 <hb7708669@gmail.com>
| | Date:   Tue Mar 31 17:49:18 2026 +0800
| |
| |     feature1
| |
| | * commit 0d85359c834f903a81e91eb504d678789851a51a (origin/master, origin/HEAD)
| |/| Merge: 13f723a f057f65
|/|/  Author: Khaliun333 <hb7708669@gmail.com>
| |   Date:   Tue Mar 31 17:45:02 2026 +0800
| |
| |       Merge pull request #1 from Khaliun333/new-feature
| |
| |       new feature
| |
| * commit f057f65f893a0aa59931f403220c243fe6e04a82 (origin/new-feature, feature
User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature2)
$ git push origin feature2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 10 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature2' on GitHub by visiting:
remote:      https://github.com/Khaliun333/lab9/pull/new/feature2
remote:
To https://github.com/Khaliun333/lab9.git
 * [new branch]      feature2 -> feature2

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature2)
$ git checkout feature1
Switched to branch 'feature1'

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$ git push origin feature1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/Khaliun333/lab9/pull/new/feature1
remote:
To https://github.com/Khaliun333/lab9.git
 * [new branch]      feature1 -> feature1

User@DESKTOP-QA5HAO2 MINGW64 ~/Desktop/lab9 (feature1)
$
