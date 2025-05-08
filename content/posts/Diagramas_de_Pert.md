+++
date = '2025-05-08T12:22:28-03:00'
draft = false
title = 'Diagramas_de_Pert'
+++

# Diagrama de Pert

Se representa por una red de flechas y nodos, que luego se evalúa para determinar cuales son las
actividades criticas y mejorar su programación.

Las actividades se representan por las flechas.

Los nodos (eventos) sirven para:

- Reconocer que una actividad terminó;
- Indicar que actividades necesitan concluirse antes de iniciar una nueva (precedencia);
- Los nodos pueden tener números o letras.

[aca_van_una_img]

* Ruta Crítica: es la ruta más larga. Indica la duración total del proyecto.
* Holgura: determina el tiempo que se dispone para terminar una tarea antes de que se arriesgue la duración total del proyecto.
* Dos actividades pueden iniciar en un mismo nodo pero no pueden finalizar en un mismo nodo

[aca_van_dos_img]

## El diagrama de Pert nos permite

- La identificación fácil del orden de precedencia
- La identificación fácil de la ruta crítica, y por lo tanto de las actividades críticas
- El cálculo sencillo de la duración de la holgura

### Ventajas del diagrama de Pert

- Destaca las dependencias de las tareas y su ruta crítica.
- Estimaciones más precisas que cuando te basas en cálculos de duración de una sola tarea.
- Es fácil ver cuánto tiempo se pueden retrasar las tareas no críticas sin afectar a la fecha de finalización del proyecto.

### Desventajas del diagrama de Pert

- Los gráficos PERT pueden llevar mucho tiempo y ser difíciles de crear y actualizar.
- Pueden resultar confusos a la hora de que los interpreten las partes interesadas.
- PERT presupone que una tarea debe finalizar antes de que comience la siguiente.

# Actividades Ficticias (Dummy)

Cuando dos o más actividades comienzan y terminan en un mismo nodo

[aca_van_una_img]

Cuando dos o más actividades comparten la misma precedencia pero no todas las precedencias son compartidas

[aca_van_una_img]

# Cálculo de la Holgura

[aca_van_una_img]

**Fin temprano (FT):** Es el momento en el que mas tempranamente es posible concluir todas las actividades que llegan a tal nodo.

**Inicio tardío (IT):** Es el ultimo momento disponible para iniciar aquellas actividades que se originan en tal nodo.
