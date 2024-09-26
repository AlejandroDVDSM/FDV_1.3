# FDV_1.3

_**1. Crear un proyecto Unity 3D básico con control de versiones en Unity.**_

Abrimos Unity Hub y al crear un nuevo proyecto marcamos la casilla _"Use Unity Version Control"_.

![1  Use UVC](https://github.com/user-attachments/assets/c16b289c-ae8e-4219-a107-b844606c1cae)

_**2. Realizar 2 cambios, agregando 2 objetos 3D, por ejemplo, una esfera y un plano. Añadirles material de color rojo y azul respecivamente.**_

Creamos los dos GameObjects y les añadimos los dos materiales solicitados. Luego, desde la pestaña _"Unity Version Control"_, marcamos los cambios para subirlos al repositorio y pulsamos el botón _"Check in Changes"_.

![2  Objetos](https://github.com/user-attachments/assets/94c13c5b-2db9-425e-98db-90743dc1a74f)

_**3. Chequear los cambios en SCM**_

Cambios subidos al repositorio:
![3  Objetos en repo](https://github.com/user-attachments/assets/ba387dd4-519d-4554-9b11-9a4da136fb16)

_**4. Agregar un nuevo objeto, por ejemplo, un cilindro verde, guardar los cambios.**_

![4  Cilindro verde](https://github.com/user-attachments/assets/a1cf9bdd-a0ef-40f5-aa4c-2c70d7308d36)

![5  Cilindro verde UVC](https://github.com/user-attachments/assets/2ed931ab-fba9-4bcf-bc3c-c2295e1025b0)

_**5. Añadir una cápsula con una textura, agregar este cambio a una nueva rama.**_

Primero, creamos la nueva rama que llamaremos `develop`. Para ello, cambiamos a la vista _"Branches"_ desde la pestaña _"Unity Version Control"_. Tras esto, hacemos click derecho en la única rama creada (`main`) y elegimos la opción _"Create child branch..."_. Cuando la rama se ha creado, Unity nos cambia automáticamente a esa nueva rama por lo que los nuevos cambios que se suban irán a `main/develop`.

![6  Nueva rama](https://github.com/user-attachments/assets/c9f7d08a-dc75-4241-bcb8-12b356b24121)

Ahora, añadimos una textura al proyecto, creamos un material con esta y creamos una cápsula en la escena para poder asignarle el material.
La textura empleada se ha conseguido en: https://textures_free.artstation.com/projects/ZeOq81?album_id=5655538.

![7  Capsula](https://github.com/user-attachments/assets/f3cbfc3d-487d-4b71-b32d-8a40c18da7cd)

Finalmente, subimos los cambios al repositorio.

![8  Capsula UVC](https://github.com/user-attachments/assets/f0481bb9-b975-4c90-b430-140983f4fe8b)
