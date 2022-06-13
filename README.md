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
>https://cdn.jsdelivr.net/gh/mumu-pika/MyBlogCDN@1.0.2/images/covers/avlon.jpg

当然，如果不加版本号，会默认使用最新版本，如下使用：
>https://cdn.jsdelivr.net/gh/mumu-pika/MyBlogCDN/images/covers/avlon.jpg

之后如果打开看见能显示资源，说明就成功！
well done!


## 优秀资源网站收集
### 1、stockup
海量数据的图片网站，更类似于图片搜索引擎，可以搜索21个免费图片网站！

>https://stockup.sitebuilderreport.com/

### 2、pixabay

丰富的中文图片网站，优质矢量图(无背景) 主要资源为风景、动物等
>https://pixabay.com/

### 3、streetwill
比较小众的图片资源网站，偶尔会惊喜!

>http://streetwill.co/

### 4、Gratisography

一个比较有创意的图片资源网站， 艺术插图等等
>http://mcguiremade.com/

### 5、textures
textures则是一个贴图网站，其提供的海量高清贴图，全部可以免费下载，在左侧导航栏你可以随意选择自己需要的分类，但是由于图片质量太高，每天都只能限量下载

>https://www.textures.com/

### 6、pexels
Pexels是一个免费高清素材下载网站，所有图片都由专业人士使用顶级的拍摄设备进行拍摄，每一张图片都会显示拍摄设备和光圈、焦距等具体信息，让你可以在下载图片的同时，学习相机的参数设置, 炒鸡良心！

>https://www.pexels.com/

### 7、pakutaso
日本高清写真资源网站，非常小清新

>https://www.pakutaso.com/

### 8、photoshopvip
日本超人气插画库

>https://photoshopvip.net/

### 9、wallhaven
动漫超清壁纸, 特别喜欢它的Random页。try your luck!

>https://wallhaven.cc/

### 10、alphacoders
超多的动漫分类wallpaper

>https://wall.alphacoders.com/

### 11、wallpaperscraft
anime 标签下的动漫图片，分辨率较高，可以按尺寸和分辨率下载图片。支持安卓和 iOS 客户端。

>https://wallpaperscraft.com/

### 12、burst.shopify
个人比较喜欢的图片资源网站，小众，但是资源和质量高

>https://burst.shopify.com/nature



## 图片压缩
对于网站优化，图片压缩也是必不可少的！
我喜欢用下面这个压缩网站，能够在线压缩主流的图片，强烈推荐！

### tinypng

>https://tinypng.com/
