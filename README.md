# 灰度传感器固件更新说明

1.下载灰度传感器固件。

[v1.1 固件下载地址](https://github-production-release-asset-2e65be.s3.amazonaws.com/172451029/ce86f480-91e5-11e9-803f-0f4369326441?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20190718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20190718T072911Z&X-Amz-Expires=300&X-Amz-Signature=52c39e8893c68cc370ad35321399c983c4454e2dac8579639dbdfc17993318aa&X-Amz-SignedHeaders=host&actor_id=17878081&response-content-disposition=attachment%3B%20filename%3Droute3.4.zip&response-content-type=application%2Foctet-stream)

[v1.0 固件下载地址](https://github-production-release-asset-2e65be.s3.amazonaws.com/172451029/a578e600-390e-11e9-8ead-9838094eb665?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20190718%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20190718T073009Z&X-Amz-Expires=300&X-Amz-Signature=51134925f359453c2f69a8c43a5f633b0ec7ffc25d6de238a63d7c2278aa274e&X-Amz-SignedHeaders=host&actor_id=17878081&response-content-disposition=attachment%3B%20filename%3Droute3.3.zip&response-content-type=application%2Foctet-stream)

2.安装[uKit Explore Blockly](https://github.com/UBTEDU/uKit-Explore-Blockly/releases)

> 注：若已安装了uKit Explore Blockly或者Arduino IDE可跳过第二步骤

3.解压route3.3.zip,找到route3.3.ino并打开
![rout3.3.ino文件列表](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/1.png)

4.用usb数据线将巡线板连接入电脑

5.在arduino IDE的状态栏选择工具->开发板->Arduino Nano。然后选择对应的端口。
![arduino IDE操作](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/2.png)
> 注：如果你的Arduino IDE版本在1.8.6以下处理器默认ATmega328p即可，若在1.8.6及以上，处理器请选择ATmega328p(Old Bootloader)

6.点击按钮上传即可更新固件

![arduino IDE上传](https://github.com/UBTEDU/Patrol_Sensor/blob/master/photo/3.png)



