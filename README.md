# 🚀 Transformación de Datos con Pandas

Este proyecto tiene como objetivo unificar varios archivos almacenados en un directorio, limpiar y transformar los datos para obtener una base de datos final limpia y bien estructurada. Aunque el proyecto original se realizó para una empresa de telecomunicaciones, se utiliza una cantidad reducida de archivos con datos simplificados y ficticios para proteger la información privada de la empresa.

## 📋 Contenido

- [🔧 Requisitos](#requisitos)
- [📌 Instrucciones](#instrucciones)
- [🔍 Exploración Inicial](#exploración-inicial)
- [🔄 Transformación de Datos](#transformación-de-datos)
- [📦 Consolidación](#consolidación)
- [💾 Guardar Resultados](#guardar-resultados)

## 🔧 Requisitos

- Python
- Pandas
- Google Colab (para la versión original del proyecto)

## 📌 Instrucciones

1. Clona o descarga este repositorio en tu entorno local.
2. Asegúrate de tener Python y las bibliotecas requeridas instaladas.
3. Sigue las instrucciones detalladas en el [cuaderno Jupyter](Transformación_de_datos_con_Pandas.ipynb) para ejecutar la transformación de datos.

## 🔍 Exploración Inicial

El proyecto comienza con la importación de las bibliotecas necesarias y la carga de los archivos en un DataFrame. Luego, se realiza una exploración inicial de los datos para comprender su estructura y contenido.

## 🔄 Transformación de Datos

En esta sección, se aplican diversas transformaciones a los datos, como la combinación de columnas, eliminación de columnas no deseadas y conversión de tipos de datos. El objetivo es preparar los datos para su consolidación.

## 📦 Consolidación

Todos los archivos transformados se consolidan en uno solo utilizando `pd.concat`. Esto crea un único conjunto de datos con toda la información relevante.

## 💾 Guardar Resultados

Finalmente, el conjunto de datos consolidado se guarda en un archivo Excel para su uso futuro.

Para obtener más detalles y ejecutar el proyecto completo, consulta el [cuaderno Jupyter](Transformación_de_datos_con_Pandas.ipynb) incluido en este repositorio.

---

**Nota:** Este proyecto utiliza datos ficticios y simplificados con fines de práctica y protege la información privada de la empresa original. Los resultados finales se almacenan en [Consolidado_sin_duplicados.xlsx](/content/drive/My%20Drive/python_projects/CSV/Consolidado_sin_duplicados.xlsx).
