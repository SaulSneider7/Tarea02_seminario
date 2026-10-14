# ACTIVIDAD: PREDICCIÓN DEL PRECIO DE UNA VIVIENDA - 2ptos
## SUBIR LA ACTIVIDAD EN TAREA 02 DE SEMINARIO

## Objetivo

Desarrollar un modelo de **Machine Learning** utilizando **Regresión Lineal Múltiple** para predecir el precio de una vivienda a partir de diferentes características.

---

## Situación

Una empresa inmobiliaria desea estimar el precio de una vivienda antes de publicarla.

Para ello cuenta con información de viviendas vendidas anteriormente.

El modelo utilizará las siguientes características:

- Área de la vivienda.
- Número de habitaciones.
- Antigüedad de la vivienda.
- Distancia al centro de la ciudad.

La variable que queremos predecir será:

- Precio de la vivienda.

Mostrar la precision del modelo


---

## Dataset

Utilice el siguiente conjunto de datos:

```python
datos = {
    "area_m2": [
        50, 60, 70, 80, 90,
        100, 110, 120, 130, 140,
        55, 75, 95, 115, 135,
        65, 85, 105, 125, 145
    ],

    "habitaciones": [
        1, 2, 2, 3, 3,
        3, 4, 4, 4, 5,
        2, 2, 3, 3, 4,
        2, 3, 3, 4, 5
    ],

    "antiguedad_anios": [
        2, 5, 3, 8, 6,
        10, 4, 7, 12, 5,
        1, 9, 6, 3, 11,
        4, 8, 2, 7, 5
    ],

    "distancia_centro_km": [
        2, 4, 3, 5, 6,
        7, 4, 8, 10, 6,
        1, 5, 7, 3, 9,
        4, 6, 2, 8, 5
    ],

    "precio_miles": [
        180, 195, 225, 235, 250,
        260, 310, 315, 320, 365,
        205, 220, 255, 315, 325,
        210, 240, 300, 310, 380
    ]
}