# Proyecto-Fin-de-Curso
Simulación de un entorno informático en un centro de conservación de carreteras.

I Introducción 
1. Agradecimientos. 
2. Objetivos y motivacion. 
2.1. Objetivos del proyecto.
2.2. Motivacion del proyecto.
II Planicacion 
2.3. Fases del Proyecto. 
2.3.1. Seleccion de la idea .
2.3.2. Introducción a las Instalaciónes de tuneles .
2.3.3. Seleccion del Hardware.
2.3.4. Seleccion del Software .
2.3.5. Creación del Armario Rack.
2.3.6. Creación de la maqueta del tunel .
2.3.7. Instalación y conguracion de los elementos del proyecto.
2.3.8. Edicion de Video.
2.3.9. Creación de la memoria.
III Elementos utilizados 
3. Seleccion de Hardware .
3.1. Proteccion y alimentacion electrica.
3.1.1. Proteccion electrica .
3.1.2. Dispositivos de alimentacion electrica a los diferentes dispositivos. 
3.1.3. Gestion de alimentacion y mando -Reles-.
3.2. Redes . 
3.2.1. Routers . 
3.2.2. Switches . 
3.2.3. Dispositivos Inalambricos . 
3.3. Servidores . 
3.3.1. Raspberry pi . 
3.3.2. Ethernet W5100 . 
3.4. Gestion del esquema de mando . 
3.4.1. Arduinos . 
3.5. Pantallas . 
3.5.1. Patalla LCD . 
3.5.2. Patallas matriciales . 
3.6. Camaras . 
3.7. Sensores . 
3.7.1. Sensor de Temperatura y humedad dht 11 . 
3.8. Ventiladores. 
3.9. Iluminacion -Diodos Led-. 
3.10. Cables de Red. 
3.11. Servomotores. 
3.12. Creación de los Videos (Time-Lapse) . 
3.12.1. Camara . 
3.12.2. Equipo para la edicion de video. 
4. Seleccion de Software.
4.1. Redes . 
4.1.1. Router OS . 
4.2. Air OS . 
4.3. tp-link . 
4.4. Servidores (Raspberry Pi OS). 
4.4.1. Instalación de Raspberry Pi OS . 
4.4.2. Descarga de la imagen del sistema. 
4.4.3. Preparacion y volcado del sistema en la tarjeta micro sd. 
4.4.4. El fichero cong.txt (La bios de la placa Raspberry pi). 
4.4.5. Primer inicio del sistema. 
4.4.6. Conguracion de parametros de red, el chero dhcpcd.conf . 
4.4.7. Conguracion de parametros de red en cada uno de los servidores . 
4.5. Clientes . 
4.5.1. Sistema de Virtualizacion usado (Virtual Box) .
4.5.2. Xubuntu . 
4.5.3. Windows . 
4.5.4. Retropie . 
4.6. Camaras (Tunel) . 
IV Creación de la Memoria 
5. LATEX 191
5.1. Que es LATEX . .
5.2. Ejemplo de un documento fuente LATEXy su resultado compilado . 
5.3. Etiquetas basicas de un documento LATEX . 
5.4. Los primeros pasos .
5.4.1. Caracteres especiales . 
5.4.2. Acentos y ñ . 
5.4.3. Estilo y tamaño de los caracteres . 
5.4.4. Algunos comandos utiles . 
5.5. Formateo de Parrafos y Listas . 
5.6. Estructura del Documento . 
5.7. Figuras y tablas . 
5.8. Escribiendo Matematicas con LaTex . 
5.9. Bibliografa y referencias cruzadas . 
5.10. Donde encontrar LaTex y software relacionado . 
6. Instalación de LATEX 211
6.1. Instalación de TexLive . 
6.2. Instalación de TeXstudio . 
V Creación de los Videos (Time-Lapse) 221
7. Time-Lapse 223
7.1. Creación de Imagenes con Inkscape . 
7.2. Creación del Time-Lapse en Kdenlive . 
7.2.1. Primer vdeo (Creación del Rack sobre un tablero) . 
7.2.2. Segundo vdeo (Creación del Tunel primera parte) . 
7.2.3. Tercer vdeo (Creación del Tunel Segunda parte) . 
VI Conguracion de los elementos del proyecto. 239
8. Esquemas. 
8.1. Esquema graco de la distribucion de los elementos en la red del Rack . 
8.2. Esquema graco de la distribucion de los elementos en la red del Tunel. 
9. Conguracion y Programacion de Arduinos 
9.1. Conceptos basicos para programar un Arduino (Microcontrolador) . 
9.1.1. Descarga e Instalación del IDE de Arduino (oficial). .
9.1.2. Conectar la placa Arduino a nuestro PC y congurarla en el IDE de arduino. 
9.1.3. Programando Arduino, Estructura de un Sketch . 
9.1.4. Librerias. 
9.2. Conguracion del modulo de mando del tunel (Arduino Mega). (Servidor
WEB) . 
9.3. Conguracion de los modulos de mando auxiliar del tunel (Arduino Nano) 
9.3.1. Control de intermitencia de semaforos Ambar . 
9.3.2. Control de los servos de las barreras abatibles . 
9.4. Conguracion del modulo de mando del Armario Rack (Arduino Mega)
(Servicio WEB) . 
9.5. Gestion de una pantalla matricial 2*16 y sensor de temperatura . 
9.6. Gestion de una pantalla matricial 2*16 y grupo de pulsadores Modulo (DFRobot)
9.7. Conguracion del modulo de mando del Armario Rack (Arduino Mega)
(Servcio WEB de Ayuda) . 
10.Conguracion de los Routers del proyecto
10.1. Conguracion del Router del Armario Rack . 
10.2. Conguracion del Router del Tunel . 
11.Conguracion de los enlaces Inalambricos .
11.1. Conguracion del Enlace del Armario Rack . 
11.2. Conguracion del Enlace del Tunel . 


