## Ejemplo_SqlAlchemy Flask

* Información tomada de https://www.digitalocean.com/community/tutorials/how-to-use-flask-sqlalchemy-to-interact-with-databases-in-a-flask-application

* **Importante**
  * Trabajar dentro de la carpeta **proyecto01**
  * **Copiar** el archivo config.py.bk a **config.py**
  * Para construir la base de datos:
    * En el cmd o terminal ejecutar: **export FLASK_APP=app**
    * En el cmd o terminal ejecutar:
    ```
    flask shell
    ```

    En el shell ejecutar el siguiente código:
    ```
      from app import db, Docente
      db.create_all()
    ```
    Salir del shell
  * Levantar la aplicación desde consola:
    ```
      flask run
    ```
