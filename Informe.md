# Enunciado

Construir nuestro propio “Waze”, es decir un sistema que nos permita encontrar la ruta más
corta entre 2 puntos en una ciudad. La ciudad estará representada por un grafo previamente
construido que representa una ciudad o una porción o distritos de una ciudad grande como Lima.

Los datos a trabajar se adjuntan en los siguientes archivos:
Lima-calles.csv Este archivo contiene por fila la información de cada calle de la ciudad de Lima con
los siguientes tres datos:
• ID de la calle
• El nombre de la calle
• La cantidad de intersecciones que contiene esa calle
Lima-intersecciones.csv Este archivo contiene información de cada intersección por calle.
Contempla los siguientes datos:
• ID del registro,
• ID de la calle,
• IDs de origen y destino de la intersección,
• el origen y destino de la intersección,
• la distancia en Km,
• la velocidad en Km/h,
• el costo,
• el costo inverso
• las coordenadas de la intersección

# Hito 0

Hito 0, desarrollar un código en Python (*.py / *. ipynb) que genere una lista de adyacencia,
a partir del cual se construya un grafo de la ciudad de Lima, teniendo como conjunto de
datos los archivos
