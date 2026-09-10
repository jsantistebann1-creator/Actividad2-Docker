SANTISTEBAN NOVOA JULIO ALEJANDRO

# Tipos de redes en Docker

- Host
    En este tipo el contenedor usa directamente la red de la computadora
-IPvlan
    Trabaja principalmente usando direcciones IP
-Overlay
    Este tipo permite conectar contendores que estan en diferentes computadoras
-Macvlan
    Hace que el contenedor aparezca en la red como si fuera otro equipo
-Bridge
    Es la red mas usada porque permite que varios contenedores se comuniquen dentro de la misma computadora
-None
    El contenedor no tiene conexion a red, entonces se usa cuando se quiere el contenedor aislado

# Tipos de volumenes en Docker

- Named Volume
    Es el volumen donde nosotros le damos un nombre y docker se encarga de guardar los datos
- Ananymous Volume
    Es un volumen creado automaticamente por docker y no tiene un nombre elegido por nosotros
- Bind mount
    Este tipo de volumen nos permite usar carpetas de nuestra computadora dentro de un contenedor
- tmpfs
    Guarda los da tos de forma temporal en la memoria de la computadora, donde se pierden cuando el contenedor se detiene

CAPTURAS DE PANTALLA DE LO TRABAJADO:

![Imagen 1](./img/image-1.png)

![Imagen 2](./img/image-2.png)

![Imagen 3](./img/image-3.png)

![Imagen 4](./img/image-4.png)

![Imagen 5](./img/image-5.png)

![Imagen 6](./img/image-6.png)

![Imagen 7](./img/image-7.png)

![Imagen 10](./img/image-10.png)

![Imagen 12](./img/image-12.png)

![Imagen 11](./img/image-11.png)

![Imagen 13](./img/image-13.png)

![Imagen 14](./img/image-14.png)

![Imagen 15](./img/image-15.png)

![Imagen 8](./img/image-8.png)

![Imagen 9](./img/image-9.png)

Despues se realizo cambios en .env.example para poner solo datos de prueba, despues de realizar las variables que se ocultaran por gitignore
aparte se cambio las variables en la parte del readme.

![Imagen 16](./img/image-16.png)

![Imagen 17](./img/image-17.png)

![Imagen 18](./img/image-18.png)
