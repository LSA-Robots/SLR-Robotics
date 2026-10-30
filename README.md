<div align="center">

# SLR ROBOTICS
### Santiago Lacoste | Robotics & Engineering

**Diseño · Electrónica · Programación · Robótica móvil**

</div>

---

## 👋 Sobre mí

¡Hola! Soy **Santiago Lacoste**, estudiante y entusiasta de la robótica, la electrónica y la programación. En SLR Robotics comparto los robots que diseño, construyo, programo y mejoro, documentando sus componentes, conexiones, pruebas y códigos.

## 🤖 Disciplinas

### Seguidor de línea
Un robot seguidor de línea es un vehículo autónomo que utiliza sensores ópticos o infrarrojos para detectar una trayectoria marcada en el suelo. El controlador interpreta esas lecturas y regula los motores para mantenerse sobre el recorrido. En mis proyectos trabajo con calibración, lectura de sensores, PWM y control PID para mejorar la estabilidad y precisión.

### Carrera — Liga Nacional de Robótica
En la modalidad Carrera, robots autónomos seguidores de línea compiten recorriendo una pista. El objetivo es completar el circuito en el menor tiempo posible. La categoría establece requisitos de autonomía, dimensiones, señalización y propulsión. La síntesis reglamentaria debe verificarse siempre contra el documento oficial vigente antes de competir.

### Carrera Pro — Liga Nacional de Robótica
Carrera Pro mantiene el desafío de recorrer el circuito de forma autónoma y contempla sistemas de impulsión adicionales, como turbinas o aspas, bajo las condiciones específicas del reglamento. No hay que asumir que los requisitos son idénticos a Carrera: cada robot debe revisarse con la versión vigente del reglamento.

**Referencia oficial:** [Liga Nacional de Robótica](https://www.lnr-argentina.com.ar/) · [Reglamentos](https://lnr-argentina.com.ar/reglamentos/Reglamento%20Carrera.pdf)

## 🏁 Proyectos

### 01 — Seguidor de línea | Arduino Nano
Robot basado en Arduino Nano, sensores QTR, driver TB6612FNG y dos motores N20. La versión documentada utiliza calibración y control PID para ajustar el movimiento.
- **Componentes:** Arduino Nano, arreglo QTR de 8 sensores, TB6612FNG, 2 motores N20, batería de dos celdas, pulsador y LED.
- **Fotos:** [carpeta del proyecto](robots/seguidor-linea-arduino-nano/fotos/)
- **Código:** [carpeta de código](robots/seguidor-linea-arduino-nano/codigo/)

### 02 — Seguidor de línea | ESP32-S3
Prototipo con ESP32-S3, 16 sensores multiplexados y drivers RZ7889. El pinout y el programa deben completarse con la versión final probada.
- **Componentes:** ESP32-S3, 16 sensores, drivers RZ7889, dos motores DC, pulsador y alimentación.
- **Fotos:** [carpeta del proyecto](robots/seguidor-linea-esp32s3/fotos/)
- **Código:** [carpeta de código](robots/seguidor-linea-esp32s3/codigo/)

## 🧰 Tecnologías
Arduino Nano · Arduino UNO · ESP32 / ESP32-S3 · C/C++ · sensores reflectivos · PWM · drivers de motores · control PID.

## 📂 Agregar un robot
Usá la [plantilla de nuevo robot](plantilla-nuevo-robot/README.md). Cada proyecto debe incluir fotos, breve descripción, tabla de componentes, conexiones, código fuente y pruebas.

## 📬 Contacto
**Santiago Lacoste — SLR Robotics**

Este repositorio reúne proyectos personales de aprendizaje, experimentación y desarrollo en robótica.