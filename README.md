## 内容

- [背景](#背景)
- [使用说明](#使用说明)
- [安装](#安装)
- [徽章](#徽章)
- [示例](#示例)
- [维护者](#维护者)
- [如何贡献](#如何贡献)
- [使用许可](#使用许可)

## 背景
 
>   作为一个技术领域从业者，我们时常会通过写作，来记录知识与专业技能，来达到强化知识点，提升学习能力，提升文字组织能力，提升逻辑思维能力的目的。  
>   目前网站搭建、撰写博客、记录笔记等场景下，除了大型网站，官方网站等会自建图片、视频等专用于存放文件的服务器。其他站点如果是这类文件很多，而且具有较强的依赖性质(服务迁移等情况)的话，那么将是一件复杂的事情，因为每个站点的文件存储方式不同。目前主流的写作方案是Markdown格式，Markdown是一种纯文本格式的标记语言。通过简单的标记语法, 它可以使普通文本内容具有一定的格式。编写Markdown格式的文章，往文章中插入图片等资源是一个问题，因为如果你使用了本地的存储，那么文章发表后，图片链接都需要调整。基于上述情况，我们有了一种只要有网络，就能实现图片文件固定链接访问的需求。因此，图床服务是较完美的选择，我个人使用的七牛云图床，七牛对象存储将数据文件以资源的形式上传到空间中。你可以创建一个或者多个空间，然后向每个空间中上传一个或多个文件。通过获取已上传文件的地址进行文件的分享和下载。



## 使用说明
1.使用前需要注册一个七牛云的账号并进行实名认证，实名认证需要一定的审核时间，注册地址为：[七牛云](https://portal.qiniu.com/signup)   
2.你需要创建一个 [空间（Bucket）](https://developer.qiniu.com/kodo/manual/3978/the-basic-concept#kodo-bucket) ,可以按照网站文档完成存储空间的搭建   
3.将你自己的 AccessKey/SecretKey 填写进代码中  
4.创建图片存放的本地路径和链接文件的存放路径  

## 安装

这个项目使用 [qiniu](https://developer.qiniu.com/kodo/sdk/1242/python) 、[pandas](https://www.pypandas.cn/)、[requests](https://cn.python-requests.org/zh_CN/latest/) 、[shutil](https://docs.python.org/3/library/shutil.html)、 [time](https://docs.python.org/3/library/time.html) 、 [glob](https://docs.python.org/3/library/glob.html) 、 [os](https://docs.python.org/3/library/os.html)。请确保你本地安装了它们。

```sh
# 使用PIP安装库
$ pip  install qiniu
$ pip  install pandas
$ pip  install requests
$ pip  install glob
$ pip  install os
```




## 徽章
如果你的项目遵循 Standard-Readme 而且项目位于 Github 上，非常希望你能把这个徽章加入你的项目。它可以更多的人访问到这个项目，而且采纳 Stand-README。 加入徽章**并非强制的**。 



[![github](https://img.shields.io/badge/github-samuelwang8848-brightgreen.svg)](https://github.com/samuelwang8848)



## 示例

想了解我们建议的规范是如何被应用的，请参考 [example-readmes](example-readmes/)。

## 相关仓库

- [Art of Readme](https://github.com/noffle/art-of-readme) — 💌 写高质量 README 的艺术。
- [open-source-template](https://github.com/davidbgk/open-source-template/) — 一个鼓励参与开源的 README 模板。

## 维护者

[@Samuelwang](https://github.com/samuelwang8848)

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/RichardLitt/standard-readme/issues/new) 或者提交一个 Pull Request。


标准 Readme 遵循 [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) 行为规范。

### 贡献者

感谢以下参与项目的人：
[@Samuelwang](https://github.com/samuelwang8848)

## 使用许可

[HDU](LICENSE) © [Samuelwang](https://github.com/samuelwang8848)
