# AES
此为端对端加密QQ聊天消息程序
采用AES对称加密
你需要与对方先协商好密钥，双方使用相同的密钥即可解密
*注意：请不要把密钥在网络间随意传输，或许你可以通过面对面，邮件传输，信件等方式与对方协定相同的密钥*




原理：
--


高级加密标准（英语：Advanced Encryption Standard，缩写：AES），在密码学中又称Rijndael加密法，是美国联邦政府采用的一种区块加密标准。这个标准用来替代原先的DES，已经被多方分析且广为全世界所使用。经过五年的甄选流程，高级加密标准由美国国家标准与技术研究院（NIST）于2001年11月26日发布于FIPS PUB 197，并在2002年5月26日成为有效的标准。2006年，高级加密标准已然成为对称密钥加密中最流行的算法之一。
![Zpicut.png](https://s2.ax1x.com/2019/06/22/Zpicut.png)

效果预览：
--
![Z9WlSs.jpg](https://s2.ax1x.com/2019/06/22/Z9WlSs.jpg)

使用方法：
-----
 - 安装所需依赖，运行AES1.py
 - **首次运行时**：先执行‘重置密钥以及对话窗口名’按钮，按要求操作，点击‘保存设置’保存，然后**重启程序**   
 - 解密方法：选定密文，Ctrl+C即可显示将明文输出在DOS窗口中，注意查看 
 - 加密方法：直接在软件文本框打字发送即可
 
由于采用的是监听剪贴板的方法，目前有不少关于剪贴板的bug，欢迎pull
希望能够有直接获取QQ消息框文字的方法


