# Intro a la programación

En este repositorio hay ejercicios de los temas:

-   `pivot_wider()` y `pivot_longer()` del paquete tidyr
-    uniones

## Preparación previa.

Creá un proyecto en tu máquina a partir de este repositorio.

1.  Abrí RStudio
2.  Andá a `File > New Project > Version Control > Git`.
    En la parte de "Repository URL" copiá y pega la dirección de este repositorio.
3.  Elegí la carpeta donde crear el proyecto.
4.  Hacé click en "Create Project".

*No te olvides de ir haciendo commits frecuentes.
Por ejemplo, cuando resolvés cada ejercicio o cada sección.*

**Al final de todo: acordate de hacer PUSH para que los cambios se vean reflejados en el repositorio remoto!**


## Diccionario de datos para avistamientos_ovni.csv


|variable                   |clase    | Descripción |
|:---|:---|:-----------|
|date_time                  |día y fecha (mdy h:m) | Día y fecha  |
|city_area                  |caracter | Ciudad o área del avistamiento |
|state                      |caracter | etado o región del avistamiento |
|country                    |caracter | País del avistamiento |
|ufo_shape                  |caracter | Forma del OVNI |
|encounter_length           |doble    | Duración del avistamiento en segundos |
|described_encounter_length |caracter | Duración del avistamiento como fue descripta |
|description                |caracter | Descripción del avistamiento |
|date_documented            |caracter | Fecha documentada |
|latitude                   |doble    | Latitud |
|longitude                  |doble    | Longitud |