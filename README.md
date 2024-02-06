# images

## 介绍

- Markdown图床
-个人学习日志编写图床

## 参与贡献

- Sentaku

## 图库使用方法

### 初始化本地仓库git init

- git add README.md
- git config --global user.email "you@example.com" （可以去掉--global）
- git config --global user.name "Your Name" （可以去掉--global）
- git commit -m "提交描述"

### 图片上传

- ~~~git remote add origin <https://gitee.com/Sentaku1129/images.git>~~~
- git remote add origin <https://github.com/Sentaku1129/images.git>
- git push -u origin "master"

### 图片使用  

> ~~~<https://gitee.com/Sentaku1129/images/raw/master/图片路径>~~~
> <https://github.com/Sentaku1129/images/raw/master/图片路径>

## 不需要的图片删除

### 预览要删除的文件  

- git rm -f -n --cached 文件名\文件夹  

> 加上-n不会删除任何文件，这可以先预览要删除的文件

### 确认无误后删除文件

- git rm -f --cached 文件名\文件夹

### 提交本地并推送服务器

- git commit -m "提交说明"
- git push -u origin master
