# UEES Maestria en Inteligencia de Negocios
# Actividad 3: Implementación de Redes Neuronales desde Cero

**Curso:** Inteligencia Artificial
**Proyecto Final:** Chatbot Conversacional Multimodal para Servicio al Cliente (Proyecto 5)  
**Grupo:** # tarea-redes-neuronales-grupo1
**Integrantes:** GRANDA CASTILLO CARLOS ALFONSO,
CAMPOVERDE CRESPO RICARDO ANDRÉS,
NUÑEZ COCHA ERICK JOAN,
TUÁREZ VERGARA VIVIANA CAROLINA,
**Fecha:** Diciembre 2025

## Descripción General

Esta actividad consiste en la implementación **desde cero** (usando únicamente NumPy) de una red neuronal feedforward aplicada a la clasificación de intenciones en un chatbot de servicio al cliente. Se incluyen:

- Red neuronal con ≥2 capas ocultas
- Soporte para activaciones: ReLU, Sigmoid y Tanh
- Inicialización Xavier/He
- Forward y backpropagation manual
- Experimentos comparativos de arquitecturas, activaciones y learning rates
- Comparación con baseline (regresión logística)
- Análisis de resultados y roadmap hacia el proyecto final

## Estructura del Repositorio
tarea-redes-neuronales-grupo1/
├── README.md
├── requirements.txt         ← ¡Nuevo!
├── data/
│   └── intent_data.csv
├── notebooks/
│   ├── 01_implementacion_red.ipynb
│   ├── 02_experimentacion.ipynb
│   └── 03_analisis_resultados.ipynb
├── results/
│   └── ... (gráficas y csv)
└── docs/
    └── reporte_tecnico.md

## Requisitos Previos

En Colab, todas las librerías ya vienen preinstaladas.

## Instrucciones de Instalación y Ejecución Google Colab 

1. **Abrir el proyecto en Google Drive**
   - Asegúrate de tener la carpeta `tarea-redes-neuronales-grupo1` en tu Google Drive.

2. **Ejecutar los notebooks en orden:**

   Abre cada notebook haciendo doble clic o clic derecho → "Abrir con → Google Colaboratory"

   **Orden recomendado:**

   1. `01_implementacion_red.ipynb`
      - Implementa la clase `NeuralNetwork`
      - Crea y guarda los datos sintéticos
      - Pruebas iniciales

   2. `02_experimentacion.ipynb`
      - Ejecuta todos los experimentos puede tardar 3-8 minutos
      - Genera automáticamente el archivo `results/performance_comparison.csv`
      - Crea todas las gráficas en la carpeta `results/`

   3. `03_analisis_resultados.ipynb`
      - Carga los resultados
      - Genera análisis avanzado y gráficas finales
      - Incluye conclusiones y roadmap

3. **Ejecutar todo el notebook**
   - En cada notebook: Menú → **Entorno de ejecución** → **Ejecutar todo** (Ctrl+F9)
   - La primera celda monta tu Google Drive (acepta los permisos)


