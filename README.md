# :fa-file-o: Automatización de Presentaciones con Python :fa-file-o:

Este proyecto automatiza la elaboración de reportes visuales de forma profesional, rápida y sin necesidad de realizar tareas manuales repetitivas.

## :fa-wrench: Descripción del Proyecto

Este proyecto consistió en desarrollar una solución automatizada mediante Python para generar presentaciones en PowerPoint que comparan imágenes clasificadas como "ANTES" y "DESPUÉS". Las imágenes están almacenadas en Google Drive y son organizadas automáticamente en diapositivas, junto con los logotipos correspondientes. El objetivo fue facilitar la elaboración de reportes visuales de forma profesional, rápida y sin necesidad de realizar tareas manuales repetitivas.

## :fa-cogs: Flujo de Automatización

1. **Carga de bibliotecas necesarias** (como `python-pptx`, `os`, `math`).
2. **Montaje de Google Drive** para acceder a las imágenes desde el entorno de Colab.
3. **Lectura y ordenamiento** de imágenes desde dos carpetas (`ANTES` y `DESPUÉS`).
4. **Creación de la diapositiva principal** con los logotipos de las empresas.
5. **Generación de múltiples diapositivas** donde cada estaran imagenes de "ANTES" y "DESPUÉS".
6. **Guardado automático** del archivo `.pptx` dentro de Google Drive.

## :fa-archive: Tecnologías y Herramientas Utilizadas

| Herramienta         | Función en el Proyecto                               | Otra Función Relevante                              |
|---------------------|------------------------------------------------------|-----------------------------------------------------|
| Python              | Lenguaje principal de programación                   | Automatización de tareas repetitivas                |
| Google Colab        | Entorno de desarrollo en la nube                     | Compartir notebooks fácilmente                      |
| Google Drive        | Almacenamiento y acceso a las imágenes               | Trabajo colaborativo en la nube                     |


## :fa-check-circle-o: Beneficios Obtenidos

- Ahorro significativo de tiempo al evitar la creación manual de las presentaciones.
- Reducción de errores humanos, ya que el proceso está automatizado.
- Organización clara de los resultados antes y después del proceso.
- Versatilidad para aplicarlo en distintas áreas como ingeniería, calidad, diseño o marketing.

## :fa-plus: Posibles Mejoras

- Actualmente las imágenes se ajustan a un tamaño fijo.Se podría adaptar el script para analizar las dimensiones originales de las imágenes y ajustar su tamaño automáticamente para una mejor calidad visual.
- Exportar también a PDF automáticamente.
- Integrar con otras plataformas como Notion o Google Slides vía API.

---

##  :fa-pencil-square-o: Autor

Proyecto desarrollado por Ricardo Rubio Alvarez Tostado.


