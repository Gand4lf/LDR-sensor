
from gpiozero import LightSensor
import time
ldr = LightSensor(4)
while True:
   If ldr<0.3:
     print(ldr.value)
     print(time.ctime)
