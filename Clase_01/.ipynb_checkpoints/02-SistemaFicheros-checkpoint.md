# Sistema de Ficheros

Toda la estructura de directorios en los sistemas basados en **UNIX** parte de un directorio raíz también llamado directorio **root** y que se simboliza por `/`. De este directorio, es desde donde nacen todo el resto de los directorios. Cualquier dirección de archivo o carpeta en Linux empieza por el directorio raíz o `/`, seguido de todos los directorios y subdirectorios que lo contienen, separados cada uno de ellos por `/`.

![FileSystem](images/FileSystem.jpg)

## Directorios principales:

- **/root**: Directorio principal del administrador del sistema
- **/boot**: Contiene archivos estátcos requeridos para arrancar el sistema operativo
- **/etc**: Directorio reservado para los archivos de configuración locales
- **/home**: Directorio de los diferentes usuarios del sistema operativo
- **/mnt**: Directorio creado para montar sistemas de archivos que se van a utilizar de forma temporal
- **/proc**: Directorio que contiene archivos especiales que envían o extraen información del kernel
- **/sys**: Directorio que contiene los archivos de configuración del sistema operativo que se está ejecutando
- **/bin** y **/sbin**: Directorio de archivos ejecutabls del sistema operativo. El segundo es propiedad del usuario root
- **/lib**: Directorio de librerias compartidas