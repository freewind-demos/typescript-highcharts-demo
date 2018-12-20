TypeScript Highcharts Demo
==========================

`highcharts`的包里已经自带了typing，不需要使用`@types/highcharts`。

另外需要注意的：

1. `series`对应的有82个类型，每个类型代表某一种图表，使用时需要结合官网例子和api等确定。可以根据`type`去猜。
2. 如果某个数据没有，在js中使用`null`，但在typescript不匹配类型，需要用`{}`代替

```
npm run demo
```

Resources
---------
- highcharts api：<https://api.highcharts.com/highstock/series.line>
