+++
date = '2025-05-08T12:53:48-03:00'
draft = false
title = 'Diagramas_de_Gantt'
+++

# Diagrama de Gantt
Es una herramienta para planificar y programar tareas a lo largo de un período determinado

Las barras representan cada una de las actividades o tareas. La longitud de cada barra representa la duración.

### Ventajas
Una ventaja importante de los gráficos de Gantt es que muestra claramente el
solapamiento de actividades.

Fáciles de entender debido a su formato lineal.

El orden de las tareas es muy claro.

### Desventajas

A diferencia de los gráficos de Pert los gráficos de Gantt no muestran claramente las dependencias que existe entre tareas

La longitud de las barras no indica la cantidad de trabajo, sino sólo la temporalización.

Si el proyecto es complejo e involucra muchas tareas en una estructura de desglose de trabajo, entonces todas las tareas no son visibles en una sola vista del diagrama de Gantt

## Ejemplo

| Actividad | Precedentes | Duración |
|-----------|-------------|----------|
| A         | -           | 2        |
| B         | A           | 2        |
| C         | A           | 1        |
| D         | B, C        | 2        |
| E         | D           | 3        |


![Diagrama de Gantt](content/posts/Diagramas_de_Gantt/1.bmp)

Diagrama de Gantt realizado con la Herramienta ProjectLibre

[imagen]

Las tareas de color rojo representan la ruta crítica del proyecto.

