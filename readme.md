# 百度图表 CMD 模块化

使用方法：

第一步引入 echarts

```
var ec = require('./echarts/echarts.js');
```

## 柱状图
```
require('./echarts/chart/bar.js');
ec.init(document.getElementById('demo'));
```


## 折线图
```
require('./echarts/chart/line.js');
ec.init(document.getElementById('demo'));
```


## 饼状图
```
require('./echarts/chart/pie');
ec.init(document.getElementById('demo'));
```



其他类型图表同理。
