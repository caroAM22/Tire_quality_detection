# Detección de Calidad de Neumáticos mediante Visión Artificial

## Descripción del Proyecto

Este proyecto, centrado en la detección de la calidad de los neumáticos, utiliza técnicas de visión artificial implementadas principalmente en Python con la librería OpenCV. El objetivo es desarrollar un sistema capaz de identificar neumáticos defectuosos a partir de un conjunto de datos que contiene imágenes clasificadas como defectuosas o buenas.

## Integrantes del Equipo

- **Carolina Álvarez Murillo:** Ingeniería de Sistemas e Informática
- **Mateo Álvarez Murillo:** Ingeniería de Sistemas e Informática
- **Cristian Londoño Franco:** Ingeniería de Sistemas e Informática
- **Miguel Ángel Martínez Arenas:** Ingeniería Física

## Dataset

El programa utiliza el conjunto de datos "Tyre Quality Classification" obtenido de Kaggle, compuesto por 1854 imágenes digitales en formato jpg. Estas imágenes están etiquetadas como defectuosas (1028) y buenas (828), facilitando el desarrollo de un sistema de inspección eficiente para la producción de neumáticos.

## Objetivos

**Objetivo General:**
Mejorar el proceso de control de calidad en la industria de neumáticos y reducir las posibilidades de accidentes debidos a neumáticos defectuosos.

**Objetivos Específicos:**
1. Realizar un preprocesamiento de las imágenes de llantas del dataset.
2. Desarrollar un clasificador de llantas defectuosas y buenas.
3. Documentar el código desarrollado, los análisis realizados y las conclusiones.

## Metodología

1. **División del Conjunto de Datos:**
   - Dividir el conjunto en entrenamiento, validación y prueba.

2. **Preprocesamiento de Datos:**
   - Cargar imágenes, redimensionar, probar canales de color, separar por luminosidad y aplicar transformaciones lineales.

3. **Construcción del Modelo:**
   - Desarrollar un modelo de clasificación utilizando las imágenes preprocesadas.

## Estructura de Carpetas

- **/dataset:** Contiene las imágenes del dataset.
- **/code:** Contiene el código fuente del proyecto.
- **/docs:** Documentación del proyecto.

## Instrucciones de Ejecución

1. Clonar el repositorio: `git clone https://github.com/tu_usuario/proyecto-neumaticos.git`
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el programa: `python main.py`

## Contribuciones

Agradecemos cualquier contribución o sugerencia para mejorar este proyecto. Si encuentras algún problema, por favor, crea un "issue" en este repositorio.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE.md](LICENSE.md) para más detalles.
