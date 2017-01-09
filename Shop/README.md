# 店铺装修-淘系 #

> 总结天猫（淘宝），店铺装修常用布局，模块，样式等内容，进行归纳整理和分享。
>
> CSS样式命名：[]

## 目录##

1. [布局](#布局)
2. [模块](#模块)
3. [CSS样式](#CSS样式) 

   ​

- ### 布局###

  - 常规布局
    1. 1920px全屏布局

  ```html
  <div class="layout-1920" style="height:500px";> 这里是放全屏布局的内容</div>
  ```

  ​	2. 1200px商品模块

  ```html
  <div class="layout-1200" style="height:500px";> 这里是放宽度为1200px的内容</div>
  ```

  ​	3. 1150px商品模块

  ```html
  <div class="layout-1150" style="height:500px";> 这里是放宽度为1200px的内容</div>
  ```

  ​	4. 1100px商品模块

  ```html
  <div class="layout-1100" style="height:500px";> 这里是放宽度为1200px的内容</div>
  ```

  - 叠加布局

  ```html
  <div style="width:1920px;height:500px;">
  	<div class="layout-1920" style="height:750px;">
        两层叠加效果，上面一层高度为500px，下面一层高度为750px
       </div> 
  </div>
  ```

  > 布局的宽度可选用`layout-1920` `layout-1200` `layout-1150` `layout-1100` 

- ### 模块

  - 滑动背景

  ```html
  <div class="layout-1920" style="background:url(背景图片地址.jpg) center no-repeat fixed;background-position: 50% 20px; height:1910px;">
    <div style="width:1200px;margin:0 auto;">
      背景图片，高度根据需要编辑，宽度为1200px的展示内容
    </div>
  </div>
  ```

  ​

  - #### ####

