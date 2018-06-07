# -浮动
浮动的框可以向左或向右移动，直到它的外边缘碰到包含框或另一个浮动框的边框为止。
由于浮动框不在文档的普通流中，所以文档的普通流中的块框表现得就像浮动框不存在一样。

不浮动代码：
<div style="border: solid 5px #0e0; width:300px;">
        <div style="height: 100px; width: 100px; background-color: Red;">
        </div>
        <div style="height: 100px; width: 100px; background-color: Green; ">
        </div>
        <div style="height: 100px; width: 100px; background-color: Yellow;">
        </div>
    </div>
    
