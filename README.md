<div align="center">

# Laboratorio de Redes y Seguridad 
### Wireshark • Nmap • Troubleshooting • Hardening • Segmentación
</div>

# Descripción del Proyecto
Este laboratorio práctico está diseñado para demostrar habilidades fundamentales en redes y ciberseguridad, utilizando herramientas ampliamente usadas en entornos profesionales.

El proyecto incluye:
- Captura y análisis de tráfico con Wireshark
- Escaneo y enumeración básica con Nmap
- Troubleshooting de conectividad TCP/IP y DNS
- Validación de puertos y servicios
- Hardening básico de red
- Conceptos de segmentación y buenas prácticas

Este repositorio es ideal para roles como:
- Analista SOC Nivel 1
- Técnico de redes
- Soporte TI
- Ciberseguridad Junior

# Objetivo del Laboratorio
- Comprender cómo fluye el tráfico en una red real
- Identificar protocolos clave (TCP, UDP, DNS, HTTP, ARP, ICMP)
- Detectar problemas de conectividad y resolverlos
- Enumerar puertos y servicios expuestos
- Reconocer configuraciones inseguras
- Aplicar medidas básicas de hardening

# Estructura del Respositorio
```
📦 laboratorio-redes-seguridad
│
├── wireshark/
│   ├── capturas/
│   ├── analisis_http.md
│   ├── analisis_dns.md
│   ├── analisis_tcp_handshake.md
│
├── nmap/
│   ├── escaneo_basico.md
│   ├── escaneo_avanzado.md
│   ├── deteccion_servicios.md
│
├── troubleshooting/
│   ├── conectividad_tcpip.md
│   ├── diagnostico_dns.md
│   ├── diagnostico_rutas.md
│
├── hardening/
│   ├── firewall_basico.md
│   ├── segmentacion_red.md
│   ├── buenas_practicas.md
│
└── README.md
```
# Herramientas Necesarias (Instalación)
A continuación tienes todo lo que debes instalar para ejecutar el laboratorio.

🟦 1. Wireshark
Herramienta para capturar y analizar tráfico de red.

🔗 Descargar:
`https://www.wireshark.org/download.html` (wireshark.org in Bing)

Incluye:
- Filtros de captura
- Filtros de visualización
- Análisis de protocolos
- Exportación de paquetes

🟩 2. Nmap
Escáner de puertos y servicios.

🔗 Descargar:
`https://nmap.org/download.html` (nmap.org in Bing)

Incluye:
- Escaneo básico (`-sS`, `-sT`)
- Detección de servicios (`-sV`)
- Detección de SO (`-O`)
- Scripts NSE (--script vuln)

🟧 3. Máquina virtual o entorno de pruebas (opcional pero recomendado)
Puedes usar:
- VirtualBox
- VMware Workstation Player
- Hyper-V

Sistemas recomendados:
- Ubuntu Server
- Kali Linux
- Windows 10/11

🟨 4. Herramientas de troubleshooting (ya vienen con Windows/Linux)
Windows:
- `ping`
- `tracert`
- `ipconfig`
- `arp -a`
- `route print`
- `nslookup`
- `pathping`

Linux:
- `ping`
- `traceroute`
- `ifconfig / ip a`
- `dig`
- `netstat`
- `ss`

🟥 5. Firewall básico
Puedes usar:
- Firewall de Windows
- UFW (Ubuntu)
- Firewalld (CentOS)

# Casos Prácticos Incluidos
## Wireshark
- Análisis de tráfico HTTP
- Análisis de consultas DNS
- Identificación del handshake TCP
- Detección de retransmisiones y resets

## Nmap
- Descubrimiento de hosts
- Escaneo de puertos
- Enumeración de servicios
- Scripts NSE básicos

## Troubleshooting
- Diagnóstico de conectividad
- Problemas de DNS
- Rutas incorrectas
- ARP y conflictos de IP

## Hardening
- Reglas básicas de firewall
- Segmentación de red
- Buenas prácticas de seguridad

# Tecnologías Utilizadas

| Tecnología  | 	Uso |
| ------------- | ------------- |
| Wireshark | Análisis de tráfico  |
| Nmap | Escaneo de puertos y servicios  |
| Windows/Linux Tools  | Troubleshooting  |
| Firewall (Windows/UFW)  | Hardening  |
| Virtualización  | Laboratorio aislado  |
# Autor
Daniel Fernandez

Proyecto orientado a demostrar habilidades en:
- Redes
- Seguridad básica
- Troubleshooting
- Análisis de tráfico
- Enumeración de servicios
