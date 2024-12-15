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

Este proyecto tiene como objetivo desarrollar un modelo predictivo para estimar la pobreza a través de dos canales distintos. Primero, se abordará como un problema de clasificación utilizando variables como la edad, la educación, el tipo de ocupación y los regímenes de seguridad social en salud en el que los individuos están afiliados. Segundo, como un problema de predicción de ingresos, donde con los ingresos previstos y la línea de pobreza se obtendrá la clasificación, utilizando variables como la educación, edad, antiguedad laboral y la cantidad de horas trabajadas.
Los datos utilizados provienen de la **Gran Encuesta Integrada de Hogares (GEIH) de 2018**.
---

## Prerrequisitos

Antes de comenzar, asegurate de tener lo siguiente:

- **Python** 3.10 o superior.
- Bibliotecas necesarias (podes instalarlas con el archivo `requirements.txt` en stores):
  - `os`
  - `pandas`
  - `zipfile`
  - `sklearn`
  - `numpy`

---

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/larasofiacantero/PS2.git

2. Dirigite al directorio del proyecto:
   ```bash
   cd PS1

3. Instala las dependencias desde el archivo requirements.txt disponible en scripts
  ```bash 
  pip install -r requirements.txt

---


## Uso

1. Scripts:
Contiene los archivos de Python con los códigos necesarios para desarrollar el trabajo.

2. Documents:
Archivos PDF que contienen las conclusiones y las respuestas a las preguntas planteadas en el trabajo.

---

## Estructura del proyecto
En resumen, el repositorio se distribuye así:
PS1/
├── documents/        # Archivos PDF con resultados y conclusiones
├── scripts/          # Código fuente del proyecto
├── requirements.txt  # Lista de dependencias
└── README.md         # Este archivo