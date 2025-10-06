# Lab8 - Teoría (Laboratorio No. 8)

Descripción
-----------

Este repositorio contiene el material del Laboratorio No. 8 (parte teórica) para la asignatura de Teoría. El propósito principal es proporcionar el cuaderno con el código y las instrucciones necesarias para realizar los ejercicios y experimentos solicitados en la práctica.

Contenido
---------

- `src/Lab8-Codigo.ipynb` - Cuaderno Jupyter con el código y las actividades del laboratorio.
- `Teoria/Laboratorio No 8.pdf` - Enunciado del laboratorio y material teórico asociado.

Objetivos
---------

- Revisar y practicar los conceptos presentados en la sesión teórica del Laboratorio 8.
- Implementar y ejecutar los experimentos y ejercicios propuestos en el cuaderno Jupyter.
- Analizar resultados y completar las preguntas del enunciado.

Requisitos mínimos
------------------

- Python 3.8+ instalado.
- Jupyter Notebook o JupyterLab (se recomienda JupyterLab para mejor experiencia).

Instrucciones rápidas (Windows - PowerShell)
-------------------------------------------

1. Abrir PowerShell y posicionarse en la carpeta del proyecto:

```powershell
cd 'c:\Users\jlope\Documents\UVG\Teoria\Lab8\Lab8-Teoria'
```

2. (Opcional) Crear y activar un entorno virtual:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Instalar dependencias (recomendado):

Si ya existe el archivo `requirements.txt` en la raíz del proyecto, instala todas las dependencias listadas con:

```powershell
pip install -r requirements.txt
```

Si prefieres instalar paquetes manualmente o no usas `requirements.txt`, puedes instalar individualmente las librerías necesarias, por ejemplo:

```powershell
pip install jupyter matplotlib
```

4. Abrir el cuaderno Jupyter:

```powershell
jupyter lab  # o: jupyter notebook
```

5. En Jupyter, abrir `src/Lab8-Codigo.ipynb` y ejecutar las celdas en orden.

Entrega y buenas prácticas
--------------------------

- Guarda cualquier notebook modificado con tu nombre o matrícula (por ejemplo `Lab8-Codigo_Nombre.ipynb`).
- Responde las preguntas del enunciado dentro del notebook en celdas de texto (Markdown) o en un archivo adicional si se indica.

Contacto / Autor
-----------------

Repositorio preparado por el equipo de clase. Para dudas sobre el laboratorio, consulta al docente o al asistente de laboratorio.

Licencia
--------

Material para uso académico en el curso. Revisar restricciones con el docente si se desea redistribuir.

Dependencias detectadas
-----------------------

Del análisis del cuaderno `src/Lab8-Codigo.ipynb` se detectaron las siguientes importaciones usadas en las celdas de código:

- `time` (módulo de la librería estándar de Python)
- `matplotlib` (se usa como `matplotlib.pyplot`)

Para instalar las dependencias necesarias de forma rápida, usa el archivo `requirements.txt` incluido:

```powershell
pip install -r requirements.txt
```

Si el cuaderno se amplía y utiliza `numpy`, `scipy` o `pandas`, añádelas al `requirements.txt` o instálalas manualmente.
