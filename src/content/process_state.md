---
title: Estados de procesos
date: 2023-10-10
author: Leonardo José De la cruz Ardila
desc: Todo proceso en un sistema operativo presenta un estado que indica la ... El número de posibles estados varía de un sistema operativo a otro...
img: https://media.revistagq.com/photos/6273edebab8c0fea708155d0/16:9/w_2560%2Cc_limit/GettyImages-1314656208.jpg
imgWidth: 800
imgHeight: 500
---

**Prioridad alta:**

Tienen acceso preferencial a la CPU y se programan antes que los procesos con una prioridad más baja.

**Prioridad media:**

Se programan después de los procesos de alta prioridad, pero antes de los que tienen prioridad baja, esto es para equilibrar el rendimiento del sistema.

**Proridad baja:**

Se programan después de los procesos de alta y media prioridad.
Se utilizan para tareas que no son criticas y que pueden ejecutarse cuando la CPU y se les da preferencia sobre otros en todo momento.

**Prioridad en tiempo real:**

Esto es para procesos que deben completarse dentro de plazos estrictos.
Estos procesos se ejecutan con alta prioridad y se les da preferencia en todo momento.

**Prioridad por debajo de lo normal:**

Esto significa que obtendría menos tiempo de CPU en comparación con otros procesos que tienen una prioridad normal o superior.
Es útil cuando se desea afectar significativamente las tareas del sistema.

**Prioridad más alta de lo normal:**

Se debe ejecutar con prioridad especial, esta configuración es util cunado deseas que un proceso tenga un acceso más rápido a los recursos de la CPU.
