
# 小杰的免费图床
## 五分钟学会搭建带有CDN加速的免费图床

详情请点击：
https://mp.weixin.qq.com/s?__biz=MzkwNzI0MzQ2NQ==&mid=2247489000&idx=1&sn=4cbaec761bb4e8e81b23b2b3a2f24d54&source=41#wechat_redirect


### PicGo
PicGo是一款图片上传工具，目前支持SM.MS图床、腾讯云COS、微博图床、GitHub图床、七牛图床、Imgur图床、阿里云OSS、又拍云图床，未来将支持更多图床。
而这里边，SM.MS和Imgur有免费版也有收费版，腾讯云、七牛、阿里云、又拍云都是收费的，微博图床据说已经挂了，那么，也就剩下GitHub安全、免费又可靠了。
所以我们可以将本地的文件，或者剪切板上截图发送到图床并生成在线图片链接，再贴到我们的博文里，不再占用我们服务器的存储和带宽啦。

PicGo地址：https://github.com/Molunerfinn/PicGo

### GitHub图床
1. 创建GitHub图床之前，需要注册/登陆GitHub账号
2. 创建Repository
- 点击"New repository"按钮
3. 生成一个Token用于操作GitHub repository
4. 回到主页，点击"Settings"按钮
5. 进入页面后，点击"Developer settings"按钮
- 点击"Personal access tokens"按钮
- 填写描述，选择"repo"权限，然后点击"Generate token"按钮

**注：创建成功后，会生成一串token，这串token之后不会再显示，所以第一次看到的时候，可以建个文本文件好好保存，忘记了只有重新生成，每次都不一样。**

### 配置PicGo
- 设定仓库名：这里的格式为用户名/仓库名，比如我的就是 jiege6919/images-host
- 设定分支名：这里写入分支名称，一般直接用maser即可。
- 设定Token：将刚刚创建的令牌填入。
- 指定存储路径：这个地方可以通过写入一个路径名，从而实现指定目录的上传。
- 设定自定义域名：这个域名是为了后边自动生成图片地址拼接而用的，格式是：https://cdn.jsdelivr.net/gh/用户名/分支
- 这么几条配置完成之后，可以点击一下确定，然后将其设为默认图床，然后就可以投入使用了。











