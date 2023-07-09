---
date: 2023-07-09 
---

随着Web Font越来越流行，特别是Google Font字库越来越完善，让我们的网站在本地配置各种好看的字体的变得越来越容易。

Web Font是将字体置于服务端，利用 **CSS** 中的 _font-family_ 进行设置，客户端展现时才将字体资源加载到浏览器中，这样就能够灵活地配置网站各个模块的字体。

本站目前使用的字体如下：

-   中文： **[Noto Serif SC](https://fonts.google.com/specimen/Noto+Serif+SC) - 思源宋体**

-   英文： **[Linux Biolinum](https://www.fontke.com/family/290108/)**

-   代码： **[Anonymous Pro](https://fonts.google.com/specimen/Anonymous+Pro)**

本文主要讲如何在Hexo博客中引入Google Font字库中的思源宋体\[Noto Serif SC\]和Anonymous Pro。

## 引入字体

在 **[Google Font](https://fonts.google.com/)** 上寻找自己喜欢的字体，并获取到引入代码。

可同时引入多种字体和字形，例如一次性引入思源宋体\[Noto Serif SC\]和Anonymous Pro。

`<link>`标签引入：

```
<link rel="preconnect" href="https://fonts.gstatic.com"><link href="https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&family=Noto+Serif+SC:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

在主题的`</head>`前引入以上代码即可。

`@import`引入

```
@import url('https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&family=Noto+Serif+SC:wght@300;400;500;600;700&display=swap');
```

将以上代码放你的CSS代码文件中即可。

## 配置字体

以上两字体的CSS配置信息如下

```
font-family: 'Noto Serif SC', serif;font-family: 'Anonymous Pro', monospace;
```

全局配置中文为思源宋体，英文为Linux Biolinum，代码为Anonymous Pro

本站采用`<link>`引入思源宋体和Anonymous Pro，配置方法如下

**由于中文字体内包含英文字体而英文字体一般不包含中文字体，所以必须优先配置英文字体，不然英文显示的依然是中文字体内的字体。**

```
html,body {    font-family: "Linux Biolinum", "Noto Serif SC", serif;    -webkit-font-smoothing: antialiased;    -webkit-tap-highlight-color: rgba(0,0,0,0);    width: 100%}
```

代码字体配置如下

代码字体为Anonymous Pro，让代码中文注释依然为思源宋体。

```
code,pre,samp {    font-family: "Anonymous Pro", Monaco, Menlo, "Noto Serif SC", monospace;}
```

## 优化加载速度

先修改原引入代码为

```
<link type="text/css" rel="preload stylesheet" as="style" href="https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&family=Noto+Serif+SC:wght@300;400;500;600;700&display=swap" crossorigin >
```

再在`</head>`前配置相关的DNS解析与字体缓存策略

代码如下

```
<link rel="dns-prefetch" href="https://fonts.googleapis.com/"><link rel="dns-prefetch" href="https://fonts.gstatic.com/"> <link rel="preconnect"      href="https://fonts.gstatic.com"      crossorigin /><noscript><link rel="stylesheet"      href="https://fonts.googleapis.com/css2      ?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700      &family=Noto+Serif+SC:wght@300;400;500;600;700&display=swap" onload="this.media='all'" /></noscript>
```

## 优化效果

配置好后在本地测试的效果如下

Ctrl+F5强制刷新  
![1](https://senorui.top/img/37d4/load.webp)

Ctrl+R刷新  
![2](https://senorui.top/img/37d4/preload.webp)

本人所用山东联通宽带网络均可正常且快速地加载Google Font的资源。

可以明显地看到第一次加载资源并缓存后，再次刷新调用的都是浏览器缓存的资源。

**本站测速结果如下**

![3](https://senorui.top/img/37d4/speed.webp)

**PS: 为了长链接能够在代码块内完整渲染，上述字体样式引用链接均做了断点处理。  
若要使用请删除相应的回车符或空格符。**

原文链接: https://senorui.top/posts/37d4.html