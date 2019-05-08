# 菜鸟教程 Git 测试

git init //初始化本地库

git add README.md //添加文件

git commit -m "添加 README.md 文件" //提交并备注信息

git config --global user.name  "wwfendurer" //你的GitHub登陆名

git config --global user.email "425845682@qq.com" //你的GitHub注册邮箱

git remote add origin git@github.com:wwfendurer/test003.git //关联一个远程库命令， git@github.com:wwfendurer/test003.git 这个是自己远程库

git push -u origin master //关联后,第一次推送master分支的所有内容命令，此后，每次本地提交后，就可以使用命令git push origin master推送最新修改

1.安装NodeJS
NodeJs的安装方式非常简单。https://nodejs.org/en/ 下载LTS版本的安装包，一路Next就好了。
安装成功后，在命令行上运行 node -v 和 npm -v

2.安装Angular的包 npm install -g @angular/cli
安装成功后，在命令行上运行 ng version

3.ng new testapp  //testapp可以自己写你喜欢的名字，就是你的项目名

4.npm start

5.ng add ng-zorro-antd [options]

6.npm install ng-zorro-antd



