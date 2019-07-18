# 灰度传感器固件更新说明

### 1.下载灰度传感器固件。

  [v1.1 固件下载地址](https://github.com/UBTEDU/Patrol_Sensor/releases/download/3.4/route3.4.zip)

  [v1.0 固件下载地址](https://github.com/UBTEDU/Patrol_Sensor/releases/download/3.3/route3.3.zip)

> 注：V1.0 版本的灰度传感器刷v1.0 固件，V1.1版本的灰度传感器刷v1.1 固件。两者不能混刷。

### 2.安装[uKit Explore Blockly](https://github.com/UBTEDU/uKit-Explore-Blockly/releases)

> 注：若已安装了uKit Explore Blockly或者Arduino IDE可跳过第二步骤

### 3.解压下载好的固件 routex.x.zip,找到routex.x.ino并打开
![rout3.3.ino文件列表](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/1.png)

### 4.使用原装数据线将灰度传感器连接入电脑，其他线可能不适用

### 5.选择开发板
* 5.1 开发板：在arduino IDE的状态栏选择工具->开发板->Arduino Nano。
* 5.2 处理器：如果你的Arduino IDE版本在1.8.6以下处理器默认ATmega328p即可，若在1.8.6及以上，处理器请选择ATmega328p(Old Bootloader)
* 5.3 端口：然后选择对应的端口。
![arduino IDE操作](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/2.png)


### 6.点击按钮上传即可更新固件

![arduino IDE上传](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/3.png)



