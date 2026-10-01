# Carta solar EPW

Aplicación web estática para generar una carta solar a partir de un archivo climático EPW. Lee las coordenadas y temperaturas del archivo, calcula la posición solar y representa las horas de sol en una gráfica polar interactiva.

## Uso

Abre `index.html` en un navegador moderno y selecciona o arrastra un archivo `.epw`. Ajusta la orientación de fachada y, opcionalmente, la temperatura mínima. Puedes descargar los datos visibles como CSV o la gráfica como PNG.

El archivo climático se procesa localmente en el navegador. No hay cuentas, servidor, base de datos ni almacenamiento de los archivos.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube los archivos de este proyecto.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**, la rama `main` y la carpeta `/(root)`.
4. Guarda los cambios. GitHub Pages publicará la aplicación en la URL que aparece en esa sección.

La gráfica usa Plotly.js desde un CDN y las fuentes tipográficas se cargan desde Google Fonts; hace falta conexión a Internet para esos recursos.