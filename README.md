 ###### 设备已出，退坑了
 
# PANSHI-X99-D4-OC-EFI
#### PANSHI X99D4(磐石至尊X99-D4）主板 OC EFI On BigSur（MacOS 11.0.1)<br>

 #### 主机配置：
 主板： PANSHI X99D4(磐石至尊X99-D4）<br>
 CPU：  E5-2650v3 @2.3GHz<br>
 内存： 8Gx4(DDR4 2133） <br>
 显卡： 蓝宝石RX570 4G   <br>
 网卡： Realtek RTL811x  <br>
 Wi-Fi：Intel AC7260（miniPCIE） <br>
 声卡:  ALC892 (layoutID 18)  <br>
 硬盘： 海康（HIKVISION）C2000Pro 512G + 1T HDD  <br>
 
 #### 正常工作项目：
 1、CPU变频 <br>
 2、GPU硬解视频（测试4KH265 on MovistPro）<br>
 3、后面板音频I/O <br>
 4、有线网卡 <br>
 5、无线网卡（蓝牙音频、接力、WiFi上网） 来源：[OpenIntelWireless](https://github.com/OpenIntelWireless)<br>
 6、USB2.0、USB3.0速率正常识别 <br>
 
 #### 已知问题：
 1、屏幕锁定息屏唤醒正常，但休眠（睡眠）无法唤醒；<br>
 2、WiFi速率只有80Mbps左右（不知是否与路由器WiFi6兼容性有关）；<br>
 3、视频剪辑软件编码对单独显支持问题，很多软件并不能正确调用GPU硬解；<br>
 
 ## 注意：
 ##### 该主板有较多BIOS项需要调整设置，周末空闲再做个详细设置说明。
 ##### 1月15号已更新0.6.5版本和一些驱动，近期比较忙，等BigSur 11.2正式版出来调整好再一次更新。

安装配置过程所使用资料均来自网络，包括但不限于以下：<br>
[tonymacx86:Heporis](https://www.tonymacx86.com/threads/mojave-10-14-5-on-dell-optiplex-3050.279277/)<br>
[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)<br>
[使用OpenCore引导黑苹果-xin's blog](https://blog.xjn819.com/?p=543)<br>
[OC-little](https://github.com/daliansky/OC-little)<br>
[OpenCore Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)<br>
[远景论坛](http://bbs.pcbeta.com/)<br>
