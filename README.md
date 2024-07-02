# Connect and program an electronic circuit It contains 6 type motors Servo tensor on simulation software

















code
```
#include <Servo.h>

Servo servo1;
Servo servo2;
Servo servo3;
Servo servo4;
Servo servo5;
Servo servo6;

void setup() {
  servo1.attach(2);
  servo2.attach(3);  
  servo3.attach(4);  
  servo4.attach(5); 
  servo5.attach(6);
  servo6.attach(7); 
}

void loop() {
  for (int angle = 0; angle <= 180; angle += 1) {
    servo1.write(angle);
    servo2.write(angle);
    servo3.write(angle);
    servo4.write(angle);
    servo5.write(angle);
    servo6.write(angle);
    delay(15);
  }
  for (int angle = 180; angle >= 0; angle -= 1) {
    servo1.write(angle);
    servo2.write(angle);
    servo3.write(angle);
    servo4.write(angle);
    servo5.write(angle);
    servo6.write(angle);
    delay(15); 
  }
}
```


![image](https://github.com/EngMahmoud2/Electronics-engineering-tasks2/assets/174360973/7c9822d4-4854-48ff-b2c9-84af29b9b6f6)

### Tinkercad
https://www.tinkercad.com/things/13pDpPxRQeP-surprising-migelo?sharecode=53FxCUGLurMCGacZiPPipVMLpR1fL0CuF6yoWa1akrQ
