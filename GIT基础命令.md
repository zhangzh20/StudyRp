# GIT基础命令

1. git init
2. git add README
3. git commit  -m "提交说明"
4. git clone <repo> 
5. git config --list
6. git config --global user.name "zhangzh"
7. git config --global user.email "1123@qq.com"
8. git status (查看仓库当前的状态，显示有变更的文件)
9. git remote add origin https://github.com/zhangzh20/StudyRp.git
10. git push -u origin master (提交到远程仓库master分支)
11. git remote rm name (删除远程仓库)
12. ssh-keygen -t rsa -C "1123598684@qq.com" （免密配置，生成公钥）

13. ssh -T git@github.com (测试免密配置是否成功)
14. git checkout 分支名 （切换）