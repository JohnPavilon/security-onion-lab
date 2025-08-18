# 📋 Requisitos para el laboratorio de Security Onion

Antes de empezar debemos comprobar que nuestro equipo debe cumplir con al menos los requerimientos mínimos para
evitar experimentar problemas durante la ejecución de nuestras pruebas, dado que vamos a necesitar abrir más de una
máquina virtual para realizar prácticas más elaboradas siempre es recomendable ajustar y aumentar nuestros recursos dependiendo de nuestras necesidades.

Security Onion tiene diversas opciones para su instalación catalogados como Node Types y cada una cumple una función, a continuación te enlistaré algunos de ellos:

## ⛏️⌬ Node Types

 🔹 Import: Hace uso de lo mínimo requerido para importar y visualizar archivos PCAP o EVTX
 Hardware mínimo recomendado
- 2 CPU
- 4 GB RAM
- 50 GB disco

🔹 Eval: Ejecuta los procesos mínimos requeridos para que una sola máquina capte el trafico de red desde un puerto TAP o SPAN
 y visualizar los resultados
 Hardware mínimo recomendado
- 4 CPU
- 8 GB RAM
- 200 GB disco

🔹 Standalone: Guarda registros de almacenamiento de si mismo y de nodos adyacentes. También puede actuar como destino de registros de sistema para demás fuentes registradas en Elasticsearch
 Hardware mínimo recomendado
- 4 CPU
- 16 GB RAM
- 200 GB disco

Para más información consultar [El siguiente enlace](https://docs.securityonion.net/en/2.4/hardware.html#hardware)

## 🔹 Software necesario
- VirtualBox o VMware Workstation/Player
- ISO de Security Onion: [Descargar aquí](https://securityonion.net/downloads)

## 🔹 Red
- **Adaptador 1 (NAT):** acceso a Internet
- **Adaptador 2 (Red interna):** monitoreo de tráfico entre máquinas del lab
