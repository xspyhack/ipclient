# pyIpclient
>
@file    pyIpclient.py                                  
@date    2013-11-08                                     
@author  xspyhack@gmail.com                             
@team    GUET Sec                                       
@brief   python implementation of Ipclient   
@usage   python pyIpclient.py  
                      
## COPYRIGHT
1. 本程序为桂林电子科技大学校园网出校器 Python 版本。
2. 使用`Python`语言实现，图形界面使用 pyGTK 库。
3. 需要`Python 2.x`环境和`pyGTK`库的支持,可以跨平台使用有登录，注销，自动登录，自动重连等原ipclient的功能。
4. 只是为了在Linux/Mac用而写的登录器，虽然本来也有Web版 ipclient
 和 client for linux ，但前者每次都要输入验证码，后者经反编译后发现只有简单的登录和刷新功能，没有注销，也没有获取用户流量和余额信息。
5. pyIpclient 1.81 版本由[ganxiangle@gmail.com](https://github.com/lemacs)创作，但由于现在学校的 ipclient 服务器版本已经更新到了**1.85**，1.81版已经不能继续使用。
6. 经过在 windows 下对官方的最新版 ipclient 抓包以及用 ganxiangle@gmail.com 学长编写的1.81版的 pyIpclient 抓包分析，得到了升级后的整个数据包发送的变更信息，在1.81版的 pyIpclient 的基础上，重新进行了封包，测试，得到1.85版可用的 pyIpClient 。
7. 引用 ganxiangle@gmail.com 学长的话，`pyIpclient仅供学习，供
Linux/Mac用户，Python用户玩玩`。

## USAGE
- **Oh, before use pyIpclient.py you must get your mac address**, ( ah~, you can open your terminal and type command `ifconfig` to get your mac address, it looks like: `xx:xx:xx:xx:xx:xx` ).
- next, replace the test mac address which is at the _line 60_ in the file _pyIpclient.py_ with your mac address.
- If you are a ***Mac OS X*** user, maybe you should install the pyGTK modole in the next. It can be downloaded from ([tar](https://wiki.python.org/moin/PyGtk/) || [pkg](http://sourceforge.net/projects/zero-install/files/PyGTK/2.24.0/org.pygtk.macosx.pkg)).
- And then, open terminal and type command `python pyIpclient.py` and enter.

## INFO
文件 _www.guetsec.org_ 是我在 windows 下用最新版 ipclient 和在 Linux 下用1.81版pyIpclient抓包得到的数据，仅供参考

## TODO
+ 检查版本是否有更新（不会真的把新的Windows版本下载下来）
+ 自动登录后自动隐藏到任务栏
+ TrayIcon的右键popup菜单，要有exit项


### -----淫荡的分割线-----

* 在这里我不忘给`GUET Sec`打个广告 ^ ^
* `GUET Sec`是桂电最神秘的协会－**桂林电子科技大学信息安全协会**的简称，2013年由我和其他几名信息安全爱好者一同创立，隶属于现代教育技术中心，也就是网络中心。
* 主要是负责维护校园网的信息安全，以及整合全校的信息安全人才，与信息安全公司建立合作，搭建交流的平台。
* 协会里面聚集了一些信息安全的牛人，在他们身上时刻能看到黑客精神`Open, Free, Share`。
* GUET Sec希望成为一个极客团队，向其他高校优秀的信息安全团队看齐。
* 我们研究但不局限于*渗透测试*，*网络运维*，*逆向工程*，*内核安全*，*移动安全*以及*软件开发*。
* 假如你是一名信息安全的狂热爱好者，[**欢迎加入我们**](http://www.guetsec.org/joinus.html)
* 更多关于GUET Sec的信息
* site: [www.guetsec.org](http:www.guetsec.org)
* blog: [blog.guetsec.org](http:blog.guetsec.org)
* weibo: [@桂电信安协会_guetsec](http://weibo.com/guetwebsec)
* by: [xspyhack@guetsec](www.xspyhack.com)
