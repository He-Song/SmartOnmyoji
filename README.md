# SmartOmmyoji

> 为了解放双手，特意学了python~

#### 依赖库
- Gooey
- pywin32
- opencv-python
- numpy

#### 使用
- 先安装python3.7,再安装上述依赖库
- 管理员身份运行 smart_onmyoji_gooey_ui.py
- 电脑版阴阳师不要调分辨率，如果要调分辨率，需要重新截图，放到对应的路径下面
- 应该不支持安卓模拟器，不过可以用scrcpy或qtscrcpy手机投屏连电脑，需要重新截图（opencv的模板匹配有点坑，大小方向一改变就匹配不到了。。。。）
- 原理是定时截图，然后找到图片坐标，然后随机延迟并点击附近随机坐标
- 除了阴阳师，也可以其他点点点的游戏，比如战舰少女、微信红包啥的~
