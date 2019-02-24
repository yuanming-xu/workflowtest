# workflowtest test cases
this is a test repository for practice git commands.
## 2019-02-11 test creating branches
    1. 先在master.HEAD 建立分支f1
    2. f1 分支创建1.txt
    3. 在f1的基础上创建f2
    4. f2 分支创建2.txt
    5. 合并 f1, f2 到 master
    6. master创建m1.txt
    7. 在master.HEAD之前的一个版本创建分支f3。就是m1.txt 创建之前。
    8. 切换分支做如下修改：f3 创建3.txt， master.HEAD 创建m2.txt, f1 修改1.txt, f2 修改2.txt
    9. 合并f1, f2, f3 到master
## 2019-02-24 plan: test delete branches && roll back branches
	1. git branch -d 
	2. git branch -D
## 2019-02-24 plan: test roll back files
	1. before add
	2. before commit
	3. before push
	4. after push

## 2019-02-24 plan: test squash commit
	1. git commit --squash ?
## 2019-02-24 plan: test rollback files from a revision number.
	1.

