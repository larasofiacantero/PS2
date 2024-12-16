 PS2

Documentos y resolución del Problem Set 2 del curso de Machine Learning (ME-UNLP).

## Índice

- [Descripción del proyecto](#descripción-del-proyecto)
- [Prerrequisitos](#prerrequisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del proyecto](#estructura-del-proyecto)

---

## Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo para estimar la pobreza a través de dos canales distintos. Primero, se abordará como un problema de clasificación utilizando variables como la edad, la educación, el tipo de ocupación y los regímenes de seguridad social en salud al que los individuos están afiliados. Segundo, como un problema de predicción de ingresos, donde con los ingresos previstos y la línea de pobreza se obtendrá la clasificación, utilizando variables como la educación, edad, antiguedad laboral y la cantidad de horas trabajadas.
Los datos utilizados provienen de la **Gran Encuesta Integrada de Hogares (GEIH) de 2018**.
---

## Prerrequisitos

Antes de comenzar, asegurate de tener lo siguiente:

- **Python** 3.10 o superior.
- Bibliotecas necesarias:
  - `os`
  - `pandas`
  - `zipfile`
  - `sklearn`
  - `numpy`
  - `seaborn`
  - `matplotlib`
---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/larasofiacantero/PS2.git

2. Dirigite al directorio del proyecto:
   ```bash
   cd PS2

3. Instala las dependencias 
  ```bash 
  pip install os (...)
---


## Uso

1. Scripts:
Contiene los archivos de Python con los códigos necesarios para desarrollar el trabajo. 'PS2' permitirá estimar los modelos y replicar las predicciones y 'PS2_est_desc' permitirá obtener los gráficos y las medidas de resumen de las variables utilizadas.

2. Documents:
Archivos PDF que contienen las conclusiones y las respuestas a las preguntas planteadas en el trabajo.

3. Views:
Contiene las figuras de la sección de estadística descriptiva.

Nota: no se incluye la carpeta 'Stores' dado que los archivos .csv utilizados superan el límite de almacenamiento disponible de GitHub. Estos pueden ser obtenidos de https://www.kaggle.com/competitions/mlunlp-2024-ps-2/data
---

## Estructura del proyecto
En resumen, el repositorio se distribuye así:
PS2/
├── documents/        # Archivos PDF con resultados y conclusiones
├── scripts/          # Código fuente del proyecto
├── views	      # Figuras
└── README.md         # Este archivo