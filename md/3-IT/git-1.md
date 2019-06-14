#### Windows 10 下使用git

##### § 1 git4windows 下载、安装、调整配置

1.1 git-bash 中文显示
右上角->属性->text

1.2 git-bash 工作目录
途径1：*git-bash 的**快捷方式*** 修改

1.3 git-bash 界面调整

##### § 2 git 基本使用

###### 2.1 git 全局配置

```
jtnfa@windows:/d/wzp/work$ git config --global user.name "rocwang12"
jtnfa@windows:/d/wzp/work$ git config --global user.email "rocwang12@gmail.com"
jtnfa@windows:/d/wzp/work$ git init
Initialized empty Git repository in D:/wzp/work/.git/
jtnfa@windows:/d/wzp/work(master)$ touch README.md
jtnfa@windows:/d/wzp/work(master)$ git add README.md
jtnfa@windows:/d/wzp/work(master)$ git commit -m "first commit"
[master (root-commit) 9fe0233] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
jtnfa@windows:/d/wzp/work(master)$
```

###### 2.2 本地仓库基本操作

###### 2.2 远程仓库基本操作

##### § 3 总结