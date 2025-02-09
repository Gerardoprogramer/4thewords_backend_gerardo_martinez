# 4TheWords Backend - Gerardo Martínez

Este es el backend del proyecto **4TheWords**, un CRUD para un libro virtual de leyendas costarricenses. El backend está construido usando **FastAPI** y **MySQL**, y está configurado para utilizar un entorno virtual de Python.

## Requisitos

Antes de empezar, asegúrate de tener instaladas las siguientes herramientas:

- [Python 3.8 o superior](https://www.python.org/downloads/)
- [MySQL](https://www.mysql.com/)
- [Git](https://git-scm.com/)
- [pip](https://pip.pypa.io/en/stable/) (para instalar dependencias)
- (Opcional) [Visual Studio Code](https://code.visualstudio.com/) o tu editor preferido.

## Instalación

Sigue estos pasos para configurar y ejecutar el backend en tu máquina local:

### 1. Clonar el repositorio

Clona el repositorio de GitHub en tu máquina local:

git clone https://github.com/Gerardoprogramer/4thewords_backend_gerardo_martinez.git
cd 4thewords_backend_gerardo_martinez

###2. Crear un entorno virtual

python -m venv venv

###3. Activar el entorno virtual

windows
venv\Scripts\activate

macOs/Linux
source venv/bin/activate

###4. Instalar las dependencias

pip install -r requirements.txt

###Crear la base de Datos
Con el script de la base de datos que se encuentra en el backend

### Ejecutar el servidor de desarrollo
correr especificamente con este, por el puerto 8080
uvicorn app.main:app --host 127.0.0.1 --port 8080 --reload





