# 🔎 Flujo de trabajo SOC Analyst N1

1. **Revisión de alertas**
   - Entrar a SOC Console → Alerts
   - Verificar fecha, IP origen/destino, regla disparada

2. **Clasificación**
   - ¿Es un falso positivo?
   - ¿Es actividad sospechosa?

3. **Investigación básica**
   - Revisar logs relacionados (Zeek, Wazuh)
   - Correlacionar con PCAP si es necesario

4. **Acciones**
   - Si es falso positivo → cerrar
   - Si es incidente real → documentar y escalar a N2/N3

5. **Documentación**
   - Crear caso en **TheHive**
   - Agregar evidencia (capturas, logs, queries)
