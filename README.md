# dragula
拖放元素，用于两个容器之间拖放复制排序等功能<br>
<img src="http://www.wware.org/img/111s.png" width="400px"><br>
普通属性<br>
data-copy	元素默认移动，不复制。如果设置为true,可以移动复制。	false/true<br>
data-moves	元素默认是可拖动的，设置为false则不能拖拽。	false/true<br>
data-accepts	元素可以在默认情况下放入任何“容器”中，设置为false为禁止状态。	false/true<br>
data-copySortSource	针对复制元素启作用状态，如果设置为false两容器元素不能排序，如果设置为true两容器元素可以排序；(该按钮是和复制copy为true状态下配合使用)	false/true<br>
data-revertOnSpill	如果设置为true，拖拽元素拖到另一个容器外但这个容器内有拖拽元素的阴影，则不能拖拽到该容器，否则相反；	true/false<br>
data-removeOnSpill	如果设置为true，将元素拖拽到容器之外则将该元素删除，设置为false，则不能删除，如果元素使用复制状态(copy设置为true)，怎该功能不启作用。	true/false<br>
data-direction	当一个元素被放到一个容器上时，它将被放置在鼠标释放点附近。如果设置为vertical，则会为哦、默认值即Y轴元素最下边，如果设置为horizontal，则会考虑为X轴就是鼠标的随意位置。	vertical/horizontal<br>
输出属性<br>
data-x-lefthtml	左边框文本内容	<br>
data-x-righthtml	右边框文本内容<br>
# 说明
1、元素内容1和元素内容2,这两边的内容可以随意拖放.<br>
2、左右拖放可以设置样式,在class为wrapper:添加样式 display:table,分别在class为container 添加样式<br>
display:table-cell;border:1px solid #f00;<br>
