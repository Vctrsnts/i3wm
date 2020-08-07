# i3-wm

Fichero de configuració de mi anterior gestor de ventanas I3wm.

Esta pensado para funcionar en un GNU/Debian

Contiene los siguientes ficheros:

* fonts : directorio donde estan las fuentes para i3-wm ( este directorio tiene que estar oculto )
* gtk-3.0 : directorio que contiene el fichero de configuración de las aplicaciones gtk3
* i3 : directorio que contiene los archivos de configuración de i3-wm
  * config :fichero de configuración de i3-wm
  * i3blocks.conf : fichero de configuración de la barra de estado
  * example_config.txt : fichero de ejemplo de i3-wm que puede servir como modelo
* i3blocks : ficheros que se necesitan para visualizar la información de la bateria y de la papelera
  * En este caso son "trash" y "battery". Se tienen que copiar en /usr/share/i3blocks
  * En el caso de "battery" necesita el paquete "ACPI"
* rofi : ficheros / templates para el lanzador de aplicaciones.
* scripts : directorio donde esta lo necesario para bloquear la pantalla en caso de necesidad
* packages_install_i3wm : Todos los paquetes que tengo instalados para poder usar i3-wm
  * En este caso es para una distribución de GNU/Debian.
