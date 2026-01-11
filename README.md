# European Drug Consumption Analysis

Análisis exploratorio y multivariante del consumo de estupefacientes en Europa utilizando datos oficiales.  
El proyecto estudia cómo varía la prevalencia de consumo según el sexo, la edad, el país y el tipo de sustancia, con el objetivo de identificar patrones y desigualdades relevantes para la salud pública.

---

## 🎯 Objetivo

Analizar los patrones de consumo de sustancias legales e ilegales en países europeos y evaluar cómo influyen:
- El género  
- El grupo de edad  
- El país  
- El tipo de sustancia  

para comprender mejor las diferencias sociodemográficas y geográficas.

---

## 🧪 Hipótesis

- **H1**: Los hombres presentan una mayor prevalencia de consumo que las mujeres en todos los grupos de edad.  
- **H2**: Existen diferencias significativas en la prevalencia del consumo entre países europeos.

---

## 📊 Dataset

El conjunto de datos incluye información sobre:
- País  
- Sexo  
- Grupo de edad  
- Tipo de sustancia (alcohol, tabaco, cannabis, cocaína, éxtasis, anfetaminas, LSD)  
- Prevalencia de consumo  

Los datos proceden de fuentes oficiales europeas y reflejan patrones reales de consumo.

---

## 🛠️ Tecnologías utilizadas

**Lenguaje y entorno**
- Python 3  
- Jupyter Notebook  
- Visual Studio Code  

**Análisis y visualización**
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  

**Control de versiones**
- Git  
- GitHub  

---

## 📈 Principales resultados

- Los hombres presentan una mayor prevalencia de consumo que las mujeres para todas las sustancias y en todos los grupos de edad.  
- El alcohol y el tabaco son las sustancias más consumidas en todos los países.  
- El cannabis es la droga ilegal con mayor prevalencia, especialmente entre jóvenes adultos (15–34 años).  
- Existen grandes diferencias entre países europeos en los patrones de consumo, tanto para sustancias legales como ilegales.  
- El consumo está influido por una combinación de factores individuales (sexo y edad) y contextuales (país y tipo de sustancia).  

---

## 📁 Estructura del repositorio

```bash
EDA_Ansioliticos_España/
│
├── README.md              # Documentación del proyecto
├── main.ipynb             # Notebook final con el EDA
├── Memoria.pdf            # Informe técnico completo
├── Presentacion.pdf       # Presentación del proyecto
└── src/
    ├── data/              # Datos utilizados (CSV,muestras)
    ├── img/               # Gráficos e imágenes exportadas
    ├── notebooks/         # Notebooks de desarrollo
    └── utils/
        └── requirements.txt
```

## ▶️ Cómo ejecutar el proyecto

Clonar el repositorio:
```bash
git clone https://github.com/luciajp-ds/EDA_ansioliticos_esp.git
```
Acceder al directorio del proyecto:
```bash
cd eda_european_drug
```
Instalar dependencias:
```bash
pip install -r requirements.txt
```
Ejecutar el notebook principal:
```bash
jupyter notebook main.ipynb
```

## 📌 Notas finales

Este proyecto forma parte de mi formación en Data Science y tiene un enfoque exploratorio y descriptivo.
En trabajos futuros se podrían incorporar técnicas inferenciales y modelos estadísticos para cuantificar de forma precisa el impacto de cada variable.

