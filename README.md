![GitHub repo size](https://img.shields.io/github/repo-size/dmudo/htv1)
# Leitor de umidade e temperatura com display Nokia 5110.
![GitHub](https://img.shields.io/github/license/dmudo/htv1)

# Sobre o projeto
Esse display é excelente para quem pretende deixar o projeto funcionando em um lugar de grande intempérie, aguenta temperaturas altas, poeira e outros resíduos, e é um display de ótimo custo beneficio.
 - Display Nokia 5110
 - Arduino Nano (ATmega 328) 
 - Modulo DHT 11 (Humidade e Temperatura)

# Tecnologias utilizadas
 - IDE Arduino 1.8.57 (Windows Store)
 - Fritizing 0.9.3
 - Biblioteca Adafruit texto - https://github.com/adafruit/Adafruit-GFX-Library
 - Biblioteca Adafruit Display Nokia https://github.com/adafruit/Adafruit-PCD8544-Nokia-5110-LCD-library
 - Biblioteca modulo dht11 https://www.arduino.cc/reference/en/libraries/dht-sensor-library/
 - C++
 
![foto - Copia](https://user-images.githubusercontent.com/12467009/172070696-8aac3676-be21-4f24-a7ab-8cdf90564b03.jpg)
![Screenshot_1](https://user-images.githubusercontent.com/12467009/172070712-00a9d8a2-4e30-42a5-acc5-5247e3f7b7dc.png)

# Pinos Nokia 5120

Arduino Nano   | Nokia 5110
--------- | ------
pino 8 | CLK
PINO 9 | DIN
PINO 10 | DC
PINO 11 | CE
PINO 12 | RST
PINO 3V | VCC
PINO 3V | BL
PINO GND | GND

# Pinos Modulo DHT11

Arduino Nano   | DHT 11
--------- | ------
PINO 5V | VCC
PINO GND | GND
PINO A1 | DATA
