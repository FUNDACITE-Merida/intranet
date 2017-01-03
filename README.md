Suite de Intranet
=================

Suite de Intranet es un sistema básico que permite la integración de distintos módulos (aplicaciones) para las tareas comunes de una pequeña o mediana empresa.

> **Importante: El sistema está en desarrollo y no es posible usarlo en producción sin el riesgo de incendiar la empresa, la ciudad y/o el país ;-).**

Suite de Intranet provee la funcionalidad base y común para las aplicaciones que se acoplarán a ella. Las funcionalidades son las siguientes:

- Autenticación, autorización y administración de usuarios.
- Manejo de dependencias organizacionales.


Instalación
-----------
<!--- ### Instalación vía composer

La forma preferida de instalar Suite de Intranet es vía [composer](http://getcomposer.org/download/).

Use los siguientes comandos:

...
php composer.phar create-project FUNDACITE-Merida/yii2-intranet suite-intranet
...
--->

Clone el repositorio:
...
git clone https://github.com/FUNDACITE-Merida/yii2-intranet.git suite-intranet
...

Ingrese al directorio creado y ejecute:
...
php composer.phar install
...

Configuración
-------------

1.- Cree una base de datos y configure los parámetros en common/config/main-local.php
2.- Por línea de comandos ejecute desde el directorio de la aplicación:
    ...
    ./yii migrate
    ...
