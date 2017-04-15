# 博客前端项目实战
## <a name='preface'>前言</a> ##
*因为github在线预览不支持数据库文件，所以该项目只能用本人电脑才能展示*
封装博客项目中用到的javascript库 学习过程来自于北风网的李炎辉老师提供的javascript教程

学习目的是 深入理解javascript的封装，并把不同浏览器的兼容问题封装解决方法。

 **需要 实现的功能列表暂时为：**
 
  1. 参考jquery的实现原理，封装base.js库，可以实现dom节点的连缀操作，仿css选择器的操作功能，在这个基础上利用原型链封装各种方法，实现操作；
  
  2.完成博客网页的基本布局，实现导航栏下拉菜单的功能， 鼠标移动菜单出现移出菜单消失带有动画效果，下拉菜单中有博客发文，界面换肤的功能等选项；
  
  3.弹出登录框，要求自适应居中，弹出时锁定屏幕，不允许其他操作，关闭时可以解锁屏幕，解放操作；
  
  4.封装拖拽功能，实现弹出框按下头部可以拖拽，放下可以停止，并且活动范围为可视区域，兼容各个浏览器（已封装成插件）；
  
  5.封装事件绑定方法，兼容各个浏览器的事件绑定，解除事件的函数；
  
  6.封装浏览器检测函数，可以检测使用的不同浏览器；
  
  7.封装DOM加载，仿照JQ的ready方法，让网页可以在dom加载完毕后就执行js文件，而不是等到图片等所有文件全部加载完以后才执行；
  
  8.封装动画方法，实现常见的：透明度，长度，宽度，移动的动画效果；
  
  9.实现百度分享侧边栏效果，鼠标移入，分享栏移入屏幕，鼠标移出，分享栏回到侧边屏幕内；
  
  10.制作滑动导航栏，实现一些较为炫酷的动画效果，伴随鼠标的移入移除，导航栏滑块动态移动，文字列表跟着发生变化；
  
  11.实现文章列表的菜单切换功能，点击伸缩列表；
  
  13.创建注册验证表单，带有弹出框的效果，并且填写的信息可以进行验证，验证通过后可以进行提交；
  
  14.轮播器效果，实现图片轮播图，并给与两种移动方式可以切换，透明度和移动两种效果；
  
  15.延迟加载功能，图片瀑布流效果，当图片进入可视区域再加载图片，加载过程有动画的透明度变化效果，为网站节省不必要的流量；
  
  16.点击小图可以弹出大图的弹窗，并且实现图片预加载功能，在图片没有加载好的时候有一个过度的图片效果，加载过程有动画的透明度变化效果；
  
  17.引入AJAX，实现表单的异步验证，注册可以向数据库提交数据，可以验证账户是否存在，登陆可以验证密码和账号；
  
  18.AJAX发文系统，发表文章可以上传到数据库，再加载到网页；
  
  19.AJAX换肤功能，可以更换网页的背景效果，并且通过AJAX，实现在其他客户端打开网页也能换肤的效果；
  
  ## <a name='todoList'>接下来要完善的功能</a>
