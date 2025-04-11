# 📊 Aplicación Interactiva de Visualización de Datos con Streamlit

## 📝 Descripción

Esta aplicación permite cargar datasets en formato **CSV** o **Excel**, realizar un análisis exploratorio básico y generar visualizaciones interactivas de manera sencilla.  
Está construida con **Streamlit**, una herramienta poderosa para crear interfaces web con Python de forma rápida e intuitiva.

---

## ⚙️ Requisitos

- **Python** 3.8 o superior
- **Librerías necesarias:**

  ```text
  matplotlib==3.10.1  
  numpy==2.2.4  
  openpyxl==3.1.5  
  pandas==2.2.3  
  plotly==6.0.1  
  seaborn==0.13.2  
  streamlit==1.44.1  
  scikit-learn==1.6.1
  statsmodels==0.14.4


## Instalación y ejecución
1. Clona este repositorio o descarga el código fuente.
2. Instala las dependencias necesarias con pip: `pip install -r requirements.txt`
3. Ejecuta la instalación de Streamlit: `streamlit run app.py`
4. La aplicación estará disponible en tu navegador en `http://localhost:8501`
5. Carga un dataset CSV o Excel para comenzar a explorar y visualizar tus datos

## 🚀 Instalación y ejecución
- **Paso 1:** Clona este repositorio o descarga el código fuente:

    ```text
        git clone https://github.com/casuriels/datavizpro.git
        cd tu-repositorio

- **Paso 2:** Crea y activa un entorno virtual:

    ```text
      1. En Windows:
          python -m venv .venv
          .\venv\Scripts\activate
      2. En mac/OS/Linux:
          python3 -m venv venv
          source venv/bin/activate

- **Paso 3:** Instala los requerimientos:
    pip install -r requirements.txt

- **Paso 4:** Ejecuta la aplicación con Streamlit:
    streamlit run app.py

- **Paso 5:** Abre tu navegador en http://localhost:8501.
    Carga un archivo .csv o .xlsx para comenzar a explorar y visualizar tus datos.

## 📂 Estructura del proyecto:

📁 datavizpro/
├── .gitignore
├── LICENSE
├── README.md
├── app.py
├── requirements.txt
├── .streamlit/
│   └── config.toml
├── data/
│   └── ejemplo.csv
└── .venv/  

## 📌 Notas:
Puedes cargar archivos .csv o .xlsx desde la interfaz de la app.
Esta herramienta es ideal para explorar y visualizar datos sin necesidad de conocimientos avanzados de programación.

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar esta herramienta o agregar nuevas funcionalidades, no dudes en hacer un pull request.