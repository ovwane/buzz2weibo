buzz2weibo - 同步Google+到新浪微博
======================================

将Google+上的public消息转发到新浪微博，可包括文字、图片、链接和地理坐标

注：原为Google Buzz开发，所以叫buzz2weibo

特性
----

* 同步文字，这个自然
* 将 Google+ 单条消息中的所有图片拼接上传
* 同步地理坐标，如果有的话
* 如果buzz附有链接，也被同步
* 每次运行缺省只同步3条，防止被新浪微博暂时封禁
* 只同步public的消息，保护私密
* 在新浪微博显示到Google+的链接


运行条件
--------

这是一个在你自己的机器运行的程序，它不是一个网络服务，至少目前不是。

buzz2weibo的运行，必须满足如下条件

* python 2.6 及以上版本，含Image库(python-imaging)
* 能周期定时执行本程序，否则只能每次手工运行
* 畅通的网络，非一般的畅通，你懂的


安装
----

下载、解压，完毕

当然用git clone会更舒服


配置
----

在解压目录下，运行

python setup.py

跟随屏幕操作。完成后，编辑config.py可以配置更多参数


使用
----

python buzz2weibo.py


建议
----

建议在Linux下使用，cron里设为每5分钟执行一次


链接
----

* 主页： https://github.com/sunner/buzz2weibo
* Bugs： https://github.com/sunner/buzz2weibo/issues
* 作者Buzz： https://profiles.google.com/u/0/sunner/buzz
* 作者微博： http://weibo.com/sunnersun
* 作者主页： http://sunner.cn
