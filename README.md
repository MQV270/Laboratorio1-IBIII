# Laboratorio1-IBIII
Acondicionamiento de señales de alta impedancia - Instrumentación Biomédica III
# Laboratorio N.º 1 – Instrumentación Biomédica III

## Acondicionamiento de señales de alta impedancia

Este repositorio contiene los archivos correspondientes al Laboratorio N.º 1 de Instrumentación Biomédica III de la Escuela Profesional de Ingeniería Biomédica – UNMSM.

El laboratorio tiene como objetivo estudiar el efecto de carga en una fuente de alta impedancia y comprobar el funcionamiento de un buffer con amplificador operacional TL084. También se compara su comportamiento con el LM324 y se utiliza un ESP32 para generar una señal simulada de pH en los puntos 4, 7 y 10. :contentReference[oaicite:0]{index=0}

## Archivos

- `codigo_ESP32.ino` – Código utilizado para generar la señal de pH mediante el DAC del ESP32.
- `esquematico.png` – Esquemático eléctrico del montaje.
- `datos_experimentales.xlsx` – Datos obtenidos durante el laboratorio.
- `README.md` – Descripción del laboratorio y de los archivos del repositorio.

## Componentes principales

- ESP32
- TL084N
- LM324N
- Resistencia de 1 MΩ
- Capacitores de 0.1 µF
- Osciloscopio
- Multímetro
- Fuente de alimentación dual ±9 V

## Procedimiento

Se verificó primero la señal generada por el ESP32, luego se observó el efecto de carga sin buffer y finalmente se evaluó el funcionamiento de los buffers TL084 y LM324. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}
