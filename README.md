# jquery.fullPage.js
### Usage
`这是一个全屏滚动插件，支持鼠标点击、滑轮和键盘事件，可以上下或是左右全屏滚动。`
```html
<div id="container">
    <div class="sections">
        <div class="section" id="section0">
            <div class="intro">
            </div>
        </div>
        <div class="section" id="section1">
            <div class="intro">
            </div>
        </div>
        <div class="section" id="section2">
            <div class="intro">
            </div>
        </div>
        <div class="section" id="section3">
            <div class="intro">
            </div>
        </div>
    </div>
</div>
```
> *引入jquery和fullpage.js后:*

```javascript
$("#container").PageSwitch();
```
插件默认配置参数说明:
```
var defaults = {
    selectors: {
        sections: ".sections",
        section: ".section",
        page: ".pages",
        active: ".active"
    },
    index: 0,
    easing: "ease",
    duration: 500,
    loop: true,
    pagination: true,
    keyboard: true,
    direction: "vertical", //horizator
};
```
- selectors：选择器，可以自定义选择器(其中page和active是右边小圆点的class)；
- index 索引 表示初始化时从第几页展示，默认值0；
- easing 动画效果 支持jquery animate的各种动画效果；
- duration：动画效果的过渡时间；
- loop 是否可以无限滚动 默认值true；
- pagination:分页 默认值为true；
- keyboard：键盘事件，是否支持上下左右键事件
- direction:滚动方向，有竖直和水平可选；

### feedback
email:`li.zhixiang@live.cn`

### 参考教程
慕课网 [http://www.imooc.com/course/236](http://www.imooc.com/course/236)