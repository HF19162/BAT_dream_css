PC mobile?
mobile first
flex 弹性布局在老版浏览器里不适合用，很容易出现兼容性问题，要IE10及以上；
布局：当不方便使用弹性布局的时候，浮动布局float是个很好的选择，撑起来PC布局
float会离开文档流
BFC
float 离开文档流跟position:absolute不一样
float是魔鬼，会影响兄弟元素
两列式布局，出了float还有谁？
定位仅仅用作定位，绝对不应该直接用于布局 