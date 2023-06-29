# Howarts Rails

![img de index](https://github.com/toffycaluga/howarts_rails/blob/main/app/assets/images/howarts_rails_1.png)

Este es el repositorio de la aplicación web Howarts Rails, que muestra información sobre los personajes de Harry Potter, incluyendo su ubicación y casa.

## Requisitos

- Ruby version 3.2.2
- Ruby on Rails version 7.0.5.1
- PostgreSQL

## Instalación

1.  Clona este repositorio en tu máquina local:

        git clone https://github.com/tu_usuario/howarts_rails.git

2.  Navega al directorio del proyecto:

        cd howarts-rails

3.  Instala las dependencias:

        bundle install

4.  Confgura la base de datos :

    - Asegurate de tener PostgreSQL instalado y en funcionamiento.
    - Edita el archivo `config/database.yml` con la configuración de tu bas de datos.
    - crea la base de datos :

            rails db:create

    - Ejecuta las migraciones:

            rails db:migrate

5.  Carga los datos iniciales:

        rails db:seed

## Uso

1.  Inicia el servidor de desarrollo:

        rails server

    o
    rails s

2.  Abre tu navegador web y visi

## Llevar a producción

1.  Asegurate de tener la Herramienta de línea de comandos de Heroku (Heroku CLI).

2.  inicia sesion en heroku:

        heroku login

te saldra el siguiente mensaje
![img de index](https://github.com/toffycaluga/howarts_rails/blob/main/app/assets/images/heroku_1.png)

3.  presiona Control + click en el vinculo que aparece e inicia sesion en heroku.

4.  Una vez este la sesión iniciada, crea la aplicación en heroku con el siguiente comando.

        heroku create

5.  Enlaza el repo con la app de heroku.

        heroku git:remote -a nombre-de-la-app

6.  crea la base de datos en heroku.

        heroku run rails db:create -a howarts-rails

7.  corre las migraciones en heroku.

        heroku run rails db:migrate -a howarts-rails

8.  corre el seed en heroku.

        heroku run rails db:seed -a howarts-rails

y Listo disfruta de la app.

ta `http://localhost:3000` para ver la aplicacion en funcionamiento.

## Contribución

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1.  Crea un fork de este repositorio.

2.  Crea una rama nueva para tu contribución:

        git checkout -b feature/nueva-caracteristica

3.  Realiza tus cambios y commitea los archivos modificados:

        git commit -am 'Agrega una nueva característica'

4.  Envía tus cambios al repositorio remoto:

        git push origin feature/nueva-caracteristica

5.  Abre pull request en github.

Recuerda reemplazar `tu_usuario` en el enlace del paso 1 con tu nombre de usuario de GitHub. Además, asegúrate de proporcionar la información correcta sobre la versión de Ruby y Ruby on Rails requerida en la sección de requisitos.

⌨️ con ❤️ por [Toffy Caluga 🤡](https://github.com/toffycaluga)
