# ink_Werttin

> An ink theme based on offical theme.

[Skimige 版本传送门](https://github.com/Skimige/ink_Werttin)

## 使用说明

### 预览

最简单的方法是去参观我的博客辣~ [传送门](http://ikevin.in)

[SmartBlog 版本，在细节上略有差异](https://www.tcdw.net/)

以下截图可能有点旧。

[首页](https://cloud.githubusercontent.com/assets/9017470/10266999/daf3a772-6ab1-11e5-9449-5bcc47eabbc7.gif) \ [文章页](https://cloud.githubusercontent.com/assets/9017470/10267001/06981ca0-6ab2-11e5-9f6e-ad007b3e66b6.gif) \ [归档页](https://cloud.githubusercontent.com/assets/9017470/10267003/26286408-6ab2-11e5-97b4-1cf25b14a98a.gif)

### 下载

```bash
cd /path/to/your/SmartBlog/templates
git clone https://github.com/tcdw/smartblog-theme-werttin
mv smartblog-theme-werttin werttin
mv werttin/static/werttin static/werttin
```

### 功能

 - 默认字体为 `Microsoft Yahei UI` ，对 `sans-serif` 和 `serif` 没啥好感
 - 支持 zh (Chinese) / en (English) 两种语言，请修改根目录的 `config.yml` 中此处：

>     lang: **

 - 为了使加载速度更快，摒弃了大部分图片。其中包括首页作者 Avatar、文章下小 Avatar 等
 - 文章内**不支持头图功能**（此功能被阉割）
 - 支持图片 Lazyload
 - 支持页面平滑滚动
 - more..

### 启用姿势

在 config/system.json 里设置以下字段：

 - `Author_Name`（作者昵称）
 - `Author_Introduction`（作者简介）
 - `Author_Image`（作者头像）

以上内容中，如果你的 `favicon.ico` 要替换或者修改为 PNG 格式的图片，请自行修改。

如果没有图片或者懒得设置，**请删除这一行，否则可能会报错。**

另：虽然确实是去掉了首页的几个头像，但在文章页评论框上，作者简介中的头像并没有去掉。
所以…别忘了设置好你的 `config/system.json`！

## License

遵循 [Apache License 2.0](https://github.com/Skimige/ink_Werttin/blob/master/LICENSE)
