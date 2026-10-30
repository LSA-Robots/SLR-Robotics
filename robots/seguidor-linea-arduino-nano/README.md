# Seguidor de línea — Arduino Nano

## Descripción
Robot autónomo que detecta una línea mediante sensores reflectivos y ajusta sus motores para seguir el recorrido.

## Fotografías
Subí imágenes a esta carpeta y enlazalas aquí, por ejemplo: `![Vista superior](fotos/vista-superior.jpg)`.

## Componentes
- Arduino Nano
- Arreglo QTR de 8 sensores (versión documentada)
- Driver TB6612FNG
- 2 motoresreductores N20
- Batería de dos celdas de litio
- Pulsador y LED indicador

## Funcionamiento
El programa calibra los sensores, calcula la posición de la línea y aplica correcciones mediante control PID para ajustar la velocidad de cada motor.

## Código
Colocá el sketch .ino probado en `codigo/`. Documentá la versión, fecha, pines y librerías.