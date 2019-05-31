# Git 应用说明

* 入门
    - 简介
    - 关于版本控制
    - Git简史
    - 什么时Git？
    - 命令行
    - 安装Git
    - 首次Git设置
    - 获取帮助
    - 总结
* Git基本应用
    - 获取Git存储库
    - 记录每次更新到仓库
    - 查看提交历史记录
    - 撤消操作
    - 远程仓库的使用
    - 打标签
    - Git别名
    - 总结
* 服务器上的Git
* 分布式Git
* GitHub
* Git工具
* 自定义Git
* Git与其他系统
* Git内部原理
* 参考资源

------

## 入门
## 帐号
## 配置
## 使用
## 参与
## 总结
## 参考资源

Typora

source tree

https://git-scm.com/downloads

Portable版本

set PATH



1. 进入项目文件夹下
2. git init			//初始化仓库

3. git status		//检查仓库状态
4. git status -s	//简要方式检查仓库状态

5. git add index.html	//添加本地文件到工作区(stage)
6. git add --all	//添加本地所有文件到工作区(stage)
7. git commit -m "第一次提交代码"	//提交

8. git config --global "user.name" "zce"	//配置名字
9. git config --global "user.email" "demo@itcast.cn"	//邮箱地址

10. git rm --cached		//移除提交
11. git log		//查看变更
12. git diff	//查看更改内容
13. git revert 提交的hash值，前6位即可	//回滚操作
14. git checkout HEAD -- .

15. git remote add origin https://github.com/zce/boxuegu.git
16. git remote -v
17. git push origin
18. git pull
19. 
20. 
21. 
22. 
23. 
24. 
25. 
26. 
27. 
28. 
29. 
30. 




Quick setup — if you’ve done this kind of thing before
or	
HTTPS
SSH

https://github.com/Rjaens/Test.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# Test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Rjaens/Test.git
git push -u origin master

…or push an existing repository from the command line
git remote add origin https://github.com/Rjaens/Test.git
git push -u origin master

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.





git clone https://gitee.com//Livios/Notes/HelloGitee.git

git clone https://gitee.com/Livios/HelloGitee.git


git config --global user.name "Livio"
git config --global user.email "l98800770@163.com"

git init
git remote add origin https://gitee.com/Livios/HelloGitee.git


2019.05.28 15:00未衬
http://wthrcdn.etouch.cn/weather_mini?city=

------

## 参考资源：

[Git下载](https://book.git-scm.com)  
[Git官方中文教程](https://book.git-scm.com/book/zh/v2)  
[SourceTree下载](https://www.sourcetreeapp.com)  
[图解Git](http://marklodato.github.io/visual-git-guide/index-zh-cn.html)  
[Git-简明指南](http://rogerdudler.github.io/git-guide/index.zh.html)  
[如何高效利用GitHub](https://www.yangzhiping.com/tech/github.html)  
[GitHub 新手详细教程](https://blog.csdn.net/Hanani_Jia/article/details/77950594)  
[Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)  
[GitHub 使用教程图文详解](https://www.cnblogs.com/r360/p/4931432.html)  



