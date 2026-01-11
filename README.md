
## **1. DESCRIPCIÓN BREVE**

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) sobre el consumo de estupefacientes en países europeos, con el objetivo de identificar patrones de prevalencia según género, edad y país, así como diferencias entre tipos de sustancias. El estudio se apoya en datos oficiales y busca aportar una visión clara que sirva como base para la reflexión en el ámbito de la salud pública y la prevención.


## **2. HIPÓTESIS PLANTEADAS**

El análisis se estructura en torno a las siguientes hipótesis principales:

H1. Los hombres consumen más estupefacientes que las mujeres en todos los grupos de edad y en todos los países.

H2. Existen diferencias significativas en la prevalencia del consumo de estupefacientes entre los países europeos.

Estas hipótesis permiten analizar la relación entre consumo, género, edad y contexto geográfico, identificando posibles desigualdades y patrones comunes.


## **3. TECNOLOGÍAS UTILIZADAS**

**Lenguaje y entorno**

Python 3.10+

Jupyter Notebook

Visual Studio Code

**Librerías de análisis**

Pandas

NumPy

**Visualización**

Matplotlib

Seaborn

Plotly

**Control de versiones**

Git

GitHub

**Gestión de datos**

CSV

OpenPyXL


## **4. ESTRUCTURA DEL REPOSITORIO**

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

## **5. INSTRUCCIONES DE REPRODUCCIÓN**

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


## **6. PRINCIPALES CONCLUSIONES**

De forma preliminar, el EDA permite observar:

El consumo de estupefacientes en Europa presenta una alta variabilidad, tanto entre países como entre grupos sociodemográficos, lo que refleja la existencia de patrones de consumo heterogéneos.

De forma consistente, los hombres muestran una mayor prevalencia de consumo que las mujeres, independientemente del grupo de edad o del tipo de sustancia analizada, lo que respalda la hipótesis H1.

Los jóvenes adultos (15-34 años) presentan mayores niveles de consumo de sustancias ilegales, especialmente cannabis, en comparación con el grupo de adultos de 15 a 64 años.

El alcohol y el tabaco son las sustancias con mayor prevalencia en todos los países analizados, aunque su intensidad varía notablemente entre contextos nacionales.

Existen diferencias claras entre países europeos en los patrones de consumo, tanto para sustancias legales como ilegales, lo que confirma la hipótesis H2 y pone de manifiesto la influencia del contexto geográfico y cultural.

El análisis multivariante evidencia que los patrones de consumo están condicionados por una combinación de factores individuales (sexo y edad) y contextuales (país y tipo de sustancia), reforzando la necesidad de enfoques diferenciados en el diseño de políticas de prevención.


