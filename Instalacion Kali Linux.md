# Instalacion de Kali Linux

Kali linux tiene dos formas de instalarse, una es descargando la maquina virtual desde la pagina oficial de Kali Linux.

La otra manera es descargar el archivo ISO de Kali Linux.

**Diferencias entre estas dos formas**

- Descargar la maquina virtual solo necesita ejecutarse en un virtualizador, ya la maquina virtual esta configurada.
- Descargar el archivo ISO es para realizar la instalacion desde cero en el virtualizador.

En la pagina oficial de Kali Linux presentan las dos formas de descargar el sistema operativo: https://www.kali.org/

<img width="1903" height="926" alt="image" src="https://github.com/user-attachments/assets/659ec8fe-930d-4690-add8-042f9749ac55" />

Para esta simulacion se hara la instalacion mediante archivo ISO.

# Paso 1: Crear una nueva maquina virtual

Como en los dos casos anteriores de instalacion de Ubuntu, se crea una nueva maquina virtual

Hacer click en la opcion ```File``` donde aparece una lista de opciones, se selecciona la opcion de ```New Virtual Machine``` 

<img width="278" height="250" alt="image" src="https://github.com/user-attachments/assets/b33a60f0-8aee-4ba5-82ba-750825e289a5" />

Aparecera la siguiente interfaz:

<img width="425" height="426" alt="image" src="https://github.com/user-attachments/assets/22f79bed-8c45-4be3-9891-0fda03f108f5" />

**Para las personas principiantes es recomendable mantener la opcion de ```Typical```.**

En el siguiente paso aparece la interfaz donde indica de que manera instalar la maquina virtual, si apartir de un archivo ISO, o crear la maquina virtual sin sistema operativo.

En este caso se instalara el sistema operativo que es Kali Linux.

Al seleccionar el archivo ISO se muestra un mensaje de que el virtualizador no detecta que sistema operativo es. 

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/03f04a65-a735-499c-ab06-7993ec5c15a8" />

En el siguiente paso solicita especificar que sistema operativo es. Se selecciona el sistema operativo Debian en su ultima version.

El porque de esto es debido a que Kali Linux, al igual que Ubuntu y Parrot son sistemas operativos basados en Debian.

En linux existen una inmensa cantidad de sistemas operativos basados en distintas distribuciones que tanto compañias como la comunidad crean.

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/e280012b-d3e3-4c95-b5e2-9fdeedca0dee" />

En el siguiente paso solicita nombrar la maquina virtual.

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/ef95528f-75c2-40ce-b32a-e736fdcbf067" />

Al continuar, se solicita dar la cantidad de disco duro deseada a la maquina virtual, para los usuarios no experimentados es recomendable seleccionar la opcion de ```Store virtual disk as a single file```

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/10816243-8caf-4163-95b9-473cf3d5473f" />

Por ultimo aparecera la ventana previa a la finalizacion de la creacion de la maquina virtual.

<img width="428" height="430" alt="image" src="https://github.com/user-attachments/assets/4001ef2c-fb67-46f8-aa82-49b3f6b9464b" />

# Paso 2: Instalar Kali linux

Una vez se arranca la maquina virtual, aparece la siguiente interfaz.

<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/db266abb-091a-4355-8b36-a780fed1f583" />

Para este laboratorio se hara la instalacion con interfaz grafica.

Una vez seleccionada la opcion de instalacion por interfaz grafica, aparece lo siguiente.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/c16799f2-0466-409c-9083-e03cd40c22ec" />

Una vez avanzado en la configuracion de idiomas, aparecera la siguiente interfaz que solicita agregar el nombre de ```hostname``` dentro de la maquina, se puede configurar al gusto de cada uno:

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/90257d93-1423-4efd-8d65-6313b055b1b7" />

Una vez terminada la configuracion del ```hostname```, se solicita la creacion de un usuario, se puede agregar el nombre de usuario al gusto de cada uno.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/27070641-b6c0-4e18-be10-d97f74dfaa65" />

Seguidamente se solicita el ingreso de una contraseña para el usuario recien creado

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/1fcd32f7-7e3b-49f4-9b6b-09a61937f6b1" />

Luego se muestra la configuracion de particiones del disco virtual.

Se selecciona la segunda opcion.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/dfdada26-e823-4edc-b582-db2b937b4f45" />

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/4ae92399-5e25-4584-a235-d9fa5d0a82f4" />

Al avanzar, el sistema presenta opciones para realizar la particion, para nuevos usuarios se recomienda hacer una sola particion, es decir seleccionar la primera opcion 

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/cb5d0a57-cd0c-4867-a16c-bfe10e51b377" />

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/96be86db-f442-4772-a3c9-0ace94b79f76" />

Una vez avanzada la instalacion, se presanta la interfaz para seleccionar el tipo de interfaz a instalar, para este caso se seleccionara GNOME, se puede seleccionar cualquiera, es al gusto de cada uno.

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/8050fac9-cbcd-479d-904e-dbd95b3d7216" />

Una vez terminada la instalacion, aparecera la siguiente interfaz solicitando el reinicio de la maquina

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/2fe521f4-7f7f-4cf7-8173-a9db32763fb1" />

Una vez reinciado el sistema, aparecera la siguiente interfaz, indicando que el sistema operativo se instalo correctamente.

<img width="1918" height="866" alt="image" src="https://github.com/user-attachments/assets/f3f74898-8834-4ee1-84a0-7724f522ad23" />

# Recomendacion

Como previamente se realizo con las dos maquinas ubuntu, se ejecuta el comando ```sudo apt update && sudo apt upgrade -y``` para que se actulicen los repositorios y aplicaciones.

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/1b941fc1-ffda-43cd-87fa-b98822736378" />
