#SVG

Scalable Vector Graphics, SVG, is a W3C XML dialect to mark up graphics. It is partially implemented in Firefox, Opera, WebKit browsers, Internet Explorer and other browsers.

##getting started

* SVG 指可伸缩矢量图形 (Scalable Vector Graphics)
* SVG 用来定义用于网络的基于矢量的图形
* SVG 使用 XML 格式定义图形
* SVG 图像在放大或改变尺寸的情况下其图形质量不会有所损失
* SVG 是万维网联盟的标准
* SVG 与诸如 DOM 和 XSL 之类的 W3C 标准是一个整体

##Intruction

* **矩形 <rect>**
* **圆形 <circle>**
* 椭圆 <ellipse>
* 线 <line>
* 折线 <polyline>
* 多边形 <polygon>
* **路径 <path>**

##demo

    <svg>
        <rect id='rectId' class='rectClass' name='rectName' width="300" height="100"
              style="fill:rgb(0,0,255);"></rect>
    </svg>

in HTML you will get a [recangle](.\svgTutorial.svg).

##SVG and HTML

    document.getElementById('')

In HTML the elements should be assigned with atrribute like id, class, name, etc. So a svg with out id is horrible. Unfortunately, in NingBo Project, we have none of them.

##add id to svg

1. edit the code

2. Adobe Illustrator