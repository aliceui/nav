# Nav - 导航

---

主导航样式，支持两级菜单。

---

## 演示文档

<link type="text/css" rel="stylesheet" media="screen" href="dist/nav.css">

### 默认用法

````html
<div class="ui-nav">
  <ul class="ui-nav-main">
    <li class="ui-nav-item">
      <a href="#">一级导航 1</a>
      <ul class="ui-nav-submain">
        <li class="ui-nav-subitem ui-nav-subitem-current"><a href="#">二级导航 1-1</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 1-2</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 1-3</a></li>
      </ul>
    </li>
    <li class="ui-nav-item ui-nav-item-current">
      <a href="#">一级导航 2</a>
      <ul class="ui-nav-submain">
        <li class="ui-nav-subitem"><a href="#">二级导航 2-1</a></li>
        <li class="ui-nav-subitem ui-nav-subitem-current"><a href="#">二级导航 2-2</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 2-3</a></li>
      </ul>
    </li>
    <li class="ui-nav-item">
      <a href="#">一级导航 3</a>
      <ul class="ui-nav-submain">
        <li class="ui-nav-subitem"><a href="#">二级导航 3-1</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 3-2</a></li>
        <li class="ui-nav-subitem ui-nav-subitem-current"><a href="#">二级导航 3-3</a></li>
      </ul>
    </li>
    <li class="ui-nav-item"><a href="#">一级导航 4</a></li>
  </ul>
  <div class="ui-nav-subcontainer"></div>
</div>
````

### 不显示二级导航

````html
<div class="ui-nav ui-nav-nosub">
  <ul class="ui-nav-main">
    <li class="ui-nav-item">
      <a href="#">一级导航 1</a>
      <ul class="ui-nav-submain">
        <li class="ui-nav-subitem ui-nav-subitem-current"><a href="#">二级导航 1-1</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 1-2</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 1-3</a></li>
      </ul>
    </li>
    <li class="ui-nav-item ui-nav-item-current">
      <a href="#">一级导航 2</a>
      <ul class="ui-nav-submain">
        <li class="ui-nav-subitem"><a href="#">二级导航 2-1</a></li>
        <li class="ui-nav-subitem ui-nav-subitem-current"><a href="#">二级导航 2-2</a></li>
        <li class="ui-nav-subitem"><a href="#">二级导航 2-3</a></li>
      </ul>
    </li>
  </ul>
  <div class="ui-nav-subcontainer"></div>
</div>
````
