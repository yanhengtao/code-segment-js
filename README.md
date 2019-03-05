##### 1、 jquery 的三种初始化方法

> 第一种
```
$(document).ready(function(){
  // do somethings
});
```
> 第二种
```
$(function(){
  // do somethings
});
```
> 第三种
```
jQuery(function($){
  // do somethings
});
```

##### 2、删除div中的内容 ，但是保留这个div

> <div id="test">这是要删除的内容，还要保留test本身</div>

> 1、原生js法
```
document.getElementById('test').innerHTML = '';
```
> 2、jQuery法
```
$('#test').empty();   // jQuery方法一
$('#test').html('');  // jQuery方法二
```
     
