## 安装Git
 下载：https://git-scm.com/

## 检测是否安装成功
 命令：git --version
 反馈：get version 2.21.0.windows.1

## 本地仓库
 1.初始化项目 git init
 2.把项目的文件添加到git 的缓 存列表中
 添加文件
 命令：git add 文件地址（添加单个文件） 
       git add 目录地址（添加整个目录的文件）
 反馈：无
 
 3.把暂存的更改 的缓存列表 提交保存
 命令：git commit -m "消息"
 
 4.创建分支
 git branch <分支名称>
 git branch 查询当前有多少个分支
 git branch <分支名称> -D 删除分支

 默认情况仓库中会有一个默认分支master

 5.切换分支
 git checkout <分支名称>

 6.合并分支
 git merge <其他分支名称>

 7.克隆：当本地没有远程仓库的代码时,使用这个命令克隆远程代码
 git clone <仓库地址>

 如果是通过clone的话远程仓库地址默认是你clone的仓库的地址

8.本地配置
git config

全局项目配置 单个项目配置则去掉global
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

9.查看仓库地址
git remote  查看仓库
git remote remove <仓库名>  删除仓库
git remote add <仓库名> <仓库地址>  添加仓库

10.检查本地仓库是否保存
 1)没有保存先保存
 2)保存好了就可以提交到远程仓库

 11.同步到远程操作
 git push <远程仓库名称> <远程分支名称>
 git push <远程仓库名称> <远程分支名称> -u (绑定这个分支作为默认提交命令)

 避免误区：
 1.一次大的更新前 保存上一个版本 保存之前写的代码方便恢复
 2.下班时需要把代码上传到远程仓库

 12.拉取更新:当远程和本地不同步时 拉取更新(远程的更新)
 git pull

 注：当添加了新的文件 只需要执行 2、3两个步骤就可以

##
