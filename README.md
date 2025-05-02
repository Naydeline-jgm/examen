# examen
# Tarea 2.4 Despliegue de un Sistema LMS Moodle con GitHub/Docker en una Mac Pro 2019-Equipo 3.
Esta es una documentación para el despliegue de la aplicación de Moodle con una infraestructura basada en contenedores de Docker :

Si deseas realizar este despliegue, puedes obtenerlo clonando el repositorio:

git clone <URL>

--------------


# Paso 1. Entrar al directorio de Moodle.

cd moodle
Entrar al directorio del moodle .

-------------------

# Paso 2. Compile el docker-compose.ym

docker-compose up -d
Recopilación de archivo docker-compose.yml.
Nota: Si desea detener la ejecución puede en algún momento más adelante, puede ejecutar el comando:

docker-compose stop
Y para iniciarlo nuevamente:

docker-compose start

------------------

# Paso 3. Ingresar al Moodle

Ingrese a su navegador favorito y coloque la URL:

localhost:80
Esto debería desplegar un panel de Moodle .

Nota: Podrá iniciar sesión de hacer clic en iniciar sesión .

El usuario es: user.
La contraseña es: bitnami.

------------------------

# Paso 4. Creación de cursos, de usuarios y asganción de roles  

Una vez dentro del moodle podemos crear cursos, para ello, debemos navegar por los apartados:

- Courses/category 1/manage courses and categories/Add new course
Lo que permitirá ingresar los datos para la creación de un nuevo curso :

![image](https://github.com/user-attachments/assets/6b16d115-73fc-42b9-9c1d-7c1e85ce1742)

![image](https://github.com/user-attachments/assets/d9429a96-b3ea-4c01-9aa5-f6c9c081abe0)

![image](https://github.com/user-attachments/assets/d57b59e8-932a-437b-b4c0-f0fedf33f688)




