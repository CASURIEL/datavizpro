#### IN ENGLISH
# 📊 Interactive Data Visualization App with Streamlit

## 📝 Description

This application allows you to load datasets in **CSV** or **Excel** format, perform basic exploratory data analysis, and generate interactive visualizations easily.  
It is built with **Streamlit**, a powerful tool for quickly and intuitively creating web interfaces with Python.

---

## ⚙️ Requirements

- **Python** 3.8 or higher  
- **Required libraries:**

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

## Installation and Execution
- 1. Clone this repository or download the source code.
- 2. Install the required dependencies using pip:
    ```text
        pip install -r requirements.txt
- 3. Run the Streamlit application:
    ```text
        streamlit run app.py
- 4. The app will be available in your browser at: http://localhost:8501
- 5. Load a CSV or Excel dataset to start exploring and visualizing your data.

## 🚀 Step-by-step Setup
- **Step 1:**  Clone this repository or download the source code:
    ```text
        git clone https://github.com/casuriels/datavizpro.git
        cd tu-repositorio

- **Step 2:** Create and activate a virtual environment:
      - 1. # On Windows:
            ```text
                python -m venv .venv
                .\venv\Scripts\activate

      - 2. # On macOS/Linux:
            ```text
                python3 -m venv venv
                source venv/bin/activate

- **Step 3:** Install requirements:
    ```text
        pip install -r requirements.txt

- **Step 4:**  Run the application:
    ```text
        streamlit run app.py

- **Step 5:** Open your browser and go to http://localhost:8501.
    Upload a .csv or .xlsx file to begin exploring and visualizing your data.

## 📂 Project Structure:
    ```text
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

## 📌  Notes:
You can upload .csv or .xlsx files directly from the app interface.
This tool is perfect for exploring and visualizing data without needing advanced programming knowledge.

## 🤝 Contributions    
Contributions are welcome!
If you want to improve this tool or add new features, feel free to submit a pull request.

---
#### EN ESPAÑOL
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
2. Instala las dependencias necesarias con pip: 
    ```text
        pip install -r requirements.txt
3. Ejecuta la instalación de Streamlit:
    ```text
        streamlit run app.py
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
    ```text
        pip install -r requirements.txt

- **Paso 4:** Ejecuta la aplicación con Streamlit:
    ```text
        streamlit run app.py

- **Paso 5:** Abre tu navegador en http://localhost:8501.
    Carga un archivo .csv o .xlsx para comenzar a explorar y visualizar tus datos.

----
## 📂 Estructura del proyecto:
    ```text
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