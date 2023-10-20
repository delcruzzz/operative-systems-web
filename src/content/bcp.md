---
title: Bloque de Control del Proceso (BCP)
date: 2023-10-10
author: Leonardo José De la cruz Ardila
desc: Laudantium iste repellat et. Et officiis corporis. At est placeat voluptas aut. Soluta dolor quae quae tempora. Voluptatibus quibusdam natus. Facilis ea repellendus expedita voluptatum rerum autem.
img: src/img/cola-inicial.png
imgWidth: 800
imgHeight: 500
---

El ***BCP*** de informática o Bloque de control del proceso, en ingles PCB (Process Control Block), se refiere a un registro especial donde el sistema operativo agrupa toda la información que necesita conocer respecto a algún proceso en particular. Por tanto, cada vez que un proceso se crea, el sistema operativo crea el BCP, que va a servir como descripción en tiempo de ejecución durante toda la vida del proceso.

La información almacenada en un BCP incluye típicamente algunos o todos los campos siguientes:

- Identificador del proceso (Process Identificator -PID-, de sus siglas en inglés).
- Estado del proceso. Por ej.: listo, en espera, bloqueado.
- Contador de programa: dirección de la próxima instrucción a ejecutar.
- Valores de registro de CPU. Se utilizan también en el cambio de contexto.
- Espacio de direcciones de memoria.
- Prioridad en caso de utilizarse dicho algoritmo para planificación de CPU.
- Lista de recursos asignados (incluyendo descriptores de archivos y sockets abiertos).
- Estadísticas del proceso.
- Datos del propietario (owner).
- Permisos asignados.
- Signals pendientes de ser servidos. (Almacenados en un mapa de bits).
