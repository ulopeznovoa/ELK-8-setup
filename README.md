# Configuración pila ELK

Fichero Docker Compose para desplegar la pila ELK. Los componentes están en la versión 8.11.1.

Advertencias:
- La pila ELK utiliza aprox. 5 GB de RAM.
- Logstash requiere que existe una carpeta "pipeline" con la configuración. Esta se monta como un bind mount.
- El control de autenticación está deshabilitado para Elasticsearch. 
