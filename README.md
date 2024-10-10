*This is a repo where you can find a docker compose to build and run a service to mange a tickets system.

*Para este servicio se utiliza una base de datos  con la siguiente estructura:

![db_structure](https://github.com/user-attachments/assets/d34515d4-67b1-4981-a46f-1d6650fb2e26)




*Para levantar el servicio lo que tiene que hacer es lo siguiente:

1.-Tener Docker (desktop es conveniente) instalado

2.-Colocarse en la carpeta que contiene el archivo: docker-compose.yml de este repositorio clonado

3.-Una vez colocado en la carpeta, debera colocar el siguiente comando: docker-compose up, el cual levanta el servicio localmente en tu máquina en el espacio designado por docker, para detenerlo debes escribir: docker-compose down

4.-Ahora que tienes levantado el servicio en el puerto: http://127.0.0.1:5000/, puedes probar el servicio con 
los endpoints agregados en la colección de postman que te comparto por correo.


Al navegar hacía el puerto escrito en el punto 4, verás un mensje de bienvenida del servicio, como el siguiente:

![mensaje_bienvenida_api](https://github.com/user-attachments/assets/6f395e7e-b89e-48b7-9a1d-2ecabb1c4a10)







