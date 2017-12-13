### Vertex

#### beginContour
>beginContour()
        
        使用beginContour（）和endContour（）函数在形状（如字母“O”的中心）内创建负形状。beginContour（）开始记录形状的顶点，endContour（）停止记录。定义负形状的顶点必须沿着与外形相反的方向“缠绕”。首先为外部顺时针顺序绘制顶点，然后对于内部形状，逆时针绘制顶点形状。 
        
        这些函数只能在beginShape（）/ endShape（）对中使用，而translate（），rotate（）和scale（）等变换在beginContour（）/ endContour（）对中不起作用。也不可能使用其他形状，例如ellipse（）或rect（）。
              
#### beginShape
>beginShape([kind])

        使用beginShape（）和endShape（）函数可以创建更复杂的表单。beginShape（）开始记录一个形状的顶点，endShape（）停止记录。kind参数的值告诉它从提供的顶点创建哪些类型的形状。没有指定模式，形状可以是任何不规则的多边形。 
        
        可用于beginShape（）的参数是POINTS，LINES，TRIANGLES，TRIANGLE_FAN，TRIANGLE_STRIP，QUADS和QUAD_STRIP。在调用beginShape（）函数后，必须遵循一系列的vertex（）命令。要停止绘制形状，请调用endShape（）。每个形状将用当前的笔划颜色进行概述，并填充填充颜色。 
        
        translate（），rotate（）和scale（）等转换在beginShape（）中不起作用。在beginShape（）中也不可能使用其他形状，例如ellipse（）或rect（）。

#### endShape
>endShape([mode])
        
        mode	常数：使用CLOSE关闭形状

### bezierVertex
>bezierVertex(x2,y2,x3,y3,x4,y4)
        
        x2: 第一个控制点的x坐标
        y2: 第一个控制点的y坐标
        x3: 第二个控制点的x坐标
        y3: 第二个控制点的y坐标
        x4: 定位点的x坐标
        y4: 定位点的y坐标
        指定贝塞尔曲线的顶点坐标。每次调用bezierVertex（）都会定义贝塞尔曲线的两个控制点和一个锚点的位置，将新的线段添加到线条或形状中。 
        
        第一次在beginShape（）调用中使用bezierVertex（）时，必须先调用vertex（）来设置第一个定位点。只有当beginShape（）没有指定MODE参数时，才能在beginShape（）和endShape（）之间使用此函数。
        
### curveVertex 指定曲线的顶点坐标
>curveVertex(x,y)
        
            x: 顶点的x坐标
            y: 顶点的y坐标

### endContour 使图像闭合
>endContour()

        使用beginContour（）和endContour（）函数在形状（如字母“O”的中心）内创建负形状。beginContour（）开始记录形状的顶点，endContour（）停止记录。定义负形状的顶点必须沿着与外形相反的方向“缠绕”。首先为外部顺时针顺序绘制顶点，然后对于内部形状，逆时针绘制顶点形状。 
        
        这些函数只能在beginShape（）/ endShape（）对中使用，而translate（），rotate（）和scale（）等变换在beginContour（）/ endContour（）对中不起作用。也不可能使用其他形状，例如ellipse（）或rect（）。

### quadraticVertex
>quadraticVertex(cx,cy,x3,y3)

        指定二次贝塞尔曲线的顶点坐标
        cx: 控制点的x坐标
        cy: 控制点的y坐标
        x3: 定位点的x坐标
        y3: 定位点的y坐标
