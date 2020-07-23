## 绑定本地仓库到GitHub:

git init

若将所绑定仓库的上一级错绑，删除上一级的.git文件夹（隐藏文件），再进入需绑定文件夹

## 绑定远程仓库

1. 先使用git remote -v来查看git是否已绑定远程仓库 
2. 绑定：git remote add origin *仓库地址*

绑定错误执行git remote remove origin来解除绑定