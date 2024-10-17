# Parte 02 - Arduino

Este projeto é uma atividade simples com o objetivo de fazer um LED piscar (blink) usando um Arduino no TinkerCad.

## Descrição

O projeto utiliza a interface do TinkerCad para montar um sistema para acender e apagar um LED em intervalos.

## Código

```
void setup()
{
  pinMode(4, OUTPUT);
}

void loop()
{
  digitalWrite(4, HIGH);
  delay(1000); 
  digitalWrite(4, LOW);
  delay(1000);
}

```
## Foto

[Screenshot](./image.png)

## Link TinkerCad

[Link de Acesso](https://www.tinkercad.com/things/aNwdvp8GFNg-smooth-robo-allis/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=q3xg-buUMa4w1dyd6NAzPs7p31ZqqdaiC6MPKleEhOs)