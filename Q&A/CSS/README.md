### Q & A
##### 1.`scrollHeight` vs `clientHeight` vs `offsetHeight`
`scrollHeight`: ENTIRE  content & padding (visible or not)
Height of all content + paddings, despite of height of the element.

`clientHeight`: VISIBLE content & padding
Only visible height: content portion limited by explicitly defined height of the element.

`offsetHeight`: VISIBLE content & padding + border + scrollbar.

Samewith `scrollWidth` vs `clientWidth` vs `offsetWidth`.

Refer: [stackOverflow](https://stackoverflow.com/questions/22675126/what-is-offsetheight-clientheight-scrollheight)

##### 2. `height` vs `line-height`.

`height` is the vertical measurement of the container.

`line-height` is the distance from the top of the first line of text to the top of the second.

You can center element vertically and horizontally by using `line-height`:
```html
<div>
    <span>Some Text</span>
<div>
```
```css
div {
    line-height: 100px;
    text-align: center;
}
```
