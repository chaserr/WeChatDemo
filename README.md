<!-- /TOC -->

# WeChatDemo
基于MonkeyDev和其他大神开发的非越狱微信插件，实现了可运行在自己手机上的一个demo
# dev
电脑上已安装theos环境
# Des
wechat.iap_vesion:6.7.1

该运行版制作主要顺序：
1. 使用otool工作修改红包插件的libsubstrate.dylib动态库的install_path为wechat的framework的可执行路径
2. 使用MonkeyDev将红包插件注入到从pp助手下载下来的最新破解版wechat.iap， 生成一个自己的dylib
3. 再使用MonkeyDev创建一个工程，将2生成的dylib注入到当前工程中
4. 使用个人证书， run -- 安装到自己的手机

> 关于MonkeyDev和MonkeyPod的使用，请移步到MonkeyDev

# Usage
因为本库是使用LFS来上传ipa大文件和可执行文件的所以需要使用下面方法来clone
```ruby
git lfs clone xxx #git库地址
```
> 关于  Git LFS 的了解请自行gooooog

> 电脑上没有安装theos环境的同学可以先自行安装

# Update
2018.10.8
由于git lfs存储量达到免费极限，可能通过以上命令无法clone下大文件，所以还是将工程文件放到网盘好了。

链接: https://pan.baidu.com/s/1pUVOmIgHIlHlzukg31DwXg

提取码: uifp
