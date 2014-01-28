firstGitSource
==============

第一次搭建git项目测试

创建ssh_keygen命令
$ ssh-keygen -t rsa -C "your_email@youremail.com"
位置在c/users/.ssh下的id_rsa.pub

验证是否成功命令
$ ssh -T git@github.com

接下来我们要做的就是把本地仓库传到github上去，在此之前还需要设置username和email，因为github每次commit都会记录他们。
 $ git config --global user.name "your name" 
  $ git config --global user.name "your name"$ git config --global user.email "your_email@youremail.com"
  （4）进入要上传的仓库，右键git bash，添加远程地址：
  $ git remote add origin git@github.com:yourName/yourRepo.git
  
可以直接找到项目目录下的.git下的config文件直接修改

