# jQuery常用监听页面滚动

当前滚动的地方的窗口顶端到整个页面顶端的距离：

var winPos = $(window).scrollTop();

获取指定元素的页面位置

$(val).offset().top;

对页面滚动条滚动的监听：要放在页面加载的时候

$(window).scroll(function(event){});

设置滚动条到指定位置

$(window).scrollTop(offset)
