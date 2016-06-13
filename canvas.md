画布的大小只能通过属性设置  不要用css
##canvas常用API

##形状


>矩形
*ctx.fillRect()      填充矩形
*ctx.strokeRect()    框线矩形


>圆
*ctx.arc()           圆
*ctx.arcTo()         圆弧


>线
*ctx.begunPath()     开始一个路径
*ctx.moveTo()        移动画笔到某点
*ctx.lineTo()        让路径中拥有一条到某点的线(并不会直接绘制)
*ctx.rect()          让路径中拥有一个矩形(并不会直接绘制)
*ctx.fill()          填充当前路径
*ctx.stroke()        描边当前路径
*ctx.closePath()     结束一个路径


*ctx.quadraticCurveTo(cp1x,cp1y,x,y) 二次贝塞尔
*ctx.bezierCurveTo(cp1x,cp1y,cp2x,cp2y,x,y)  三次贝塞尔


##样式


##位移(挪动画布)


*ctx.save()    保存画布初始位置
*ctx.restore()  让画布恢复到初始保存的位置
*ctx.translate()  画布移动
*ctx.rotate()
