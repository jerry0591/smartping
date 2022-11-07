<p align="center">
    <a href="http://smartping.org">
        <img src="http://smartping.org/logo.png">
    </a>
    <h3 align="center">SmartPing | 开源、高效、便捷的网络质量监控神器</h3>
    <p align="center">
        一个综合性网络质量(PING)检测工具，支持正/反向PING绘图、互PING拓扑绘图与报警、全国PING延迟地图与在线检测工具等功能
    
    </p>    
</p>

## 功能 ##

- 正向PING，反向Ping绘图
- 互PING间机器的状态拓扑，自定义延迟、丢包阈值报警（声音报警与邮件报警），报警时MTR检测
- 全国PING延迟地图（各省份可分电信、联通、移动三条线路）
- 检测工具，支持使用SmartPing各节点进行网络相关检测

## 设计思路 ##

本系统的定位为轻量级工具，即使组多点成互Ping网络可以遵守无中心化原则，所有的数据均存储自身节点中，每个节点提供出方向的数据，从任意节点查询数据均会通过Ajax请求关联节点的API接口获取并组装全部数据。
## 项目截图 ##

![app-bg.jpg](http://smartping.org/assets/img/app-bg.png "")

源码来源https://github.com/smartping/smartping
