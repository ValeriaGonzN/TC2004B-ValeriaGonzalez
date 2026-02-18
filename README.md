\# TC2004B - Análisis de Ciencia de Datos



\*\*Nombre:\*\* Valeria González Nava

\*\*Matrícula:\*\* A00842141

\*\*Semestre:\*\* Febrero-Junio 2026



\## Descripción



Repositorio personal para el curso TC2004B. Contiene notebooks y proyectos del semestre.



\## Estructura



TC2004B-TuNombre/

├── README.md

├── .gitignore

├── notebooks/      # Jupyter Notebooks

└── data/          # Datasets (cuando aplique)



\## Contenido por Semana



\### Semana 1

\- Práctica de Git/GitHub

\- Primer notebook con dataset Iris

\- Familiarización con herramientas



\## Contacto



\- Email: a00842141@tec.mx

\- GitHub: \[@ValeriaGonzN](https://github.com/ValeriaGonzN)



\## Acceso Rápido

\- \[Práctica Iris (Notebook)](./notebooks/semana1\_practica\_iris.ipynb)

\- \[Información personal] (Data)](./data/info.txt)

## Setup Local

### Requisitos
- Python 3.8+
- Git

### Instalación

#### 1. Clonar repositorio
```bash
git clone https://github.com/ValeriaGonzN/TC2004B-ValeriaGonzalez
cd TC2004B-ValeriaGonzN
```

#### 2. Crear ambiente virtual

**Mac/Linux:**
```bash
python3 -m venv tc2004b_env
source tc2004b_env/bin/activate
```

**Windows (PowerShell):**
```bash
python -m venv tc2004b_env
tc2004b_env\Scripts\Activate.ps1
```

#### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

#### 4. Ejecutar Jupyter
```bash
jupyter notebook
```

Navega a `notebooks/` y abre el .ipynb

Kernel → Restart & Run All

### Desactivar ambiente
```bash
deactivate
```

### Problemas Comunes

**Error: comando no encontrado**
- Verifica que Python esté instalado: `python --version`

**Error de permisos (Windows)**
- Ejecuta: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

**ModuleNotFoundError**
- Verifica que el ambiente esté activo
- Reinstala dependencias: `pip install -r requirements.txt`