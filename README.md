# MyBlogCDN
mumu's blog (CDN)

这里作为博客的图床仓库使用
jsDelivr + Github 搭建免费CDN


## 建立图床仓库步骤
### 1、新建仓库
Create a new repository

### 2、克隆远程仓库至本地

```js
git clone git@github.com:mumu-pika/MyBlogCDN.git
```

### 3、本地保存好数据之后上传push到远程仓库
```
git status                      //查看状态
git add .                       //添加所有文件到暂存区
git commit -m '第一次提交'        //把文件提交到仓库
git push                        //推送至远程仓库
```

### 4、发布仓库  Releases
Create a new release

**Attention!!**
发布版本号需要添加号tag

### 5、通过jsDeliver引用资源
引用资源的地址格式：
>https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径

>https://cdn.jsdelivr.net/gh/user/repo@version/file

例如：
>https://cdn.jsdelivr.net/gh/mumu-pika/MyBlogCDN@1.0.0/images/pika.gif

之后如果打开看见能显示资源，说明就成功！
well done!
