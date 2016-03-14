#### jQuery的自定义内容滚动条

```html
<link rel="stylesheet" href="css/jquery.mCustomScrollbar.css" />
<script type="text/javascript" src="js/jquery-1.8.0.min.js"></script>
<script src="js/jquery.mCustomScrollbar.concat.min.js"></script>
```

```html
<div class="content" data-mcs-theme="dark">
   <!-- your content -->
</div>
```

```js
<script>
    $(function(){
	 $(".content").mCustomScrollbar();
    })
</script>
```

效果演示：http://itmyhome.com/jquery_scroller/