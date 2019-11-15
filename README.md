## El taller de Papá Noel

### Premisa
La entrada de datos, va a ser fija, en un archivo .py dentro de variables
de tal modo, que podremos hacer un simple import de cada variable que necesitemos 
si queremos probar a cambiar alguna variable, solo tendremos que cambiarla en el archivo.py

### Descripción

- nenes
    - pueden hacer lista de regalos (es el archivo de la premisa)
    - los nenes pueden ver la lista de regalos de otros nenes (amigos suyos)
    - los regalos vetados no aparecerán en la lista de los amiguitos
    - los nenes podrán comentar acciones buenas que han hecho durante el día
    - los nenes tendrán karma, comenzando por 0
    - según el karma pueden elegir un número de regalos que además no podrán ser los más famosos

- papás
    - los papás deben dar de alta a los nenes para que los nenes puedan usar la app
    - los papás pueden vetar regalos por edad (los nenes no podrán verlos)
    - reciben lista de regalos
    - pueden eliminar elementos de la lista de regalos
    - los papás pueden validar esas opciones para que Papá Noel los vea

### Condiciones

NO NOS PREOCUPAMOS DE LOGAR A NADIE

En una primera fase, se hará sin MVC y sin delivery Mechanism (sin flask), sin base de datos, sin persistencia real (persistencia la metemos en el archivo .py famoso fake de data)