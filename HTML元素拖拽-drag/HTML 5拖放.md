## HTML 5拖放

浏览器支持：IE9、Firefox、Opera 12、Chrome以及Safari 5

1. 设置元素可拖放

```
<img draggable="true">
```

2. ondragstart

> 当拖拽元素开始被拖拽的时候触发的事件，此事件作用于被拖拽元素上

3. ondragenter

>当拖拽元素进入目标元素时触发，此事件作用于目标元素

4. ondragover

> 当拖拽元素在目标元素上移动时触发，作用于目标元素，ondragover规定在何处放置被拖动的数据

**默认情况下，无法将数据/元素放置到其他元素中，如果需要设置允许放置，必须阻止对元素的默认处理方式，所有需要通过调用ondragover事件的event.preventDefault()方法**

```
event.preventDefault()
```

5. ondrop

> 当放置被拖数据时，触发drop事件，此事件作用于目标元素

6. ondragend

> 当拖拽完成后触发的事件，此事件作用于被拖拽元素上

