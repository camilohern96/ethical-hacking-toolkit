# 02 · Escaneo y Enumeración

Descubrimiento de hosts, puertos, servicios y versiones.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| Nmap | El escáner de puertos y servicios de referencia (+ scripts NSE) | [nmap.org](https://nmap.org/) | 📚 |
| Masscan | Escaneo de puertos a muy alta velocidad | [GitHub](https://github.com/robertdavidgraham/masscan) | 📚 |
| RustScan | Escaneo rápido que delega en Nmap | [GitHub](https://github.com/RustScan/RustScan) | 📚 |
| Naabu | Escáner de puertos rápido (ProjectDiscovery) | [GitHub](https://github.com/projectdiscovery/naabu) | 📚 |
| Netdiscover | Descubrimiento de hosts por ARP en redes locales | Kali | 📚 |
| arp-scan | Escaneo ARP de la red local | [GitHub](https://github.com/royhills/arp-scan) | 📚 |
| enum4linux-ng | Enumeración SMB / NetBIOS / usuarios en Windows y Samba | [GitHub](https://github.com/cddmp/enum4linux-ng) | 📚 |
| smbclient / smbmap | Acceso y mapeo de recursos compartidos SMB | Kali / [GitHub](https://github.com/ShawnDEvans/smbmap) | 📚 |
| snmpwalk / onesixtyone | Enumeración de SNMP | Kali | 📚 |
| httpx | Sondeo de servicios HTTP (títulos, tecnologías, códigos) | [GitHub](https://github.com/projectdiscovery/httpx) | 📚 |
| WhatWeb | Identificación de tecnologías web | [GitHub](https://github.com/urbanadventurer/WhatWeb) | 📚 |
| Wappalyzer | Detección de tecnologías (extensión de navegador) | [wappalyzer.com](https://www.wappalyzer.com/) | 📚 |

## 🧾 Comandos rápidos

```bash
# Escaneo completo de puertos TCP
nmap -p- --min-rate 5000 -n -Pn 10.10.10.10 -oN allports.txt

# Versiones y scripts por defecto sobre puertos encontrados
nmap -sC -sV -p 22,80,445 10.10.10.10 -oN servicios.txt

# Descubrimiento de hosts en la red local
sudo arp-scan --localnet
```
