---
layout: page
title: Icon
---

Icon 提供了 Mailcup 所用到的图标字体方案

你可以在下面的CSS文件里找到 `_icon.scss`.

* 此处不用改，将下面所有的 2 级标题制成索引...
{:toc}

##引入图标
在需要使用图标的地方直接使用

{% example html %}
<span class="mc-icon-clip"> clip</span>
{% endexample %}

##所有可用的图标
在需要使用图标的地方直接使用

{% example html %}
<div class="row">
<div class="col-md-3"><span class="mc-icon-clip btn-lg"> clip</span></div>
<div class="col-md-3"><span class="mc-icon-pin btn-lg"> pin</span></div>
<div class="col-md-3"><span class="mc-icon-clock btn-lg"> clock</span></div>
<div class="col-md-3"><span class="mc-icon-search btn-lg"> search</span></div>
</div>
<div class="row">
<div class="col-md-3"><span class="mc-icon-paper btn-lg"> paper</span></div>
<div class="col-md-3"><span class="mc-icon-close btn-lg"> close</span></div>
<div class="col-md-3"><span class="mc-icon-alldone btn-lg"> alldone</span></div>
<div class="col-md-3"><span class="mc-icon-done btn-lg"> done</span></div>
</div>
<div class="row">
<div class="col-md-3"><span class="mc-icon-expand btn-lg"> expand</span></div>
<div class="col-md-3"><span class="mc-icon-dropdown btn-lg"> dropdown</span></div>
<div class="col-md-3"><span class="mc-icon-label btn-lg"> label</span></div>
<div class="col-md-3"><span class="mc-icon-more btn-lg"> more</span></div>
</div>
<div class="row">
<div class="col-md-3"><span class="mc-icon-setting btn-lg"> setting</span></div>
<div class="col-md-3"><span class="mc-icon-back btn-lg"> back</span></div>
<div class="col-md-3"><span class="mc-icon-forward btn-lg"> forward</span></div>
<div class="col-md-3"><span class="mc-icon-reply btn-lg"> reply</span></div>
</div>
<div class="row">
<div class="col-md-3"><span class="mc-icon-replyall btn-lg"> replyall</span></div>
<div class="col-md-3"><span class="mc-icon-foucus btn-lg"> foucus</span></div>
<div class="col-md-3"><span class="mc-icon-unfocus btn-lg"> unfocus</span></div>
<div class="col-md-3"><span class="mc-icon-textlist btn-lg"> textlist</span></div>
</div>
<div class="row">
<div class="col-md-3"><span class="mc-icon-numlist btn-lg"> numlist</span></div>
</div>
{% endexample %}

##图标尺寸
图标大小分为三种

* 默认尺寸，不需要指定
* `.btn-sm` 小尺寸
* `.btn-lg` 大尺寸

{% example html %}
<span class="mc-icon-clip btn-sm"> clip</span>
<span class="mc-icon-clip"> clip</span>
<span class="mc-icon-clip btn-lg"> clip</span>
{% endexample %}

##应用实例
可以把它们应用到按钮、工具条中的按钮组、导航或输入框等地方

{% example html %}
<button type="button" class="btn btn-default btn-lg" aria-label="Left Align">
  <span class="mc-icon-pin" aria-hidden="true"> Confirm</span>
</button>

<button type="button" class="btn btn-default" aria-label="Left Align">
  <span class="mc-icon-pin" aria-hidden="true"> Confirm</span>
</button>

##颜色

{% example html %}
<span class="mc-icon-clip btn-lg darkblue"> clip</span>
<span class="mc-icon-clip btn-lg midgrey"> clip</span>
<span class="mc-icon-clip btn-lg midblue"> clip</span>

{% endexample %}