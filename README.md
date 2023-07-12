# NACLACG.github.io
![t2i](https://github.com/NACLACG/GetID-Over/blob/master/EllenMiraMathers/10901%20%23680453.png?raw=true)
# 前置
下载并安装JAVA8:

教程使用的环境仅供参考 以自己安装的为准

https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-47-34.png?raw=true)

环境变量:

JAVA_HOME 对应 %JAVA8_HOME%

JAVA8_HOME 对应 c:\Program Files\Java\jdk1.8.0_60

把 C:\ProgramData\Oracle\Java\javapath 目录下 java.exe   javaw.exe   javaws.exe 删除

于cmd中使用 java -version 命令测试是否安装成功


下载并解压WTSightEdit:

https://github.com/SMILEY4/WTSightEdit/releases/tag/1.2.13


下载并解压JavaFX:

https://gluonhq.com/products/javafx/

# JAVAFX放置于WTSightEdit解压路径内部

以下为需要复制的路径 以操作者自主决定的解压路径为参照

D:/WTSightEdit_1_2_13/javafx-sdk-20.0.1/lib

D:/WTSightEdit_1_2_13/data/wtedit_application.jar

# 打开CMD运行以下命令

```
   java --module-path D:/WTSightEdit_1_2_13/javafx-sdk-20.0.1/lib --add-modules javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web,javafx.swt -jar D:/WTSightEdit_1_2_13/data/wtedit_application.jar
   ```

其中 D:/WTSightEdit_1_2_13/javafx-sdk-20.0.1/lib 和 D:/WTSightEdit_1_2_13/data/wtedit_application.jar 以自己本机为参照修改

于 D:/WTSightEdit_1_2_13 目录下创建WTSightEdit.txt文件写入以下内容:

java -jar WTSightEdit.jar

# 将WTSightEdit.txt文件后缀改为bat

# 创建Example.blk文件[创建txt文件改后缀即可] 写入以下内容
```
crosshairHorVertSize:p2=3, 2
rangefinderProgressBarColor1:c=240, 202, 97, 80
rangefinderProgressBarColor2:c=255, 255, 255, 64
rangefinderTextScale:r=1.2
rangefinderVerticalOffset:r=-21
rangefinderHorizontalOffset:r=-40
rangefinderUseThousandth:b = yes
fontSizeMult:r=0.97
lineSizeMult:r=1.0
drawCentralLineVert:b=no
drawCentralLineHorz:b=no
drawSightMask:b=yes
crosshairColor:c=0, 0, 0
crosshairLightColor:c=255, 255, 255
crosshairDistHorSizeMain:p2=0.03, 0.02
crosshairDistHorSizeAdditional:p2=0.005, 0.003
distanceCorrectionPos:p2=-0.03, -0.011
drawDistanceCorrection:b=yes

crosshair_distances{
}

crosshair_hor_ranges{
}

matchExpClass {
exp_tank:b = yes
exp_heavy_tank:b = yes
exp_tank_destroyer:b = yes
exp_SPAA:b = yes
}

drawQuads {

}

drawLines{

}

drawTexts {
}

drawCircles {

}
   ```


# 以Example.blk为蓝本创建瞄具

使用 WTSightEdit.bat 文件打开程序

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-56-29.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-57-06.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-57-16.png?raw=true)

# 程序的最后更新为2021年 会有载具不全的情况 选相近的

  1.输入载具部分名称

  2.按钮功能为匹配含有输入字符部分的载具

  3.下一步

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-58-06.png?raw=true)

# 找到主炮[或者自己需要的弹种]随意丢一张图片上去

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-59-06.png?raw=true)

# 找到自己要编辑的弹种 

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_14-59-28.png?raw=true)

# 需要把添加过图片的弹种 全部编辑一遍

1.勾上

2.鼠标滚轮缩放编辑区

3.随意放置5个点

4.正式开始编辑瞄具

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-00-37.png?raw=true)

# 此后的内容为简单的界面功能介绍 最重要的瞄具存储在末尾部分
# 该教程的编写者为 EllenMiraMathers - Ellen·Mira·Mathers-Sight的作者
https://live.warthunder.com/post/1077734/en/


# 该选项为选择部分动态虚线描边
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-01-48.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-02-13.png?raw=true)

# 该选项为 显示/不显示 测距仪数值

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-03-04.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-03-21.png?raw=true)

# 动态标尺

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-04-30.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-04-58.png?raw=true)

# 放置游戏截图用以辅助瞄具绘制

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-05-49.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-06-01.png?raw=true)

# 添加直线 圆圈等基本型 以及编辑面板

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-07-06.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-07-26.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-07-58.png?raw=true)

# 完成编辑后导出自己的瞄具

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-08-50.png?raw=true)

# 瞄具编辑完成后需要进行代码移植

  1.程序创建的瞄具文件会有载具和武器的配对限制

  2.依照第二张图的提示，把需要的代码移植到对应位置

![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-10-51.png?raw=true)
![t2i](https://github.com/NACLACG/NACLACG.github.io/blob/master/WTSinght/Snipaste_2023-07-12_15-12-01.png?raw=true)
