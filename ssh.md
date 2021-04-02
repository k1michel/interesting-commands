# COMMAND SSH

- `ssh AuthenticationPreferred=password pi@192.168.43.221` crear comunicacion ssh con dispositivo usando unico comando
    - En realidad es posible configurar ssh desde el archivo de configuracion usando editor de texto

```
Host MichelRPi                          # Nombre referido a esta configuracion
  HostName 192.168.43.221               # IP host
  PreferredAuthentications password     # Por defecto usar contraseña como metodo de autentificacion
  User pi                               # Nombre del usuario que existe en la maquina remota
```