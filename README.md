# Paquete DEB vx-dga-l-scratch-2-offline

Paquete que crea el instalador de scratch 2 offline para un equipo Vitlalinux. Dicho instalador permite la instalación de la última versión de scratch a la edición del paquete mediante AdobeAir de forma sencilla.
Es necesario seguir el asistente del mismo.

# Usuarios Destinatarios

Todos los equipos Vitalinux EDU DGA que se desee instalar Scratch2 Offline de forma cómoda

# Aspectos Interesantes:
```
Ninguno
```
# Como Crear el paquete DEB a partir del codigo de GitHub
Para crear el paquete DEB será necesario encontrarse dentro del directorio donde localizan los directorios que componen el paquete.  Una vez allí, se ejecutará el siguiente comando (es necesario tener instalados los paquetes apt-get install debhelper devscripts):

```
apt-get install debhelper devscripts
/usr/bin/debuild --no-tgz-check -us -uc
```

# Como Instalar el paquete generado vx-dga-l-*.deb:
Para la instalación de paquetes que estan en el equipo local puede hacerse uso de ***dpkg*** o de ***gdebi***, siendo este último el más aconsejado para que se instalen también las dependencias correspondientes.
```
gdebi vx-dga-l-*.deb
```
