# NOTAS EJCUTAR DESPLIEGUE

- 1. Conectar con ssh al dispositivo en cuestion    
    - Para la activacion de ssh se puede hacer sin monitor en la RPi, basta con cargar la tarjeta SD en Windows y crear un archivo vacio llamado `ssh` en la particion llamada `boot`, [más info](https://www.raspberrypi.org/documentation/remote-access/ssh/).
- 2. Conseguida la conexion SSH es posible realizar el despliegue con lineas de comandos
- 3. `git clone <url remota>` Clonamos el repositorio desde la ruta remota en un directorio local con el mismo nombre
- 4. RECORDATORIO: si el repositorio contiene un _venv_ es necesario instalar la herramienta desde la cual fue creado
     el entorno virtual en el dispositivo. Asi como, a continuacion ejecutar el instalador de esa herramienta para activar
     los paquetes que se incorporaron dentro y asi poder ejecutar el _venv_ tal y como se guardo.
        Referencias: [poetry.md](poetry.md)
                     [mas info](https://docs.python.org/3/library/venv.html#venv-def)