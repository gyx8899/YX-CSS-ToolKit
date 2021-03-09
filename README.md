# CSS 练习工厂

## 常用的样式 - 回归基础

- 多行省略
```
.text {
  display: -webkit-box;
  overflow: hidden;
  text-overflow: ellipsis; 
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}
```

- img 图片设定高宽后模糊
```
img {
  width: 100px;
  image-rendering: -moz-crisp-edges;
  image-rendering: -o-crisp-edges;
  image-rendering: -webkit-optimize-contrast;
  image-rendering: crisp-edges;
  -ms-interpolation-mode: nearest-neighbor;
}
```

- 使用 `display: table;` 上下居中
```
.wraper {
  display: table;
}
.item {
  display: table-cell;
  vertical-align: middle;
}
```
