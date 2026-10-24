---
title: "¿Cómo 'ven' y toman decisiones los robots autónomos?"
date: 2026-10-20
draft: false
featured: true
summary: "Una mirada accesible a los sensores LIDAR, visión por computadora y la toma de decisiones en tiempo real en la robótica moderna."
authors:
  - admin
tags:
  - Robótica
  - Visión Artificial
  - Divulgación
categories:
  - Divulgación
---

La robótica autónoma ha dejado de ser una fantasía de ciencia ficción para convertirse en una realidad cotidiana. Desde vehículos que se conducen solos hasta rovers explorando la superficie de Marte, los robots necesitan percibir su entorno y tomar decisiones en milisegundos.

## ¿Cómo percibe el mundo un robot?

Un robot autónomo combina múltiples tipos de sensores para construir un modelo en 3D de su entorno:

1. **LIDAR (Light Detection and Ranging):** Emite pulsos de luz láser para medir distancias con precisión milimétrica.
2. **Cámaras de Visión Estéreo:** Permiten calcular la profundidad calculando la diferencia entre dos imágenes contiguas.
3. **Sensores Inerciales (IMU):** Miden la aceleración y orientación del robot.

## El ciclo de percepción y acción

Para desplazarse sin chocar, el software del robot ejecuta constantemente tres pasos:

* **Percepción:** Procesa los datos de los sensores para identificar obstáculos y rutas libres.
* **Planificación:** Calcula la ruta óptima desde su posición actual hasta el objetivo.
* **Control:** Envía señales a los motores para ajustar la velocidad y dirección.