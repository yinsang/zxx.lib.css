
用于减小 CSS 体积，提升 Web 页面性能
- **不需要使用**其他reset.css代码
- 添加最常用的 CSS 小 className，保留最常用的属性。
- 建议放在head里加载
# Use
使用时需要注意css className覆盖的情况，建议放在head最后
```html
<head>
<link href="others.bundles.css" rel="stylesheet" />
<link href="zxx.lib.css" rel="stylesheet" />

</head>
<div class="dib">title</div>
```

fork from [zxx.lib.css](https://github.com/zhangxinxu/zxx.lib.css)
