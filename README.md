### Fundamentos Tecnológicos
##### 9 de enero de 2023
# Nano
**Nano** es un editor de texto en la linea de comandos (la terminal) al que se le puede dar un formato Markdown `md`.

![Logo Nano](https://extassisnetwork.com/tutoriales/wp-content/uploads/nano-min.png.webp "Nano")

`.nanorc` es el archivo de configuración de nano.

- Instrucciones indicadas por el profesor Adolfo Antón Bravo
  - El directorio o carpeta `/etc` (importante la barra del inicio pues indica la raíz del sistema de directorios) 
  - Es donde se encuentran muchos de los archivos de configuración de las aplicaciones que se manejan en sistemas Unix/Linux
  - Lo que hicimos fue copiar con `cp` ese archivo en nuestro espacio de usuarix con el nombre `.nanorc` para configurarlo a nuestro  gusto
  - Como en otros comandos, cp sigue la estructura de `COMANDO ORIGEN DESTINO`, es decir, `cp` `/etc/nanorc ~/.nanorc`
  
La ruta de destino tiene algunas **características**:

- `~/` es un atajo u otra forma de escribir `/home/mi-nombre-de-usuarix/`
 
- El punto inicial del archivo `.nanorc` indica que será un archivo oculto, es decir, que no se mostrará en el Explorador de archivos de Windows o en un `ls` pero sí que existe. En el primer caso habría que activar la opción Ver archivos ocultos y en el segundo la opción `-a`, es decir, `ls -a` para verlo

- Una vez copiado, ya puedes editarlo con nano `~/.nanorc` (nótese que pongo la ruta con `~/` por si cuando lo escribes no estas en tu `HOME`, si estás ahí no hace falta ya que estás en ese directorio
