### 2d primitives

- arc 圆

      arc(a,b,c,d,start,stop,[mode])
    
      arc(x,y,w,h,start,stop,[绘制方式])

      a	Number: x-coordinate of the arc's ellipse
      
      b	Number: y-coordinate of the arc's ellipse
      
      c	Number: width of the arc's ellipse by default
      
      d	Number: height of the arc's ellipse by default
      
      start	Number: angle to start the arc, specified in radians
      
      stop	Number: angle to stop the arc, specified in radians
      
      mode	Constant: optional parameter to determine the way of drawing the arc. Parameter options are OPEN, CHORD or PIE
      

- ellipse 椭圆
    
      ellipse(x,y,w,[h])
      ellipse(x,y,w,[h])
      
- line 线
>line(x1,y1,x2,y2)

        x1: 第一个点的x坐标
        y1: 第一点的y坐标
        x2: 第二点的x坐标
        y2: 第二点的y坐标
- point 点

       point(x,y)
       
- quad 四边形

        quad(x1,y1,x2,y2,x3,y3,x4,y4)
     
- triangle 三角形

        triangle(30, 75, 58, 20, 86, 75);