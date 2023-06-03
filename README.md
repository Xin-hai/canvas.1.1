# canvas.1.1
canvas 简易画图

## 禁用缩放
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
  
  
## 防止移动端跳动
    body {
    height: 100vh;
    overflow: hidden;
    }
   
    
    
## 填充样式、优化显示锯齿状、线段粗细
      ctx.fillStyle = "black";
      ctx.strokeStyle = "black";
      ctx.lineCap = "round";
      ctx.lineJoin = "round";
      ctx.lineWidth = 8;
      
 ## 区分移动端和PC端
     let isTouchDevice = "ontouchstart" in document.documentElement;
 当isTouchDevice为true时为移动端，false为PC端
 
 
     
