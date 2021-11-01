# ArduinoProm

## Montage pour la lecture:
  
Arduino -> IC 74287  
*addr  
pin 46 -> pin 5  
pin 47 -> pin 6  
pin 48 -> pin 7  
pin 49 -> pin 4  
pin 50 -> pin 3  
pin 51 -> pin 2  
pin 52 -> pin 1  
pin 53 -> pin 15  
  
*data  
pin 30 -> pin 12  
pin 31 -> pin 11  
pin 32 -> pin 10  
pin 33 -> pin 9  
  
*cs  
gnd -> pin 13 & 14  
  
gnd -> pin 8  
+5 vcc -> pin 16  
  
## Montage pour l'écriture:  
  
*addr  
pin 46 -> pin 5  
pin 47 -> pin 6  
pin 48 -> pin 7  
pin 49 -> pin 4  
pin 50 -> pin 3  
pin 51 -> pin 2  
pin 52 -> pin 1  
pin 53 -> pin 15  
  
*data  
pin 40 -> pin 12 -> 3.9k -> 5v  
pin 41 -> pin 11 -> 3.9k -> 5v  
pin 42 -> pin 10 -> 3.9k -> 5v  
pin 43 -> pin 9 -> 3.9k -> 5v  

*cs  
pin 39 -> pin 13 & 14  
  
gnd -> pin 8  
+10v -> pin 16   
  
*ne pas laisse le chip brancher trop longtemps pour ne pas le faire surechaufé


![alt text](https://raw.githubusercontent.com/Pikasoo01/ArduinoProm/main/NS_74S287.jpg)
