# Trabajos Prácticos - Aprendizaje Automático 1 - Q2/2026

Repositorio oficial para el desarrollo y entrega de los trabajos prácticos obligatorios de la asignatura.

## 📂 Estructura del Repositorio

El proyecto se encuentra organizado de la siguiente manera:

```text
TP_AA1_Apellido1_Apellido2_Apellido3_Apellido4/
├── TP_1/
│   └── TP-regresion-AA1.ipynb
└── TP_2/
│    └── TP-clasificacion-AA1.ipynb
└── requirements.txt
```

TP_1/: Contiene el desarrollo, análisis y código correspondiente al trabajo práctico de regresión (TP-regresion-AA1.ipynb).

TP_2/: Contiene el desarrollo, análisis y código correspondiente al trabajo práctico de clasificación (TP-clasificacion-AA1.ipynb).   

## Integrantes del Grupo(Correo de Contacto):

Sebastián Perez (psebastian10101010@gmail.com)

Franco Venesia (francovenesia@gmail.com)

Joaquín Welschen (joaquinwelschen@gmail.com)

Iñaki Cruz Elizondo Rios (etios74@gmail.com)

---

## Configuración del entorno virtual

Este proyecto requiere **Python 3.12.10** y las librerías listadas en `requirements.txt`.

### 1. Verificar instalación de Python 3.12.10
Comprobar la versión instalada:

```
python --version
```

[Descargar Python 3.12.10](https://www.python.org/downloads/release/python-31210/)

### 2. Crear entorno virtual

#### Windows - CMD
```
python -m venv venv
venv\Scripts\activate
```

#### Windows - PowerShell
```
python -m venv venv
.\venv\Scripts\Activate.ps1
# Si aparece error de permisos, ejecutar:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

#### Linux / macOS
```
python3.12 -m venv .venv
source venv/bin/activate
```
#### Desactivar el entorno
```
deactivate
```

### 3. Instalar dependencias
Dentro del venv, ejecutar:

```
pip install -r requirements.txt
```
Para confirmar que todo está instalado correctamente:

```
pip list
```

