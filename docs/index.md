# Sprint 1

## **Instal·lació SO Ubuntu 24**

#####Aqui posarem el nom, el tipus de SO i la versió que volem.
![captura de pantalla1](./img/2.png)

#####Posem la memòria que creiem necesaria.
![captura de pantalla1](./img/3.png)

#####Podem ampliar la capacitat de la nostra màquina si volem.
![captura de pantalla1](./img/4.png)

#####Una vegada dintre fiquem la ISO de ubuntu desktop 24.
![captura de pantalla1](./img/5.png)

#####Cliquem a instal·lar ubuntu.
![captura de pantalla1](./img/6.png)

#####Seguidament triarem les opcions personals que més ens agradi o s'ajustin a nosaltres.
![captura de pantalla1](./img/7.png)

![captura de pantalla1](./img/8.png)

#####Instal·lem el sistema d'ubuntu.
![captura de pantalla1](./img/9.png)

#####Volem que sigui una instal·lació interactiva.
![captura de pantalla1](./img/10.png)

#####Desisió personal (recomano la predeterminada).
![captura de pantalla1](./img/Captura de pantalla de 2024-09-19 12-38-41.png)

#####Ara per a fer les particions que volem cliquem a alguna altra cosa.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-19 12-56-19.png)

#####Ara creem una nova partició.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-22-32.png)

#####Li donem la memoria que volem tindre perque esta sera una partició swap, que es la particio per a tindre un extra de RAM per a la instalació. 
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-23-26.png)

#####Per a la partició Home li posarem l'espai per les nostres homes o usuaris varia segons el que volem.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-25-46.png)

#####I per acabar amb les particions la root que li donarem la memoria restan.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-25-46.png)

#####Aqui es pot observar com quedara.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-31-25.png)

#####Comprovem que ho tenim tot en ordre.
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 12-33-48.png)

#####I ja tendries la teva màquina d'ubuntu 24 Desktop amb particions fetes!!
![captura de pantalla1](./img/Captura de pantalla de 2024-09-20 13-11-10.png)

## Configuració xarxa

#####per a començar la nostra màquina tindra Xarxa NAT.
![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-19 12-12-25.png)

#####Si activem el DHCP no haurem de canviar res.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-02-04.png)

#####I si volem manual haurem de posar la configuració de xarxa.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-02-13.png)

#####Per a comprobar que s'ha canviat fem ip a i mirem la ip que sigui la correcta.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-11-13.png)

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-11-40.png)

#####I ara per canviar-ho manualment entrarem al netplan.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-10-46.png)

#####El canviarem per a que quedi així.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-09-14.png)

#####Farem un netplan apply per a guardar.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-10-08.png)

#####Farem ping per a comprovar que tot funcioni.

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-11-57.png)

![captura de pantalla de xarxa](./img/Captura de pantalla de 2024-09-24 12-12-13.png)


## Punts de restauració

#####Instal·lem el timeshift
![captura de pantalla de backsave](./img/Captura_de_pantalla_de_2024-09-24_12-21-41.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-23-26.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-24-35.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-25-06.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-26-29.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-26-41.png)
###### Ara que ja tenim el timeshift instal·lat clicarem a fer la instantània al botò de crear.
![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-26-58.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-28-08.png)

![captura de pantalla de backsave](./img/Captura de pantalla de 2024-09-24 12-27-38.png)


## GRUB

##### Mirem que tenim grub
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-18-30.png)
##### Eliminem la grub 
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-18-55.png)
##### Mirem que no tenim grub
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-19-11.png)
##### Anirem a parametres 
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-02 08-30-02.png)
##### En l'apartat de emmagatzematje
![captura de pantalla de grub](./img/Captura de pantalla 
de 2024-10-01 12-12-12.png)
##### Obrim des de una nova ISO 
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-12-53.png)

![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-02 08-31-25.png)
##### Entrem a la màquina 
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-13-21.png)

![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-14-27.png)
##### Iniciarem la reparació recomanada.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-15-13.png)
##### Una vegada reparada ja podriem tancar la maquina i tornar a obrir-la.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-16-01.png)

![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-16-44.png)
##### Obrim la màquina normal 
![captura de pantalla de grub](./img/Captura de pantalla 
de 2024-10-01 12-17-29.png)
##### I al entrar a la carpeta boot podem veure que s'ha creat la grub.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-18-30.png)
##### La tornem a borrar
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-18-55.png)
##### Tornem a posar desde parametres l'altra ISO de recuperació de GRUB.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-24-45.png)
##### Al obrir ens mostrara aquesta pantalla, seleccionarem Arranque manual. 
![captura de pantalla de grub](./img/Captura de pantalla 
de 2024-10-01 12-41-45.png)
##### Anem a Sistemas Operativos
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-41-49.png)
##### Seleccionem Linux 
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-41-55.png)
##### Ara tanquem la maquina i tornem a obrir treient la ISO I deixant l'apartat d'emmagatzematje buit.
![captura de pantalla de grub](./img/Captura de pantalla 
de 2024-10-01 12-12-12.png)
##### Al entrar entrarem al directori boot.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-43-54.png)
##### Posarem les comandes per tornar a instal·lar la GRUB.
![captura de pantalla de grub](./img/Captura de pantalla 
de 2024-10-01 12-44-18.png)
##### Fem una update a la GRUB per acaba de recuperar-la.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-45-02.png)
##### Ara fem un ls i ja la tindrem.
![captura de pantalla de grub](./img/Captura de pantalla de 2024-10-01 12-45-20.png)

## Instalació virtual d'aplicacións

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-05-44.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-07-24.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-08-52.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-09-56.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-10-24.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-11-48.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-13-04.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-13-15.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-36-27.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-38-17.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-40-23.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-41-42.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-44-04.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-46-47.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-50-45.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-51-45.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-10 12-51-45.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 08-52-27.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 09-01-05.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 09-10-14.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 09-48-16.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 10-13-02.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-39-02.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-40-48.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-41-40.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-43-35.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-44-58.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-47-18.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-49-22.png)

![captura de pantalla de instalació](./img/Captura de pantalla de 2024-10-15 11-49-08.png)