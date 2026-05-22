PRACTICA EXPRESS ESMODULE

Se monta un servidor Express que muestra una web de frases aleatorias creada con javascript.
Se agrega el Dockerfile que construye la imagen que engloba la app completa.

Preguntas:
- ¿Qué diferencia hay entre un servidor Express y Apache (el de la práctica A)? El servidor Express se está ejecutando en la máquina Host mientras que el servidor Apache se ejecuta en un contenedor.
- ¿Por qué añadimos "type": "module" al package.json? Para habilitar la importación/exportación de código entre ficheros js.
- ¿Qué ocurre cuando visitas http://localhost:3000 en el navegador? se llama al servidor Express y éste ejecuta los fichero js con los que se construye el html que se devuelve.
- ¿Qué ventajas tiene el servidor en un contenedor? Se puede ejecutar en cualquier máquina con Docker/Podman sin depender de que tenga las versiones que necesita de los módulos que usa (ya están instalados dentro del contenedor)
