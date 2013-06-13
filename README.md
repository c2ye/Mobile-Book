移动终端开发指南
==================

##前言：##

移动开发知识太过零散，不知从何开始，想到的先堆在这里，内容多了以后再整理，算是个开始吧。

本页内容全部来源于互联网，如有侵权请速度联系我们删除。


##基本设置##

    <meta name="viewport" content=" width=device-width, initial-scale=1, maximum-scale=1">

##问题解决##

背景图2倍再使用背景缩放

    -webkit-background-size: 60px 200px;

消除 transform 旋转后的锯齿

    -webkit-transform: skew(25deg) translateZ(0);

去掉 input 的内阴影

    -webkit-appearance: caret;

去掉点击高亮反馈

    -webkit-tag-highlight-color: rgba(0,0,0,0);

禁止选中

    -webkit-user-select: none; user-select: none;

禁止数字自动识别

    <meta name="format-detection" content="telephone=no" />


更多 webkit 私有属性，请看: <http://ued.ctrip.com/blog/wp-content/webkitcss/>





