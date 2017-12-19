# XYZReader
这是一个在线阅读器，得到初始代码之后，遇到了很多对于用户不友好的UI设计，我将根据Material Design原则重新设计，具体遇到问题和解决方法如下：
<h4>缺点</h4>
<ol>
<li>主页空间使用不合理</li>
<li>界面使用颜色不合理，使得读者难以阅读</li>
<li>logo显示异常模糊</li>
<li>具体项目页，toolbar排版糟糕</li>
<li>文章字体颜色过浅，无法阅读</li>
</ol>
<h4>修改</h4>
<ol>
<li>因为个人兴趣，所以优先修改的是具体页面的toolbar问题，使用到了CoordinatorLayout,以及AppCompat 扩展而来的应用主题。AppBar和Toolbar进行设置</li>
<li>追加动画效果</li>
<li>调整ImageButton为FloatingActionButton</li>
<li>调整detail页的颜色使用</li>
</ol>

