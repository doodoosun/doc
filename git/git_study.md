
1. 查看Git 的状态
git status 
2.添加当前工作区的所有文件，到缓冲区.
git add .
3.Commit 你的代码并且添加注释“test”
git  commit -m “test”
4.用远端重置本地的文件Overwrite的作用
git reset --hard origin/develop
git reset --hard
5.改动之前先更新（如果本地有更新先git add .）
git pull 
6.查看更新日志
git log
7.
vim .git 
8.文件的集中状态
untracked unstaged
9.编辑ignore文件
vim .gitignore
10. github 中和Issue 关联
git commit -m “#3 “   能
11.本地版本commit 的合并，如果本地有6个commit，会重新
（git add . | git commit -m "version" | git push）
git rest origin/develop
12. 初始化git 文件夹会生成.git 文件夹
$ git init
Initialized empty Git repository in /Users/Documents/workspace_luna/doc/.git/
13. 
$ git remote add origin git@github.com:doodoosun/doc.git
14. 推送到Master 分支
 $ git push -u origin master




