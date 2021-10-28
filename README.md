1. La aplicacion necesita Python version 3.7, puede ser una version Alpine.
2. El directorio de trabajo debe ser `/code`
3. Va a necesitar las siguientes variables de entorno:
    ```
    FLASK_APP=app.py
    FLASK_RUN_HOST=0.0.0.0
    ```
4. Van a ser necesarios los paquetes: `gcc musl-dev linux-headers`
5. Van a necesitar un archivo `requirements.txt` con este contenido:
    ```
    flask
    redis
    ```
    Luego instalar con `pip install -r requirements.txt`
6. La aplicacion utiliza el puerto 5000
7. Copiar todo el contenido de la app y ejecutarla con `flask run`

**NOTA:**Sera necesario un Redis para conservar la cuenta.