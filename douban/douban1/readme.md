css 命名词汇
<!-- 当你应对起来比较困难的时候，说明水平还不够 
今晚对今后两条线的处理方案确立进行再次定性思考
不定性的态度是很正常的自然规律发展，因为相互都是如此，
用不着降低去适应对方,自然交互过程的本质是如此
所以结果永远是未定式的
-->
feeds *-item
html结构及布局
从上到下，左到又，语义性，功能性
1. 结构套路
 content>h3+p
2. 盒子
3. a作为盒子，在移动端是很正常的
display：block
4. 盒子模型
文字line-height  padding  margin
5. 文字截断
tmall 商铺信息是由商家填的，它的高度，不被限制，
display:-webkit-box;新的盒子模型，像flex来划分父元素的空间
overflow:hidden;
-webkit-line-clamp 行数
-webkit-box-orient:vertical;
6. 浮动 float：left|right
离开文档流
在一个盒子里，将要浮动的元素写在最前面
左右布局,
在flex布局之前，我们一般借助于float来布局
图片的宽高，宽度用百分比，自适应的需求，
高度方面？div padding-top:自身的宽度来做比例100%  正方形。
自适应设备里盒子的等比例设置 width 百分比
高度用padding-top
明天详细讲：弹性布局，浮动，盒子
！