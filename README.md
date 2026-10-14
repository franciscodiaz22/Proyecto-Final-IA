# Proyecto Final — Inteligencia Artificial (ISW-309)

Prototipo inteligente para la gestión de solicitudes de soporte técnico de
**Global AI Education, S.R.L.**

- **Participante:** Francisco José Díaz Abreu — Matrícula 100066529
- **Facilitador:** Edwin Aponte Reynoso
- **Escuela de Ingeniería y Tecnología — Universidad Abierta Para Adultos (UAPA)**
- **Santo Domingo, República Dominicana — Octubre 2026**

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Proyecto_Final_IA_Global_AI_Education.ipynb` | Notebook de Google Colab con el prototipo completo |
| `solicitudes_soporte_ia.csv` | Dataset de 90 solicitudes de soporte técnico (14 variables) |

## Componentes implementados

1. Carga y exploración del dataset
2. Búsqueda de una solicitud por número de ticket
3. Sistema básico de reglas para recomendar la acción inicial
4. Reconocimiento de patrones (5 análisis y 4 gráficas)
5. Agente inteligente **SIGA-IA**
6. Chatbot de orientación inicial **EduBot-GAE**
7. Modelo de Machine Learning (DecisionTreeClassifier) para predecir la prioridad

## Resultados

- Exactitud del modelo con las 9 variables: **78.26%**
- Exactitud sin `tiempo_estimado_min`: **65.22%**
- Recall de 1.00 en la categoría de prioridad Alta

## Cómo ejecutarlo

1. Abrir el notebook en Google Colab.
2. En la celda de carga, sustituir `USUARIO/REPO` por la ruta de este repositorio.
3. Ejecutar todas las celdas (Entorno de ejecución → Ejecutar todo).

El dataset se descarga automáticamente desde este repositorio mediante su enlace RAW,
por lo que no es necesario subir archivos manualmente.
