# 🛡️ Security Onion Lab – Mini SOC en VM

Este repositorio documenta la instalación y configuración de **Security Onion**, una distribución basada en Ubuntu diseñada para monitoreo, detección y respuesta a incidentes.  
El objetivo es demostrar habilidades como **analista SOC N1**, desde la instalación hasta la investigación de alertas.

## 🔹 Objetivos
- Instalar Security Onion en VirtualBox/VMware.
- Configurar interfaces de administración y monitoreo.
- Generar tráfico sospechoso (Nmap, testmyids, Metasploitable).
- Analizar y clasificar alertas en el SOC.
- Documentar el flujo de trabajo de un analista SOC N1.

## 🔹 Stack incluido
Security Onion integra múltiples herramientas de seguridad:
- **Suricata** (IDS/IPS)
- **Zeek** (Network Security Monitoring)
- **Wazuh** (Host-based IDS)
- **Elastic + Kibana** (Visualización de logs)
- **TheHive** (Gestión de casos/incidentes)
- **Fleet/Osquery** (Monitoreo de endpoints)

## 🔹 Screenshots
📸 Capturas de ejemplo (instalación, dashboards, alertas) en `/screenshots`.

## 🔹 Cómo reproducir
1. Clona este repositorio.
2. Sigue los pasos en `/setup/`.
3. Lanza tráfico sospechoso siguiendo `/usage/generar_alertas.md`.
4. Investiga y documenta resultados.

## 🔹 Autor
👤 [Jonathan Josué Valencia Cruz] – Aspirante a Analista SOC N1 
