# code-base
* 记录一些代码和学习笔记
* 见证自己的成长



## git常用命令

```

1.1 基本配置
git --version：返回版本号
git --help：帮助文档
git config --list：查看所有配置
git config --list --show-origin：查看所有配置以及它们所在的文件
git config --global user.name "用户名"：全局配置用户名
git config --global user.email 邮箱地址：全局配置邮箱
git config user.name：查看用户名
git config user.email：查看邮箱
我们在 GitHub 的每次提交理论上都会在 主页的下面产生一条绿色小方块的记录，如果你确认你提交了，但是没有绿色方块显示，那肯定是你提交代码配置的邮箱跟你 GitHub 上的邮箱不一致，GitHub 上的邮箱可以到 Setting -> Emails里查看。

1.2 基本操作
git status ：查看仓库状态
git init：创建一个空仓库，或者重新初始化一个已有仓库
git add：把文件添加到可提交列表（临时缓冲区）
git commit：提交改动（增删改）至仓库
git log：打印提交日志
git branch：查看、添加、删除分支
git checkout：切换分支、标签
git merge：合并分支
git tag：新建、查看标签
git clone：下载仓库
git commit -m "xxx" //提交,并添加备注信息
git push origin main //将本地仓库上传至主分支

```

