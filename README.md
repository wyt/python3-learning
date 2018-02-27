## Python3 Learning
------

### 新建python3-learning项目

```bash
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ ls
README.md
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ git status
位于分支 master

初始提交

未跟踪的文件:
  （使用 "git add <文件>..." 以包含要提交的内容）

	README.md

提交为空，但是存在尚未跟踪的文件（使用 "git add" 建立跟踪）
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ git add README.md
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ git commit -m "first commit"
[master （根提交） 7aab6fe] first commit
 1 file changed, 5 insertions(+)
 create mode 100644 README.md
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ git remote add origin git@github.com:wyt/python3-learning.git
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ git push -u origin master
对象计数中: 3, 完成.
Delta compression using up to 2 threads.
压缩对象中: 100% (2/2), 完成.
写入对象中: 100% (3/3), 322 bytes | 0 bytes/s, 完成.
Total 3 (delta 0), reused 0 (delta 0)
To git@github.com:wyt/python3-learning.git
 * [new branch]      master -> master
分支 master 设置为跟踪来自 origin 的远程分支 master。
wangyt@wangyt-virtual-machine:~/data01/github/python3-learning$ 
```

### Python Hello

1. python hello

   见hello.py, 设置成可执行文件, 添加头 #!/usr/bin/env python3

2. python calc

   见calc.py, python数学计算示例.


