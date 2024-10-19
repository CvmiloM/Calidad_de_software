# Mi Tienda D - Calidad de software

- Calidad de software Este proyecto es una tienda en línea creada con Django. Aquí encontrarás toda la información necesaria para configurar y ejecutar este proyecto en tu máquina local.

## Requisitos Previos

Asegúrate de tener instalados los siguientes requisitos antes de comenzar:

- Python 3.6 o superior
- Django
- Pillow

## Instalación

Sigue estos pasos para configurar el proyecto:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   
Crea y activa un entorno virtual:
python -m venv env
source env/bin/activate  # En Windows usa `env\Scripts\activate`

2. **Instala las dependencias necesarias**
   ```bash
    pip install django
    pip install pillow

3. **Configuración**
Configura las variables de entorno:

Crea un archivo .env en el directorio raíz del proyecto y añade tus variables de entorno según sea necesario.

Realiza las migraciones:

    python manage.py makemigrations
    python manage.py migrate

Crea un superusuario(opcional):
    python manage.py createsuperuser

Ejecutar el Servidor
Para iniciar el servidor de desarrollo, utiliza el siguiente comando: python manage.py runserver








