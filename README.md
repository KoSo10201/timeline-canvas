# 使用canvas编写时间轴插件 #
## **背景** ##

项目中有一个视频检测的功能，需要一个时间轴类似视频播放中进度条功能一样显示录像情况，并且可以点击、拖动、放大缩小展示时间轴，获取到时间轴的某个时间。原来的时间轴是使用了***timeslider*** 这个插件，原插件中是使用原生的js 绘制dom节点来显示时间轴，后面使用起来发现每一次重绘就要操作上百个dom节点，性能很差，所以决定采用canvas来重写时间轴。

# 感言
感谢liaoanran | [canvas编写时间轴插件](https：//github.com/liaoanran/timeline-canvas )	


# 说明
该录像liaoanran时间轴js二次修改。

## 修改后效果如下 ##
![](https://i.imgur.com/zW11Lcx.png)

## **修改内容** ##
**1.**
显示刻度最左边00:00

**2.**
增加渲染录像块计算方式及注释

**3.**
修正鼠标显示光标事件源坐标

