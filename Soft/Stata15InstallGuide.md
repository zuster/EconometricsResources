![](https://www.stata.com/includes/images/stata-logo-blue.svg)
<center><h1>Stata15安装指南</h1></center>
1. 把计算机系统时间改到2016年随便哪一天。

2. 安装完整版本 SetupStata15.exe， 安装中要选取IC版本，我的安装根目录是E盘Stata15文件夹，安装完成后此时桌面并没有快捷方式图标。

3. 把计算机系统时间改为当前时间。

4. 下载[RunAsDate.exe](http://www.nirsoft.net/utils/run_as_date.html)，我下载的是`runasdate-x64`。下载后解压缩，把其中的 `RunAsDate.exe` 拷贝到 `Stata15` 安装目录下（此时即E盘Stata15文件夹），运行RunAsDate.exe。
	
	1. 第一步：application to run中选择要运行的程序，即E:\Stata15\Stata-64.exe
	
	2. 第二步：把date改到2017年6月30日之前任何一天
	
	3. 第三步：在create desktop shortcut中填写Stata15
	
	4. 第四步：依次点击run和create desktop shortcut，此时桌面会出现stata15快捷方式图标。
	
	  ![](https://pic.edu.jg.com.cn/forum/201708/20/120358uvpdctuuz9vvpgzt.jpg)
	5. 激活：点击run之后，stata15程序首次启动，输入以下信息：这里的序列号只适用IC版本名字和单位随便填。
	```
		Serial number:10699393
		code: 6irr omjb3xob $m9x k7uh u7lt y258 a51y tphc
		Authorization:vutm
	```
	6. 从桌面快捷方式运行stata15，显示如下：
		![](https://pic.edu.jg.com.cn/forum/201708/20/1205497dh9hdd7h6pew266.jpg)
	7. 在命令窗口输入 set update_query off ，以后就不会显示以上红字了。或者 edit—preferences-general preferences—internet—enable automatic update checking ，取消
	8. 现在情况是：目前可以使用，但是依然不能直接双击stata文件直接用stata15打开（会出现your license has expired错误提示），而是需要利用桌面的快捷方式图标打开，也就是打开桌面快捷方式图标进入stata15后再利用菜单或者命令打开相关数据和do文件，或者需要把文件拖拽到快捷方式图标的方式打开。

> 本内容参考自[Stata15 安装](https://bbs.pinggu.org/thread-5929849-7-1.html)

⚠ _本项目中涉及的资料均来自网络，如果设计版权和付费问题，随时联系删除。下载试读后请及时删除并<b style="color:red;">购买正版</b>_。