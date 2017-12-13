### Attributes

#### ellipseMode 

>ellipseMode(mode)

        处理圆的位置
        mode	Constant: either CENTER, RADIUS, CORNER, or CORNERS
        可选参数： 中心，半径，角，
        
#### smooth
        绘制所有具有平滑（消除锯齿）边缘的几何图形。smooth（）也将改善调整图像的图像质量。请注意，smooth（）默认为活动状态; noSmooth（）可用于禁用几何，图像和字体的平滑。

#### noSmooth
        来禁用几何，图像和字体的平滑处理。
        
#### rectMode
>rectMode(mode)

       mode	常数：CORNER，CORNERS，CENTER或RADIUS
       可选参数：角落,角落,中心或半径
       改变给定给rect（）的参数的方式来修改绘制矩形的位置。 

#### strokeCap
>strokeCap(cap)

        cap	常数：SQUARE，PROJECT或ROUND
        可选参数：正方形,尖角,圆形
        设置渲染线尾的样式。这些端点可以是方形的，扩展的，也可以是圆形的，每一个都用相应的参数：SQUARE，PROJECT和ROUND来指定。默认上限是ROUND。
        
#### strokeJoin
>strokeJoin(join)

        join	Constant: either MITER, BEVEL, ROUND
        可选参数：尖角,切面,圆滑
        
- strokeWeight
>strokeWeight(weight)

        weight	Number: the weight (in pixels) of the stroke
        渲染宽度

