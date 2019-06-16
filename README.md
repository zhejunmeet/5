# 5

巩固浏览高程前几章基础内容，这周重点看了事件和画图（因为重点勾画2333</br>
事件冒泡</br>
事件补充</br>
事件三个阶段</br>
1.捕获阶段 </br>
2.当前目标阶段 </br>
3.冒泡阶段 </br>
事件对象.eventPhase可以查看事件出发时所处的阶段</br>
事件对象的属性和方法</br>
   event.type 获取事件类型</br>
   clienX/clientY 所有浏览器都支持，窗口位置</br>
   pageX/pageY IE以前不支持，页面位置</br>
   event.target  event.sreElement 用于获取触发事件的元素</br>
   event.preventDefault()取消默认行为</br>
阻止事件传播方式</br>
   event.stopPropagation(); </br>
常用鼠标和键盘事件</br>
   onmouseuo鼠标按键放开时触发</br>
   onmousedown鼠标按键按下触发</br>
   onmousemove鼠标移动触发</br>
   onkeyup键盘按键按下触发</br>
   onkeydown键盘按键抬起触发</br>

Cancas</br>
<cancas> width height </br>
  var drawing = document.getElementById("drawing"); </br>
  if (drawing.getContext){  </br>
   var context = drawing.getContext("2d");</br>
   context.strokeStyle = "red";</br>
   context.fillStyle = "#0000ff";</br>
  }</br>
矩形 fillRect  strokeRect  clearRect;</br>
路径</br>
文本 fillText strokeText</br>
变换 阴影 渐变createLinearGradient  creatRadialGradient</br>
模式 图像 数据合成</br>
