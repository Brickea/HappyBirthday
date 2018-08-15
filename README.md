# NOTE

BRICKEA

2018年8月14日

---

## Bootstrap的css直接引用方法

* css的引用

```html
<link rel="stylesheet" href="https://cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u"
        crossorigin="anonymous">
```

* js的引用

```html
<!-- jQuery (Bootstrap 的所有 JavaScript 插件都依赖 jQuery，所以必须放在前边) -->
    <script src="https://cdn.bootcss.com/jquery/1.12.4/jquery.min.js"></script>
    <!-- 加载 Bootstrap 的所有 JavaScript 插件。你也可以根据需要只加载单个插件。 -->
    <script src="https://cdn.bootcss.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```

---

## 关于图片压缩提升网站性能

两个思路

* 一个是将图片直接进行压缩，可以到一些线上网页进行，一般压缩到100kb一下会比较好

* 二个是通过“画图”来直接修改图片的分辨率，也可以有效减小图片大小进而提升网页加载性能