11.3. Conguracion del punto de acceso Mikro Tik . 
12.Conguracion del servicio de camara remota en el Tunel 
12.1. Concepto del paquete Motion . 
12.2. Descarga e Instalación de MotionEyesOS. 
13.Conguracion de servicios en el Rack 
13.1. Conguracion del Servidor DNS . 
13.1.1. Instalación de Bind ¿Que es Bind9? . 
13.1.2. Tipos de registros . 
13.1.3. Instalación de Bind9 . 
13.1.4. Instalación de Webmin ¿Que es Webmin? . 
13.1.5. Conguracion de Bind9 mediante Webmin. 
13.1.6. Pruebas de redireccion. 
13.1.7. Nombres DNS y direcciones ip asignadas en el proyecto. 
13.2. Conguracion del Servidor WEB . 
13.2.1. Instalación del servidor Apache y herramientas necesarias. 
13.2.2. Instalación del sistema de gestion de base de datos MariaDB (MySQL).
13.2.3. Instalación del gestor web de bases de datos mysql, phpMyadmin. 
13.2.4. Instalación del lenguaje de programacion PHP . 
13.2.5. Instalación del CMS (WordPress) . 
13.3. Conguracion del Servidor de Almacenamiento masivo de datos (NAS) . 
13.3.1. Conguracion de los parametros de RED . 
13.3.2. Instalación de discos en el sistema. 
13.3.3. Creación del sistema de ficheros. 
13.3.4. Creación de usuarios. 
13.3.5. Creación de un recurso en red SMB/CIFS. 
13.3.6. Creación de recurso compartido FTP . 
13.4. Conguracion del servidor de Ticketing (Servicio de incidencias informaticas)
13.4.1. Instalación del servidor Apache y herramientas necesarias. 
13.4.2. Instalación del lenguaje de programacion PHP . 
13.4.3. Instalación del sistema de gestion de base de datos MariaDB (MySQL).
13.4.4. Instalación del paquete GLPI . 
13.4.5. Creación de usuarios y perles . 
13.4.6. Usuarios . 
13.4.7. Creación de una incidencia. 
13.5. Servidor de correo interno (PostFix). 
13.5.1. Introducción a Postx y Dovecot . 
13.5.2. Instalación y conguracion de Postx. 
13.5.3. Instalación de Dovecot . 
13.5.4. Conguracion del cliente de correo Mozilla Thunderbird. 
13.5.5. Instalación de RoundCube . 
13.6. Servicio de entretenimiento (Retropie) . 
13.6.1. Instalación . 
13.6.2. Administracion de Roms y Bios . 
13.6.3. Ejecucion de una Rom. 
VII Pruebas del sistema y en el sistema. 
14.Pruebas de funcionamiento. 
14.1. Puerta de acceso principal a todos los elementos de la red, puerta de enlace,
y servidor DHCP interno.(Router principal) . 
14.2. Puerta de enlace principal a todos los elementos de la red correspondientes
al tunel (Router secundario) . 
14.3. Servidor de la Gestion web de los componentes administrables del Armario
Rack. 
14.4. Servidor de la Gestion web de los componentes administrables del Tunel. 
14.5. Servidor web de ayuda donde se muestra la conguracion de la zona de
mando a traves de una web en la red. 
14.6. Punto de acceso inalambrico para conexion con el tunel (Antena Ubikiti
NanoStation) . 
14.7. Punto de acceso inalambrico para conexion con el Armario Rack (Antena
Ubikiti PowerStation) . 
14.8. Punto de acceso para usos varios (Antena Mikrotik) . 
14.9. Servidor DNS . 
14.10.servidor Web, pagina interna del centro de conservacion de carreteras. 
14.11.Servidor de almacenamiento masivo en red NAS . 
14.12.Servidor de alojamiento del sistema de ticketing de incidencias informaticas
interno. 
14.13.Servidor de correo interno (Postx) . 
14.14.Servidor de entretenimiento (Retropie) . 
14.15.Servidor streaming de camara de vigilancia en el tunel. 
15.Nmap: Escaner de red y puertos 517
15.1. ¿Que es Nmap? 
15.2. ¿Que es Zenmap? 
15.3. Sintaxis de uso. 
15.4. Algunas opciones mas usadas de Nmap (y Zenmap). 
15.5. Escaneado de todos los servicios del centro de control y tunel. 
Bibliografa / Paginas web consultadas 541.

