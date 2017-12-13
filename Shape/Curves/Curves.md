### Curves

#### bezier 贝赛尔曲线
>参数一： bezier(x1,y1,x2,y2,x3,y3,x4,y4)
>参数二： bezier(z1,z2,z3,z4)

        x1: 第一个锚点的x坐标
        y1: 第一个锚点的y坐标
        x2: 第一个控制点的x坐标
        y2: 第一个控制点的y坐标
        x3: 第二个控制点的x坐标
        y3: 第二个控制点的y坐标
        x4: 第二个锚点的x坐标
        y4: 第二个锚点的y坐标
        z1: 第一个锚点的z坐标
        z2: 第一个控制点的z坐标
        z3: 第一个锚点的z坐标
        z4: 第一个控制点的z坐标
    
#### bezierDetail 贝赛尔曲线分辨率
> bezierDetail(detail)

         default: 20
         type: number
         detail	曲线的分辨率
     
#### bezierPoint
>bezierPoint(a,b,c,d,t)
 
         a	号码：曲线上第一个点的坐标
         b	号码：第一个控制点的坐标
         c	号码：第二个控制点的坐标
         d	号码：曲线上第二点的坐标
         t	号码：值在0和1之间
         评估位置t的Bezier点a，b，c，d。参数a和d是曲线上的第一个和最后一个点，b和c是控制点。最后的参数t在0和1之间变化。这可以用x坐标来完成一次，再用y坐标来得到贝塞尔曲线在t的位置。
         
#### curveTangent
>curveTangent(a,b,c,d,t)

        评估点a，b，c，d的位置t的曲线的切线。参数t在0和1之间变化，a和d是曲线上的点，b和c是控制点。
        参数
        a	号码：曲线上第一个点的坐标
        b	号码：第一个控制点的坐标
        c	号码：第二个控制点的坐标
        d	号码：曲线上第二点的坐标
        t	号码：值在0和1之间