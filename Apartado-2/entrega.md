# Entrega
1. Entrega los ficheros de ansible que has generado, comprimidos en un zip.
2. Entrada captura de pantalla accediendo a alguna máquina interna sin usar *vagrant ssh*.
3. Entrega capturas de pantalla donde se vean las puertas de enlaces de los dos equipos.
4. Entrega capturas de pantalla donde se vean las máquinas haciendo ping al exterior.
5. Entrega una captura de pantalla donde se vea un acceso a la página web alojada en la máquina *web* accediendo a *practica-tunombre.dominio.algo*. Entrega la línea de tu resolución estática en tu cliente para que funcione.
6. Entrega la instrucción y una prueba de funcionamiento para realizar una conexión desde la máquina web a la base de datos creada, usando el nombre *bd-tunombre.dominio.algo*.
7. Añade un nueva máquina llamada *cliente* conectada a la **red_intra**, configura el inventario de *ansible* y vuelve a pasar la receta para que esta máquina tenga acceso a internet.
8. (Optativa) Crea un rol llamado *wordpress* que realice todos los pasos necesarios para instalar WordPress en el servidor web.