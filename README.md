# POWERSHELL SCRIPTS

<p>Proyecto destinado a <strong>FINES EDUCATIVOS</storng></p>

## Descripción

<p>Script que automatiza la descarga de un video generado por partes de manera dinámica.</p>

## Instalación y Ejecución

1. Clonar el repositorio
```sh
  git clone https://github.com/elciberprofe/powershell-scripts.git
  ```
2. Descomprimir ffmpeg.rar
3. Abrir el terminal de PowerShell y acceder a la carpeta del proyecto
```sh
  cd 'C:\Users\elciberprofe'
  ```
4. Ejecutar el script
```sh
  .\descargarVideo-v1.ps1
  ```
  
 ## Ejercicios a Desarrollar
1. Realiza un FORK del proyecto en tu GITHUB y clona el repositorio a tu ordenador local
2. Mejora el SCRIPT para que a partir de la URL del video original se genere automáticamente la URL de la API
3. Mejora el SCRIPT para que solamente ejecute FFMPEG si existen partes de videos en el directorio
4. Mejora el SCRIPT para no descargue el contenido JSON durante el proceso y lo mantenga en memoria
5. Mejora el SCRIPT para que realice la descarga de varios videos a través de leer un fichero TXT
6. Mejora el SCRIPT para que a partir de una URL real con todos los videos realice la descarga de todos ellos
