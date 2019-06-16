# 5

巩固浏览高程前几章基础内容，这周重点看了事件和画图（因为重点勾画2333
事件冒泡
事件补充
事件三个阶段
1.捕获阶段 
2.当前目标阶段 
3.冒泡阶段 
事件对象.eventPhase可以查看事件出发时所处的阶段
事件对象的属性和方法
   event.type 获取事件类型
   clienX/clientY 所有浏览器都支持，窗口位置
   pageX/pageY IE以前不支持，页面位置
   event.target  event.sreElement 用于获取触发事件的元素
   event.preventDefault()取消默认行为
阻止事件传播方式
   event.stopPropagation();
常用鼠标和键盘事件
   onmouseuo鼠标按键放开时触发
   onmousedown鼠标按键按下触发
   onmousemove鼠标移动触发
   onkeyup键盘按键按下触发
   onkeydown键盘按键抬起触发

Cancas
<cancas> width height
  var drawing = document.getElementById("drawing");
  if (drawing.getContext){
   var context = drawing.getContext("2d");
   context.strokeStyle = "red";
   context.fillStyle = "#0000ff";
  }
矩形 fillRect() strokeRect() clearRect()
路径
文本 fillText strokeText()
变换 阴影 渐变createLinearGradient() creatRadialGradient()
模式 图像 数据合成
