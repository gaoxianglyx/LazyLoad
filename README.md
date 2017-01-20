# LazyLoad-图片延迟加载（懒加载）插件

**使用原生js编写，使得图片出现在可是区域再加载，尚未发现兼容性问题**

[在线实例](http://gaoxianglyx.top/gallery/)


---


### 使用方式
- 你需要在页面中引入LazyLoad.js

```
<script src="LazyLoad.js"></script>
```
- 然后初始化

```
<script>
    var x = new LazyLoad();
    x.init();
</script>
```
**约定，对于需要延迟加载的img标签：**  
1. 定义lazy-src属性为图片实际地址
2. 将预加载的图片地址放入src属性

如实例：

```
<img src="load.gif" alt="img" lazy-src="ture.jpg" height="640px">
```
