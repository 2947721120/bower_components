
<!---

This README is automatically generated from the comments in these files:
demo-snippet.html  url-bar.html

Edit those files, and our readme bot will duplicate them over here!
Edit this file, and the bot will squash your changes :)

The bot does some handling of markdown. Please file a bug if it does the wrong
thing! https://github.com/PolymerLabs/tedium/issues

-->

[![Build status](https://travis-ci.org/PolymerElements/iron-demo-helpers.svg?branch=master)](https://travis-ci.org/PolymerElements/iron-demo-helpers)

_[演示和API文档](https://elements.polymer-project.org/elements/iron-demo-helpers)_


##&lt;demo-snippet&gt;

`demo-snippet` 是显示一个代码片段的来源一个辅助元素，
其呈现的演示。它可以用于两种天然元素和
聚合物元件

```html
本地元素演示示例

    <demo-snippet>
      <template>
        <input type="date">
      </template>
    </demo-snippet>

一个聚合物的例子 <paper-checkbox> demo

    <demo-snippet>
      <template>
        <paper-checkbox>Checkbox</paper-checkbox>
        <paper-checkbox checked>Checkbox</paper-checkbox>
      </template>
    </demo-snippet>
```

### Styling

下面的自定义属性和混入可供造型:

| Custom property | Description | Default |
| --- | --- | --- |
| `--demo-snippet` | Mixin applied to the entire element | `{}` |
| `--demo-snippet-demo` | Mixin applied to just the demo section | `{}` |
| `--demo-snippet-code` | Mixin applied to just the code section | `{}` |



##&lt;url-bar&gt;

`url-bar` 是显示一个简单的只读的地址栏，如果一个辅助元素
且仅当该网页是在iframe。通过这种方式，我们可以试玩元素
应对我们基于iframe的演示环境的网址.

如果页面是不是在iframe中，不显示的URL栏元素.

### Styling

下面的自定义属性和混入可供造型:

| Custom property | Description | Default |
| --- | --- | --- |
| `--url-bar` | Mixin applied to the entire element | `{}` |


