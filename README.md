# Ponderada 01 - Arduino

Este projeto é uma atividade simples com o objetivo de fazer um LED piscar (blink) usando um Arduino.

## Descrição

O projeto utiliza um Arduino para acender e apagar um LED em intervalos regulares. Esta é uma atividade básica que ajuda a entender como programar o Arduino e controlar saídas digitais.

## Código

```
void setup() {
  
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH); 
  delay(500);                     
  digitalWrite(LED_BUILTIN, LOW);  
  delay(500);                     
}

```
## Vídeo

[Vídeo demonstrativo](./IMG_1860.mp4)