# Configuración pila ELK

Fichero Docker Compose para desplegar la pila ELK. Los componentes están en la versión 9.2.1.

Advertencias:
- La pila ELK utiliza aprox. 5 GB de RAM.
- Logstash utiliza una carpeta "pipeline" con la configuración, que se monta como un bind mount.
- El control de autenticación está deshabilitado para Elasticsearch, para simplificar el despliegue.
