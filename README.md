# Responsive-website
*******响应式JS*******：
<br>
1.原理：动态添加font-size根元素,浏览器根据添加的根元素来进行自动调整
<br>
*******注意事项*******：
<br>
2.页面布局尽量采用flex流动式布局
<br>
3.例如最外层div设置width：100%   内容区div（template） width：86%（宽度会随着浏览器的宽度变化而变化），内部的div采用display：flex
<br>
4.flex布局请参照:https://blog.csdn.net/lm9948/article/details/80732702
<br>
5.页面元素单位除了字体单位采用px像素外，其余所有的元素单位采用 rem单位  具体1rem=？px 请根据实际的设计稿和需求进行设置（详情请看responsive.js注释）
