# Instalacion de SIEM Wazuh en Ubuntu Linux

Una vez instalado la maquina virtual, es hora de instalar el SIEM Wazuh.

 En caso de requerir a la guia oficial de Wazuh: https://documentation.wazuh.com/current/installation-guide/index.html

 Desde la terminal de Ubuntu, se ejecuta el siguiente comando:

 ```curl -sO https://packages.wazuh.com/4.7/wazuh-install.sh```

 En caso de no tener ```curl``` instalado, se instala con el siguiente comando

 ```sudo apt install curl```

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/36d21b27-7960-489f-bd67-aaa52e81d83b" />

 Una vez descargado el archivo ```wazuh-install.sh```, se le otorgan permisos de ejecucion al script de bash mediante el siguiente comando:

 ```chmod +x wazuh-install.sh```

 <img width="1920" height="954" alt="image" src="https://github.com/user-attachments/assets/7c18d983-fe07-414b-9748-626844a84abe" />

Una vez realizado esto, mediante el siguiente comando se realiza la instalacion de wazuh

```sudo ./wazuh-install.sh -a --ignore-check```

- -a instalacion completa
-  --ignore-check ingora que el sistema operativo no sea la version compatible

  Una vez finalizada la instalacion, aperece el siguiente mensaje

  <img width="1009" height="237" alt="vmware_KBWlBqXvBJ" src="https://github.com/user-attachments/assets/1cd7c511-2a51-4b3a-b466-21224bb9ebe8" />

Las credenciales que aparecen deben ser guardas en un lugar seguro, ya que son las que dan acceso al panel de Wazuh.

Para ingresar al panel de Wazuh, en Firefox se coloca lo siguiete

Esto es un ejemplo, se debe colocar la direccion Ip de la maquina
```https://127.0.0.1/```

Aparecera una advertencia, para avanzar se presiona la opcion de ```Advanced``` y luego ```Accept the Risk```

<img width="1918" height="920" alt="image" src="https://github.com/user-attachments/assets/8e5205c0-9ad1-4c1a-834f-31573a812fc1" />

Una vez en el panel de inicio de sesion de Wazuh, se colocan las credenciales que previamente el script de instalacion otorgo.


<img width="1918" height="920" alt="vmware_UVgE99El59" src="https://github.com/user-attachments/assets/9952af6f-0810-4834-a583-49c08f7c683f" />
