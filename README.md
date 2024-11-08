# ELK
codigo para usar ELK en Laravel usando docker

- el archivo nginx se usa para aceder a Kibana por el puerto 80 usando proxy inverso

- docker-compose cliente tiene la instalación filebeat que se instala en cliente
    este se encarga de hacer un instalación de filebeat desde la raiz del proyecto cliente

- docker-compose servidor tiene la instalación que debe estar en el servidor
    este tiene la instalación de servidor nginx, elasticsearch, logstash y kibana

- la carpetas de logstash tienen el archivo de configuración necesario para ejecutar logsrash en el servidor

- y la carpeta de filebeat tiene el archivo que contiene la configuraración de la instación
del cliente con los parametros de entrada y de salida.


el codigo de elasticseatch fue sacado de: 

https://medium.com/@mehraien.arash/laravel-log-management-using-filebeat-elk-elastic-search-logstash-and-kibana-be7db5985bd6

