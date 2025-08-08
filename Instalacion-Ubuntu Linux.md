
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

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/f5942a80-4f7b-48c2-af8d-8f21c1c991c2" />

Una vez avanzado en los pasos con las configuraciones de gusto personal, se mostrara el siguiente mensaje.

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/1609dc77-e155-4b5f-8059-7b9ec198011f" />

Pueden saltarse el paso, **pero es muy recomendable actualizar**

Una vez acutalizado, el programa pide iniciar nuevamente el proceso de instalacion, este aparece al lado izquierdo de la pantalla

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/90be4160-8688-4016-a930-bc2095c25309" />

Una vez lanzando nuevamente el instalador del sistema operativo y avanzando con los pasos, es recomendable para los usuarios nuevos dejar las opciones recomendadas por el instalador:

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/573e08d1-6e7e-4c20-9f1b-b74ddd30bc90" />

Una vez llegado a esta interfaz, se selecciona la opcion de ```Advanced Features``` 

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/3783d4a2-c66c-4cdb-862d-4031c7cc1eb8" />

Se selecciona la opcion de ```Use LVM``` 

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/9b08e118-709b-46e1-8724-b74f3ea8013c" />

En el siguiente paso se solicita la creacion de usuario:

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/8d00b656-9d1e-4233-8ed1-1ad4499a7187" />

Conforme se avanzan en la instalacion, al final aparecera la siguiente interfaz, donde se hara click al boton ```Install```

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/94b5780c-d3e8-43a6-b7e1-23e7c88b8c57" />

Al presionar ```Install``` aparecera la siguiente pantalla de carga, la instalacion del sistema operativo puede tardar mucho.

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/83f0bca5-4331-45ee-b7e9-58efa0585547" />

Una vez terminada la instalacion del sistema operativo, se presiona en la opcion de ```Restart Now```

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/8cb604b5-1cdb-4b62-8cca-551fd7c0363a" />

Una vez se reinicia la maquina virtual, deberia aparecer la siguiente interfaz

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/be01b682-21ae-425b-9984-995e640e2907" />

Esto indica que el sistema operativo esta instalado exitosamente.

# Recomendacion

Cada vez que se instala un sistema linux, es recomendable ejecutar el siguiente comando en la consola:

```sudo apt-get update && sudo apt-get upgrade -y ```

# Esta instalacion funciona tanto para la maquina donde se aloja el SIEM como la para la maquina donde se colocara el agente que monitorea los eventos del equipo, ya que para ambos se utilizara Ubuntu

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/8ee681e0-9cad-466b-b841-8e5d0d7e4d7f" />

Con la finalidad de que el sistema opeartivo se actualice junto a las aplicaciones.
