# MCDI503 - Exploración Inteligente de Ciencia de Datos
## Avance del Proyecto - Fase 1: Implementación inicial del análisis exploratorio de datos (EDA) 

**Grupo:** GRUPO N°1

**Integrantes:**

- Pablo Ignacio Balbontín Constenla @pabbalbontin-maker
- Melany Esmeralda Reyes Leiva @melanyreyesy
- Ingeborg Andrea Muñoz Carnot @dark452
- Mario Alejandro López Pulgar @malp2203

**Docente:** Raúl Calvo

**Fecha:** Septiembre de 2026

**Dataset**: Titanic

---
## Sumativa N°1

## 1. Descripción del proyecto

 El propósito de este avance es explorar la estructura, calidad y patrones iniciales del dataset Titanic para identificar qué variables se asocian aparentemente con la supervivencia de los pasajeros, estableciendo una base técnica reproducible para las fases posteriores del proyecto.

 ## 2. Estructura del repositorio

 ```
MCDI503_GRUPO1/
├── docs/                           # Carpeta para futuros documentos  
├── notebooks/
│   └── mcdi503_f1_sumativo_grupo1.ipynb         # Notebook Ejecutable
├── figures/                        # Figuras del informe
├── requirements.txt
└── README.md
```

## 3. Reproducir el análisis

```bash
git clone https://github.com/dark452/MCDI503-grupo1.git
cd MCDI503-grupo1
python -m venv .venv
source .venv/bin/activate          # en Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/mcdi503_f1_sumativo_grupo1.ipynb
```