# mip-options

mip-options 组件说明

标题|内容
----|----
类型|通用
支持布局|responsive,fixed-height,fill,container,fixed
所需脚本|https://c.mipcdn.com/static/v1/mip-options/mip-options.js

## 示例

### 基本用法
```html
<mip-options id="myoptions">
    <div class="price">
        <span on="tap:myoptions.setParam(order,DESC")>降序</span>
        <span on="tap:myoptions.setParam(order,ASC)">升序</span>
        <span on="tap:myoptions.setParam(order,DEFAULT)">默认</span>
    </div>
    <div class="color">
        <span on="tap:myoptions.setParam(color,red)">红色</span>
        <span on="tap:myoptions.setParam(color,blue)">蓝色</span>
        <span on="tap:myoptions.setParam(color,yellow)">黄色</span>
    </div>
    <div class="size">
        <span on="tap:myoptions.setParam(size,big)">大</span>
        <span on="tap:myoptions.setParam(color,middle)">中</span>
        <span on="tap:myoptions.setParam(color,small)">小</span>
    </div>
</mip-options>

```

## 注意事项

mip-options绑定`setParam`方法中的参数中间没有空格。

