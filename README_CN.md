[English version](https://github.com/franocisgar/Hackintosh-AsRock-B460M-Pro-4/blob/master/README.md)  
# Hackintosh-AsRock-B460M-Pro-4  
  
   
更新日志  
  
  
1-X-2021  
更新OpenCore至0.6.4  
相关驱动更新  
Lilu V1.5.1  
AppleALC V1.5.6  
VirtualSMC V1.2.0  
SMCProcessor V1.2.0   
SMCSuperIO V1.2.0  
WhateverGreen V1.4.6     
在5500XT EFI版本里 移除SSDT-RX5500XT-To-W5500X-Version1.0的默认加载  
  
  
12-8-2020  
更新OpenCore至0.6.4  
相关驱动更新  
Lilu V1.5.0  
AppleALC V1.5.5  
VirtualSMC V1.1.9  
SMCProcessor V1.1.9   
SMCSuperIO V1.1.9  
WhateverGreen V1.4.5     
  
  
11-29-2020  
在RX5500XT的EFI中重新编译并更改关于RX5500XT的SSDT-RX5500XT-To-W5500X-Version1.0(更新了ROM修正版、VBIOS版本、EFI驱动程序版本),并修改显示型号为W5500X,并在Config下的DeviceProperties下把所有关于RX5500XT的信息删除  
  
  
11-27-2020   
RX5500XT的EFI加入了SSDT-RX 5500 XT-Version 1.0.aml的并修改了Config下的DeviceProperties关于RX5500XT的部分信息  
  
  
11-24-2020  
加入了RX5500XT的优化EFI  
加入了没有Navi显卡优化的EFI
  
  
11-16-2020  
更新OpenCore至0.6.3  
相关驱动更新  
自己已入手华擎B460M Pro 4+10900es(QTB1),同样用QTB1的朋友可以在platforminfo信息下将ProcessorType的数值从0更改为4105,达到关于本机的CPU型号显示  
修复了黑果下PCI的设备显示  
  
  
10-15-2020  
更新OpenCore至0.6.2  
相关驱动更新  
 
 
10-6-2020  
关于更新  
从OpenCore0.6.2版本起，该机器已不在本人手上，所以目前只推出EFI beta版本，有需要的朋友可参照beta版进行相应的修改
，beta版本不做可使用的保证  
至于EFI正式版等过段时间有闲情重新入一套B460M Pro 4再进行更新  
  
  
华擎B460M Pro 4  
如果没有独显 请使用***.No.navi的EFI  
如果使用的不是Navi核心独显，请使用***.No.navi的EFI  
EFI版本:OpenCore 0.6.1+  
主板:华擎 B460M Pro 4  
CPU:Intel Core I5 10400或 I9 10900ES (QTB1)  
独显：撼讯RX5500XT 伪装成 Radeon Pro W5500X  
     盈通萌宠RX5600XT 伪装成Radeon Pro W5700X  
  
请自行修改机型信息(platforminfo)   
关于启动界面的GUI皮肤，请自行修改