# 🚨 Generar tráfico sospechoso para pruebas

## 🔹 Ejemplo 1: IDS test
Desde otra VM (Windows/Linux):
```bash
curl http://testmyids.com
```

## 🔹 Ejemplo 2: Escaneo de puertos
Desde Kali Linux:
```bash
nmap -sS <IP_Víctima>
```

## 🔹 Ejemplo 3: Ping sospechoso
```bash
ping 8.8.8.8
```

## Podemos irnos a Security Onion → SOC Console → “Alerts” para visualizar como se registran estos eventos.
