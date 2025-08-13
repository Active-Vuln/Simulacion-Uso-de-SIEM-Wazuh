# Instalacion Ubuntu

Este es el procedimiento para instalar Ubuntu como el sistema que generara los eventos. A pesar de ser los mismos pasos para instalacion del Ubuntu que actuara como SIEM.

En este Ubuntu se habilitaran servicios como SSH para realizar pruebas de fuerza bruta y visualizar como actua el SIEM. La creacion de una sencilla pagina web que sea vulnerable a una subida de archivos sin santizacion.

# Pasos para instalar Ubuntu linux en el virtualizador

**Una vez instalado el virtualizador de preferencia, es hora de instalar el sistema operativo.**

En este caso se hara uso de VMware Workstation.

# Paso 1: Crear una nueva maquina virtual

Hacer click en la opcion ```File``` donde aparece una lista de opciones, se selecciona la opcion de ```New Virtual Machine``` 

<img width="278" height="250" alt="image" src="https://github.com/user-attachments/assets/b33a60f0-8aee-4ba5-82ba-750825e289a5" />

Aparecera la siguiente interfaz:

<img width="425" height="426" alt="image" src="https://github.com/user-attachments/assets/22f79bed-8c45-4be3-9891-0fda03f108f5" />

**Para las personas principiantes es recomendable mantener la opcion de ```Typical```.**

En el siguiente paso aparece la interfaz donde indica de que manera instalar la maquina virtual, si apartir de un archivo ISO, o crear la maquina virtual sin sistema operativo.

En este caso se instalara el sistema operativo que es Ubuntu Linux.

**En caso de no tener la imagen de Ubuntu Linux, se descarga en el siguiente enlace:**
https://ubuntu.com/download/desktop 

<img width="427" height="426" alt="image" src="https://github.com/user-attachments/assets/e5f3bbf9-c40f-430e-b542-dcf4ab2fc1c0" />

En el siguiente paso se solicita un nombre de usuario y contraseña temporal para la instalacion del Ubuntu Linux:

<img width="425" height="423" alt="image" src="https://github.com/user-attachments/assets/ee521fa8-e3e1-4fec-945a-028a940c671f" />

Una vez llenado el formulario, el siguiente paso da la opcion de nombrar la maquina virtual y ademas muestre la ruta donde se guarda la maquina virtual, **Es importante recordar la ruta donde se guarda la maquina virtual**

<img width="426" height="429" alt="image" src="https://github.com/user-attachments/assets/18554db7-5a81-4eee-bf31-dc08a68f2b20" />

En el siguiente paso se solicita la cantidad de disco duro que se le asignara al sistema operativo, es de la eleccion de cada uno colocar segun consideren necesario.

**Para principiantes se recomienda seleccionar la opcion de almacenar el disco virtual en un solo archivo**

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/23e359d5-f78e-4c28-8b50-35fecb066754" />

Por ultimo aparecera la siguiente informacion sobre la configuracion realizada

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/3970945e-326f-437d-82a5-b6d9830af5aa" />

Al finalizar la maquina virtual arrancara automaticamente.

<img width="720" height="400" alt="image" src="https://github.com/user-attachments/assets/3fe9f0fb-46dd-4ef6-bf1e-0bc53dd28c05" />

# Paso 2: Instalacion de Ubuntu

## En este paso se realizara la instalacion del sistema operativo, todo sera mediante interfaz grafica.

Una vez el sistema operativo termina de bootear correctamente, aparece lo siguiente:

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/26fc8211-498e-4bc5-a955-03a34c8196fb" />

Una vez avanzado en los pasos con las configuraciones de gusto personal, se mostrara el siguiente mensaje.

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/e2e1d28d-923a-4467-b65f-265cca827590" />

Pueden saltarse el paso, **pero es muy recomendable actualizar**

Una vez acutalizado, el programa pide iniciar nuevamente el proceso de instalacion, este aparece al lado izquierdo de la pantalla

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/fb876e50-5e2f-4dd0-80a7-6508d3014d30" />

Una vez lanzando nuevamente el instalador del sistema operativo y avanzando con los pasos, es recomendable para los usuarios nuevos dejar las opciones recomendadas por el instalador:

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/3b203b09-b4d1-41f8-a596-36f609ed3c6b" />

Una vez llegado a esta interfaz, se selecciona la opcion de ```Advanced Features``` 

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/73912866-ac08-4944-bcd5-ffbe1a01baea" />

Se selecciona la opcion de ```Use LVM```

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/abc6343e-8bb7-4cd3-987a-532d8884670e" />

En el siguiente paso se solicita la creacion de usuario:

**En este paso se configura a gusto de cada uno**

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/c1f4114f-7bd5-413e-93ad-538db32e727e" />

Conforme se avanzan en la instalacion, al final aparecera la siguiente interfaz, donde se hara click al boton ```Install```

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/5f2102de-80a2-4fe2-a0a4-83b42dc94e96" />

Al presionar ```Install``` aparecera la siguiente pantalla de carga, la instalacion del sistema operativo puede tardar mucho.

Una vez terminada la instalacion del sistema operativo, se presiona en la opcion de ```Restart Now```

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/2b99a4d4-debe-4346-9d74-41de8c09105e" />

