# Vagrant
Queremos automatizar la creación de un servidor LAMP usando Vagrant, el esquema que queremos desarrollar, que vemos en la imagen, tiene las siguientes características:

Es escenario tiene cuatro máquinas:

- router: que está conectada a una red pública ( **br0** ) y a una red privada (muy aislada) **red_intra**.
- web: En este servidor se instalará un servidor web. Esta máquina está conectada al **router** por la **red-intra**. Y esta conectada por otra red muy aislada *red-datos* a las otras máquinas del escenario.
- bd: En este servidor se instalará un gestor de bases de datos. Esta máquina está conectada al **router** por la **red-intra** . Y esta conectada por otra red muy aislada **red-datos** a las otras máquinas del escenario.
- san: Este el el servidor de almacenamiento. Posee almacenamiento configurado en RAID5 y nos permite compartir dispositivos de bloque por medio de iSCSI.
    - Esta máquina está conectada al **router** por la **red-intra**. Y esta conectada por otra red muy aislada red-datos a las otras máquinas del escenario.