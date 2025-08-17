# 💻 Instalación de Security Onion en una VM

## 🔹 Crear VM
1. Crear nueva VM en VirtualBox/VMware.
2. Asignar recursos:
   - 2 CPU
   - 4 GB RAM
   - 50 GB disco
3. Agregar dos adaptadores de red:
   - NAT (administración)
   - Red interna (monitoreo)

## 🔹 Instalar
1. Montar ISO de Security Onion y arrancar.
2. Seguir asistente de instalación (similar a Ubuntu).
3. Tras reinicio → abrir el **Setup Wizard**.

## 🔹 Configuración básica
- **Mode:** Evaluation / Standalone
- Usuario y contraseña administrador
- Seleccionar interfaces (NAT para administración, interna para monitoreo)
- Aceptar configuración por defecto (incluye Suricata, Zeek, Wazuh, Kibana, etc.)
