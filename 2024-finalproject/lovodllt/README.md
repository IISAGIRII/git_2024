# 学习总结
终于是做到这里啦  
这真的是大型抗压训练啊  
经常熬大夜到两三点一无所获  
大半的时间都是在重装系统和检查各种依赖的问题  
~~ubuntu重装了9次的我已经无所畏惧了~~好吧，现在是第10次了  
由于指令太多，这里只记录常用的  

## shell

### 基本命令
1. `pwd`: 展示当前路径
2. `echo`: 打印数据(差不多就是cout，print之类的)  如：echo hello
3. `cd`: 打开某个文件  注：cd ..可以退回到上一级
4. `cat`: 执行文件
5. `mdkir`: 新建文件夹
6. `touch`: 建立一个文件
7. `--help`: 查询命令的具体用途
8. `mv`: 用于移动文件
9. `rm`: 用于删除文件
10. `^c`: 停止进程
11. `^z`: 暂停进程  注：`fg`在前台恢复运行  `bg`在后台恢复进程
12. `chmod`: 用于修改文件的读，写，运行权限
13. `grep`: 筛选内容  如：grep txt 可以筛选出包含txt的行
### 各种符号
1. `>`: 写入内容 __注意：会覆盖原文件__
2. `>>`: 追加内容，在文件内容末尾，不影响原文件
3. `|`: 将一个程序与另一个连接  如：cat hello.txt | grep hello
4. `*`: 匹配任意字符
   + `*txt`: 以txt结尾的
   + `abc*`： 以abc开头的
   + `*hello*`： 包含hello的


## git

###基础命令
1. `git init`: 新建一个仓库
2. `git status`：查看仓库状态
3. `git add <filename>`: 提交文件到暂存区  注：也可以使用`git add .`提交全部
4. `git commit`: 提交文件  注：`-m`后写对本次提交的描述
5. `git log`: 显示历史  注：可以添加`--oneline`以简单显示
6. `git diff`: 显示工作区与暂存区的差异
###分支与合并
1. `git branch`: 显示分支
2. `git brancg <name>`: 创建分支
3. `git checkout <name>`: 切换到分支
4. `git merge <name>`: 合并分支  注：将指定分支合并到当前分支
###远程操作
1. `git clone`: 下载远程仓库
2. `git remote add <远程仓库别名> <远程仓库地址>`: 添加远程仓库
3. `git remote -v`: 查看远程仓库
4. `git pull <远程仓库名> < 远程分支名> ：<本地分支名>`： 拉取仓库内容


## 一些零碎

作为一个彻头彻尾的零基础小白，走到这里不容易啊。还是要非常感谢一起培训的同学们和各位部长的热心帮助，毕竟作为一个小白实在是有很多的疑惑，非常感激大家没有因为我频繁的叨扰而厌烦。
okok就写这么多吧，继续加油！

                 