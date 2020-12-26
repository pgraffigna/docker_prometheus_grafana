# docker_prometheus_grafana

Docker-compose para desplegar un servidor Prometheus + instalación de node-exporter + instalación de grafana para visualizar las métricas.

Testeado con Vagrant + Ubuntu Server 18.04.

---
- crear carpeta /root/prometheus y copiar el archivo prometheus.yml
- crear carpeta /root/grafana y cambiar permisos a 472:472
- grafana dashboard id 11074 