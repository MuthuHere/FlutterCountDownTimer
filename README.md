# flutter_timer


![Alt Text](https://media.giphy.com/media/JTaKRLBVYICFq66nfF/giphy.gif)


### Paint did things for you here

       @override
       void paint(Canvas canvas, Size size) {
          Paint paint = new Paint()
            ..color = backgroundColor
            ..strokeWidth = 5.0
           ..strokeCap = StrokeCap.round
           ..style = PaintingStyle.stroke;
         canvas.drawCircle(size.center(Offset.zero), size.width / 2.0, paint);
         paint.color = color;
         double progress = (1.0 - animation.value) * 2 * math.pi;
         canvas.drawArc(Offset.zero & size, math.pi * 1.5, -progress, false, paint);
        }
