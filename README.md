# Crear un red virtual en VirtualBox

1 de Diciembre 2022

En esta práctica crearemos una red en Virtual Box para conectar en ella las máquinas con las que vamos a hacer las distintas prácticas.

## Crear la red ##

Para crear la red, lo primero que vamos a hacer es irnos a archivo, luego a herramientas y haremos clic en Network manager. Luego crearemos una Red NAT, para conectar las distintas máquinas virtuales:

![](img\img1.png)



Configuraremos la red que se llamará REDPRUEBA, la IP de la red será la 192.168.56.1/24 y la máscara de red 255.255.255.0.

Además de esto habilitaremos el DHCP, para que reparta las IP:



![](img\img2.png)



Una vez hecho esto tendremos que configurar cada máquina:

### Windows 10

Para configurar la máquina pulsaremos sobre ella y el botón configuración en el apartado de red estableceremos Red NAT y seleccionaremos nuestra red (REDPRUEBA)

![](img\img3.png)

Una vez configurada procederemos a iniciarla, una vez se ha iniciada abriremos una pantalla de comandos y observaremos si se ha hecho correctamente con el comando ipconfig:





