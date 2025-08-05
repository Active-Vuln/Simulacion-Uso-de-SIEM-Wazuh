# Simulacion-Uso-de-SIEM-Wazuh
Este repositorio tiene el proposito de simular una pequeña topologia de red que se compone de un SIEM-Computadora que genera y recibe trafico-Maquina Atacante(Kali linux), la idea es comprender el funcionamiento de SIEM y su importancia en una red.



# La topologia se conforma de la siguiente forma:
<img width="2457" height="502" alt="Topologia drawio" src="https://github.com/user-attachments/assets/bc79d8fd-c8d0-43f0-bb17-7777dad35c9a" />



La primera maquina es un sistema operativo Ubuntu donde se encuentra instalado el SIEM Wazuh, su unico proposito es el de monitorear los eventos de la computadora a su lado la cual tambien es un sistema operativo Ubuntu, como se observa en la imagen se encuentra otra computadora que contiene un Kali linux, la idea es generar eventos sospechosos a la maquina Ubuntu y ver como el SIEM actua al detectar este trafico, de que manera se muestran las alertas y como se deben identificar.

# Todo esto es realizado en un ambiente controlado, el proposito es simular una pequeña red que es monitoreada por SIEM, las maquinas son virtualizadas mediante VMware por tanto ningun tercero es afectado al realizar estas pruebas.
