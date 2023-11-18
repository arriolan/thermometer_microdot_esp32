### Microdot Sample: Indicador de Temperatura con Interfaz Web

Bienvenido a **Microdot Sample**, un ejemplo de implementación de un indicador de temperatura con una interfaz web. Esta aplicación utiliza un servidor Flask ejecutándose con Micropython en una ESP32.

#### Estructura de Archivos

```
|-- main.py (aplicación principal)
|-- index.html (interfaz de la aplicación)
|-- assets (directorio con archivos CSS y JS)
    |-- css (estilos de la interfaz)
        |-- style.css (archivos de estilos)
    |-- js (scripts de JavaScript)
        |-- data.js (script que actualiza la interfaz periódicamente)
```

#### Descripción

El archivo `main.py` contiene la lógica principal de la aplicación, mientras que `index.html` proporciona la interfaz de usuario para visualizar la temperatura. Los estilos de la interfaz se encuentran en el directorio `css`, específicamente en `style.css`. El directorio `js` alberga el script `data.js`, responsable de actualizar la interfaz de forma periódica.

#### Guía Rápida

1. Clona este repositorio en tu entorno de desarrollo.
2. Ejecuta el archivo `main.py` en una Raspberry ESP32 con Micropython.
3. Abre un navegador y accede a la interfaz web en `http://direccion-ip` (sustituye con la dirección y puerto correctos).
4. Disfruta monitoreando la temperatura a través de la interfaz web intuitiva.

¡Espero que esta implementación te resulte útil y que encuentres inspiración para tus propios proyectos con Microdot!
