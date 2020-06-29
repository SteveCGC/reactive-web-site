# 媒体查询

### css3媒体属性简介
- width: 视口宽度
- height: 视口高度
- device-width: 渲染表面的宽度，就是设备屏幕的宽度
- device-height: 渲染表面的高度，就是设备屏幕的高度
- orientation: 检查设备处于横向还是纵向
- aspect-ratio:基于视口宽度和高度的宽高比 widht/height 如：16/9, 4/3
- device-aspect-ratio: 
- color: 每种颜色的位数bits，如：min-color:16位，8位
- resolution: 检测屏幕或打印机的分辨率 如：min-resolution:300dpi

> 以上属性都可以添加 min- 或 max- 前缀

### viewport视口

- 布局视口 ( layout viewport )
- 可视视口 ( visual viewport )
- 理想视口 ( ideal viewport )

> 指定以下内容，布局视口成为理想视口
```
<meta name="viewport" content="width=device-width" />
```

