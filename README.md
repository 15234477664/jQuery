# jQuery常用监听页面滚动

当前滚动的地方的窗口顶端到整个页面顶端的距离：

var winPos = $(window).scrollTop();

获取指定元素的页面位置

$(val).offset().top;

对页面滚动条滚动的监听：要放在页面加载的时候

$(window).scroll(function(event){});

设置滚动条到指定位置

$(window).scrollTop(offset)

# 关于scrollTop,offsetTop,scrollLeft,offsetLeft用法介绍
页可见区域宽： document.body.clientWidth;

网页可见区域高： document.body.clientHeight;

网页可见区域宽： document.body.offsetWidth (包括边线的宽);

网页可见区域高： document.body.offsetHeight (包括边线的宽);

网页正文全文宽： document.body.scrollWidth;

网页正文全文高： document.body.scrollHeight;

网页被卷去的高： document.body.scrollTop;

网页被卷去的左： document.body.scrollLeft;

网页正文部分上： window.screenTop;

网页正文部分左： window.screenLeft;

屏幕分辨率的高： window.screen.height;

屏幕分辨率的宽： window.screen.width;

屏幕可用工作区高度： window.screen.availHeight;
