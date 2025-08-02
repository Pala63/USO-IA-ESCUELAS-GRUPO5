# 📚 Análisis del Uso de Asistentes de IA en la Vida Estudiantil

Este proyecto analiza el uso de asistentes de inteligencia artificial (IA) por parte de estudiantes de distintas disciplinas académicas. Usamos un subconjunto del dataset `ai_assistant_usage_student_life.csv` para explorar cómo los estudiantes interactúan con estos sistemas, qué tan satisfechos están y si estarían dispuestos a usarlos nuevamente.

---

## 📊 Visualización de los Resultados

![Gráfico del Análisis](grafico_final.png)

### Parámetros visualizados:

- **Sessions (Sesiones Totales):** Cantidad de veces que se utilizó el asistente por disciplina.
- **UsedAgain (%):** Proporción de estudiantes que volverían a usar el asistente.
- **SatisfactionRating:** Valoración promedio de satisfacción (de 1 a 5).

---

## 🧠 Hallazgos Clave

- Las disciplinas con más sesiones son *Biología*, *Ciencias de la Computación* y *Ingeniería*.
- La satisfacción y la intención de reutilizar el asistente son sorprendentemente altas en *Historia* y *Psicología*, a pesar de no liderar en sesiones totales.
- Las valoraciones están agrupadas alrededor de 3.4, mostrando una percepción positiva general.
- La fidelización (UsedAgain) se mantiene bastante uniforme, lo que indica que el asistente tiene potencial de adopción transversal entre disciplinas.

---

## 🔄 Reproducir el análisis en Google Colab

Puedes ejecutar este proyecto directamente desde Google Colab con el siguiente notebook:

📎 [Haz clic aquí para abrir en Colab](https://colab.research.google.com/drive/1QPjtZkh4X8F3VG7B__lhzRSitnCz3IFW#scrollTo=6edcca56)

O sigue los pasos:

1. Sube el archivo `ai_assistant_usage_student_life.csv` desde tu repositorio o desde [aquí](https://github.com/Pala63/USO-IA-ESCUELAS-GRUPO5/blob/main/data/ai_assistant_usage_student_life.csv).
2. Instala la librería necesaria:  
```python
!pip install -U kaleido
