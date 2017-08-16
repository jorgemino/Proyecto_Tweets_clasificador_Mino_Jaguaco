# Proyecto_Tweets_clasificador_Mino_Jaguaco
Proyecto clasificador tweets
Integrantes: Jorge Miño
             Sonia Jaguaco
Objetivo proyecto
El proyecto se basa en la recoleccion tweets para procesamiento y limpieza, posterior a esto clasificarlos segun los sentimientos y obetener datos de interes en funcion de su clasficacion.

Resumen del proyecto 
Recolectar tweets para el posterior analisis de sus sentimientos, posterior a la recoleccion filtrar los tweets con expresiones regulares, con los tweets filtrados extraer tweets y ponerles sentimientos a criterio de uno, una vez clasificados crear un train con los tweets y con el script Codigo Phyton clasificador.py y posterior a esto filtrar y obtener resultados.


Herramientas utilizadas:Couchdb, Pycharm, elasticsearch

Para instalar Couchdb ingresar a este link
https://www.digitalocean.com/community/tutorials/how-to-install-couchdb-and-futon-on-ubuntu-14-04

Para instalar Pycharm ingresar a este link
http://ubuntuhandbook.org/index.php/2015/07/install-pycharm-ubuntu-1404/

Elasticsearch
Para instalar elasticsearch seguir el siguiente enlace
https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-elasticsearch-on-ubuntu-16-04

Para instalar river en elasticsearch 
https://github.com/elastic/elasticsearch-river-couchdb

Instalacion pluing head para visualizar elasticsearch
https://mobz.github.io/elasticsearch-head/


Proceso de recoleccion de tweets necesitamos registrarnos como desarrollador en la pagina de twitter y obtener credenciales 
en el archivo de Script/Cosechador Phyton.txt ponemos nuestrar credenciales.
Para ejecutar el script utilizamos el siguiente comando este script nos permite recolectar tweets 
python cosechador_phyton.py localhost tweets 

Creamos una vista en couchdb en el documento Documentacion/Proceso Clasificacion.docx ahi se explica como se crea una vista en couchdb y parte del analisis en elasticsearch y exportacion utilizando curl y river.

Posterior a esto tenemos que clasificar los tweets lo que dentro del script /Script/Codigo Phyton clasificador.py que esta en la 
carpeta del proyecto ejecutamos en pycharm dentro de este script esta explicado que hace cada parte del codigo.

Para el analisis de datos se creo vistas filtrando los sentimientos este documento de explicacion se encuentra en 
/Documentacion/Datos filtrados por sentimientos.docx


                      
