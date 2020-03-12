# accordion
使用jQuery动画制作的手风琴菜单  
https://longteng33.github.io/accordion  
1、为每个nav title添加点击事件，每当点击时为当前元素toggleClass，同时使紧挨它的兄弟元素slideToggle  
2、如果不允许同时展开多个subNav，那么在点击每个title时，获取当前元素的父元素的兄弟元素的子元素中有一样className的，removeClass
3、同时使紧挨它的兄弟元素slideUp