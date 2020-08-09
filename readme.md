## 基于 vue 的 auto_complete 组件
输入框选择框。  
在输入框的下面给出建议（element-ui实现了）  
https://element.eleme.cn/#/zh-CN/component/input  
想了很久，终于想明白了。
> select 标签不支持 js 触发，于是手动模拟写\<select>
>如 bootstrap 一样

```html
<div class="auto_complete">
  <input type="text">
  <ul>
    <li>xxx</li>
    <li>222</li>
</ul>
</div>
```
```css

```