# Evaluación 2 - DEVASC
Repositorio que contiene los scripts en Python desarrollados para la evaluación práctica de automatización de APIs y geolocalización.

## Contenido del Repositorio
1. **Ramdom50libros.py**: Script que se conecta a la API del simulador de biblioteca escolar (`http://library.demo.local`) mediante autenticación básica y genera automáticamente 50 libros aleatorios con títulos, autores e ISBN únicos utilizando la librería `faker`.
2. **geolocalizacion.py**: Script que interactúa con la API de rutas de Graphhopper, permitiendo elegir un perfil de vehículo (`car`, `bike`, `foot`), ingresar puntos de origen y destino, calcular la ruta con instrucciones paso a paso en español, y mostrar todos los valores numéricos con un máximo de dos decimales. Incluye opción de salida con "s" o "salir".

## Instrucciones de Ejecución

### Requisitos previos:
- Máquina virtual DEVASC (o entorno con Python 3 instalado).
- Librerías requeridas: `requests` y `faker`.

### Ejecutar la generación de libros:
python3 Ramdom50libros.py

### Ejecutar el script de geolocalización:
python3 geolocalizacion.py
