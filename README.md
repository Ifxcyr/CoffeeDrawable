##  CoffeeDrawable，纯Paint实现的一个搅拌咖啡效果，可用作Loading动画。
### 博客详情： <https://blog.csdn.net/u011387817/article/details/100530256>

### 使用方式:
#### 添加依赖：
```
implementation 'com.wuyr:coffeedrawable:1.0.0'
```

### APIs:
|Method|Description|
|------|-----------|
|create(View targetView)|创建对象<br>**targetView**: 显示此Drawable的容器，下同|
|create(View targetView, int cupRadius)|指定杯子半径来创建对象|
|create(int width, int height)|指定Drawable的宽高来创建对象|
| create(int width, int height, int cupRadius)|指定Drawable的宽高和杯子半径来创建对象|
|start()|开始播放搅拌动画|
|finish()|结束播放搅拌动画|
|reset()|重置状态|
|setProgress(float progress) |设置移动进度|
|updateSize(int width, int height, int cupRadius)|更新CoffeeDrawable的尺寸|
|setCupBodyColor(int color)|设置杯身颜色|
|setCupBottomColor(int color)|设置杯底颜色|
|setCoffeeColor(int color)|设置咖啡颜色|
|setHandColor(int color)|设置手颜色|
|setStickColor(int color)|设置搅拌棒颜色|
|setStirringDuration(long duration)|设置搅拌一圈的时长 (默认: 500)|
|setHideDuration(long duration)|设置隐藏手臂动画时长 (默认: 300)|
|setEdgeFadeDuration(long duration)|设置咖啡边缘渐变动画时长 (默认: 500)|


### Demo下载: [app-debug.apk](https://github.com/wuyr/CoffeeDrawable/raw/master/app-debug.apk)
### Demo源码地址： <https://github.com/wuyr/CoffeeDrawable>

### 效果图：
![preview](https://github.com/wuyr/CoffeeDrawable/raw/master/previews/preview1.gif) ![preview](https://github.com/wuyr/CoffeeDrawable/raw/master/previews/preview2.gif)
