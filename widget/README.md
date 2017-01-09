# 店铺装修样式命名规范#

> 适用于天猫，淘宝店铺装修样式命名。
>
> 关于css 样式的使用，必须定购淘宝提供的旺铺css服务，订购：[旺铺CSS](https://fuwu.taobao.com/ser/detail.html?spm=a1z13.8114210.1234-fwlb.12.YzobpL&service_code=ARTICLE_WANGPU_PLUS&from_key=css&tracelog=search)



- ## 目录##

  1. [下拉菜单](下拉菜单)
  2. [功能模块](功能模块)
  3. [基础样式](基础样式)


- ### 下拉菜单###


```html
<!--导航条-->
<a class="list1-trigger01" title="春上新" target="_blank" href="#">2017春上新</a>
<!--下拉菜单-->
<div class="J_TWidget hidden" data-widget-type="Popup" data-widget-config="{
          'trigger':'.list1-trigger01',
          'align':{
                  'node':'.list1-trigger01',
                  'offset':[0,0],
                  'points':['cr','cc']
                  }
            }">
  <ul class="shy_dh">
    <li> <a href="#" target="_blank">春上新第一波</a> </li>
    <li> <a href="#" target="_blank">春上新第二波</a> </li>
    <li> <a href="#" target="_blank">春上新第三波</a> </li>
  </ul>
</div>
<!--自定义css-->
.shy_dh li a {
	padding: 10px 20px;
	color: #000;
	display: block;
	text-decoration: none;
}
.shy_dh li a:hover {
	background: #000;
	color: #fff;
}
```

