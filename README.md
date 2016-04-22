# laba8
Моя лаба 8
<html>
<head>
<title>Canvas</title>
</head>
<body>
<canvas id="myCanvas" width="1000" height="1000">
<p>Ваш браузер не поддерживает рисование.</p>
</canvas>
</body>
</html>
<script type="text/javascript">
var myCanvas = document.getElementById('myCanvas');
var ctx = myCanvas.getContext('2d');

//сторона 1
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 3;
ctx.moveTo(150,165);
ctx.lineTo(150,285);
ctx.lineTo(165,300);
ctx.lineTo(285,300);
ctx.lineTo(300,285);
ctx.lineTo(300,165);
ctx.lineTo(285,150);
ctx.lineTo(165,150);
ctx.closePath();
ctx.fillStyle = 'yellow';
ctx.fill();
ctx.stroke();
//сторона 2
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 3;
ctx.moveTo(165,150);
ctx.lineTo(200,110);
ctx.lineTo(320,110);
ctx.lineTo(285,150);
ctx.closePath();
ctx.fillStyle = 'blue';
ctx.fill();
ctx.stroke();
//уголок
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 3;
ctx.moveTo(300,165);
ctx.lineTo(335,125);
ctx.lineTo(320,110);
ctx.lineTo(285,150);
ctx.closePath();
ctx.fillStyle = 'purple';
ctx.fill();
ctx.stroke();
//сторона 3
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 3;
ctx.moveTo(300,165);
ctx.lineTo(335,125);
ctx.lineTo(335,245);
ctx.lineTo(300,285);
ctx.closePath();
ctx.fillStyle = 'red';
ctx.fill();
ctx.stroke();
//круги на 1 стороне
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 5;
ctx.arc(180, 180, 8, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'black';
ctx.fill();
ctx.stroke();
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 5;
ctx.arc(180, 270, 8, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'black';
ctx.fill();
ctx.stroke();
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 5;
ctx.arc(270, 180, 8, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'black';
ctx.fill();
ctx.stroke();
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 5;
ctx.arc(270, 270, 8, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'black';
ctx.fill();
ctx.stroke();
ctx.beginPath();
ctx.strokeStyle = 'dark'; 
ctx.lineWidth = 5;
ctx.arc(225, 225, 8, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'black';
ctx.fill();
ctx.stroke();
//круги 2 стороны
ctx.beginPath();
ctx.scale(2, 1); 
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;
ctx.arc(105, 130, 5, 0, Math.PI*2, true);
ctx.resetTransform();
ctx.closePath();
ctx.fillStyle = 'dark';
ctx.fill(); 
ctx.stroke();
ctx.beginPath();
ctx.scale(2, 1); 
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;
ctx.arc(135, 130, 5, 0, Math.PI*2, true);
ctx.resetTransform();
ctx.closePath();
ctx.fillStyle = 'dark';
ctx.fill(); 
ctx.stroke();
//круги 3 стороны
ctx.beginPath();
ctx.scale(1, 2); 
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;
ctx.arc(320, 100, 5, 0, Math.PI*2, true);
ctx.resetTransform();
ctx.closePath();
ctx.fillStyle = 'dark';
ctx.fill(); 
ctx.stroke();
//текст
ctx.fillStyle = "black";
ctx.font = 'bold 30px sans serif';
ctx.fillText("Вариант №9, М-11, Миншатов А.", 40, 400);

</script>