Una vez se reinicia la maquina virtual, deberia aparecer la siguiente interfaz

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/f95e6fd0-1564-45e3-907b-d3e55a81b5b2" />

Esto indica que el sistema operativo esta instalado exitosamente.

# Recomendacion

Cada vez que se instala un sistema linux, es recomendable ejecutar el siguiente comando en la consola:

```sudo apt-get update && sudo apt-get upgrade -y ```

Este comando permite actualiza la lista de paquetes de los repositorios y las aplicaciones instaladas en su ultima version disponible, es imporatante realizarlo cada cierto tiempo.

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/823b2566-5df4-404c-87f4-210ed7a5dccc" />

# Paso 3: Instalacion y configuracion de servicio SSH

Este paso es para la instalacion del servicio ```SSH``` tambien conocido como ```Secure Shell```, generalmente este servicio corre por el puerto TCP 22.

Para instalar ```SSH``` se hace con el siguiente comando:

```sudo apt install openssh-server -y```

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/98a41aef-f758-45f0-9a1c-1d6593e96945" />

Una vez instalado ```SSH```, mediante: ```systemctl status ssh``` se puede ver el estado en que se encuentra el servicio (Activo o Inactivo)

<img width="882" height="164" alt="image" src="https://github.com/user-attachments/assets/e0d9d64d-40cb-447e-a19c-79c754d8c621" />

En este caso se encuentra inactivo, para activarlo, se corre el siguiente comando: ```systemctl start ssh```

<img width="1011" height="449" alt="image" src="https://github.com/user-attachments/assets/49c98389-ec01-43df-9935-c7b4141e4951" />

En caso de querer detener el servicio, se hace con el comando: ```systemctl stop ssh```

En caso de que el servicio necesite un reinicio, se hace con el comando: ```systemctl restart ssh```

# Paso 4: Instalacion de Apache server

En este apartado se instalara las herramientas necesarias para hacer una pagina web con subida de archivos sin santizacion.

Para ello se instalara el servidor de Apache.

- Se instala con el siguiente comando: ```sudo apt install apache2```

Se instalara php que es el lenguaje con el que se hara la pagina web.

- Se instala con el siguiente comando: ```sudo apt install php```

Por ultimo se instalara el modulo que hace la conexion de php con apache.

- Se instala con el siguiente comando: ```sudo apt install libapache2-mod-php```

**Tambien se puede instalar de la siguiente forma: ```sudo apt install apache2 php libapache2-mod-php```** 

<img width="850" height="277" alt="image" src="https://github.com/user-attachments/assets/e7b9c0db-d9f4-417f-9e78-af0111cd034a" />

Cuando se instala el servidor Apache2, se crea el siguiente directorio ```/var/www/html```, es importante conocerlo puesto que es donde se crea la pagina y se muestra una vez el servidor web se activa.

<img width="610" height="145" alt="image" src="https://github.com/user-attachments/assets/90c6bd2d-4b84-43b8-a38f-3b5bc9ea113e" />

Como se observa en la imagen anterior, se ve la estructura del directorio ```/var/www/```, dentro de ```html``` se encuentra un archivo ```index.html``` que es el archivo que crea apache y cuando se arranca el servidor se muestra en la web.

Para activar el servidor web, se realiza con el siguiente comando: ```systemctl start apache2```

Para ver el archivo ```index.html``` en la web, desde el navegador se coloca lo siguiente: ```localhost```

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/905a64ff-8c5c-4578-948f-b922f36fa8d0" />

De esta manera se confirma que el sistema operativo tiene una pagina web corriendo por el puerto TCP 80.

# Paso 4: Creacion de una pagina web con vulnerabilidad en la subida de archivos

Para este paso se creara un archivo php que tenga la funcionalidad de subir archivos sin verificar la extension, es decir sin sanitizar, la idea que verificar desde el SIEM como se registran estos compartimientos, ver cuando un atacante sube un archivo que contenga una ```Web Shell``` o una ```Reverse shell```.

Una ```Web Shell``` es la manera en que un atacante subi un archivo en el cual se solicita un parametro que permita la ejecucion remota de comandos de sistema, esto es peligroso porque permite al atacante ingresar dentro del sistema.

Una ```Reverse shell``` es cuando un atacante subi un archivo con codigo php u otro lenguaje de programacion y hace que el sistema regrese la conexion con una sesion ```bash``` o ```sh```.

Se crea un archivo llamado ```upload.php``` el cual su finalidad es la de subir archivos sin sanitizacion. Este se crea dentro de ```/var/www/html```, ademas se crea un directorio ```uploads``` que es donde se guardaran los archivos.

<img width="656" height="154" alt="image" src="https://github.com/user-attachments/assets/2b0b6f4c-b670-4c44-990d-a67b866c19b9" />

Desde la web se puede ver el archivo ```uploads.php```:

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/40d88963-3be5-46b6-b4f6-59c287123eda" />

Al subir un archivo, se guarda dentro de ```uploads```:

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/f96b4d38-3b85-45f2-b74e-f189dd39d1a8" />

# Este sistema operativo esta listo para realizar las pruebas basicas para la deteccion de eventos en el SIEM Wazuh
