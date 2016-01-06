Bienvenidos a Next-OS Project.

Instalar Pngquant para optimizacion de png:

sudo apt-get install pngquant

Sincronizar codigo:

repo init -u git://github.com/Next-OS/android.git -b mm

Descargamos el codigo fuente con:

repo sync

Una vez tengamos el codigo descargado, compilamos con:

. build/envsetup.sh

brunch

seleccionamos nuestro dispositvo empezara a compilar.

Si no tienes las dependencias de tu dispositivo ya agregadas deberas añadir una caperta llamada local_manifests dentro de la carpeta .repo y en ella añadir el roomservices.xml correspondiente a tu dispositivo.

Estos roomservices.xml lo puedes encontrar en este link:

https://github.com/Next-OS/local_manifests
