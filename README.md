test case 1. 
1. create empty this file at local, commit and then push. (done)
```
$ git log
commit 2f60424d14a40b8ac1c3011b99f6a90f829b2977 (HEAD -> master, origin/master)
Author: Henry <hliang9795@gmail.com>
Date:   Wed Mar 3 21:03:20 2021 -0500

    empty README.md create at local
```

2. branch. 
2.1 add file1, file2, file3 in 3 commit. change README.md, commit them in 4 commits
2.2 git merge to master, is a fast forward merge. Because master has nothing changed. 

```
21:47 $ git lg1
* a2ca9c7 - (9 minutes ago) add file at local branch br1 - H. Liang (HEAD -> master, origin/master, br1)
* a1f99ef - (18 minutes ago) update README.md at local branch - Henry (origin/br1)
* 02f43ca - (18 minutes ago) add file3 in local branch br - Henry
* 0dcf6c0 - (22 minutes ago) add file2 at local branch br - Henry
* 5153242 - (24 minutes ago) add file 1 at Local branch br. - Henry
* a22cd5a - (41 minutes ago) Update README.md - hliang9795
* 2f60424 - (45 minutes ago) empty README.md create at local - Henry
✔ /mnt/i/workspace/git-sandbox [master|✔]
```

