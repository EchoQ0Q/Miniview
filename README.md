# Miniview 缩略图插件

## Get Started 引入文件:
```html
<link href="miniview.css" rel="stylesheet" />
<script src="http://apps.bdimg.com/libs/jquery/2.1.4/jquery.min.js"></script>
<script src="miniview.js"></script>
```

# 创建miniview标签
```html
<div id="miniview"></div>
```
# 初始化插件
```javascript
$('#miniview').miniview({
    node: '.canvas-element',
    container: '#canvasWrapper',
    miniW: 200,
    miniH: 150
});
```

## Options
### node:  画布节点类名
- Type: `String`
- Default: '.item'

### container:  画布ID名
- Type: `String`
- Default: '#canvasWrapper'

### miniW:  缩略图宽度
- Type: `Number`
- Default: 150

### miniH:  缩略图高度
- Type: `Number`
- Default: 150

## Methods
### refresh： 刷新缩略图,与画布节点同步
```javascript
$("#miniview").miniview('refresh');
```








