# 07 · Redes, Sniffing e Inalámbricas

Análisis de tráfico, ataques de capa 2 (DHCP, ARP, DNS, MAC) y auditoría WiFi **en entornos autorizados**.

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

> 🔒 Captura y analiza únicamente tráfico de redes propias o con autorización escrita.

---

## 📡 Captura y análisis de tráfico (sniffers)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Wireshark | Analizador de protocolos de referencia para inspeccionar tráfico. | [Enlace](https://www.wireshark.org) | 📚 |
| tcpdump | Captura de tráfico por línea de comandos. | [Enlace](https://www.tcpdump.org) | 📚 |
| Colasoft Capsa | Analizador de red con detección de anomalías y diagnóstico. | [Enlace](https://www.colasoft.com/capsa/) | 🎯 |
| Xplico | Herramienta de análisis forense de red que reconstruye sesiones. | [Enlace](https://www.xplico.org) | 🎯 |
| RITA | Analiza logs de red para detectar C2 y *beaconing*. | [Enlace](https://www.activecountermeasures.com/free-tools/rita/) | 🎯 |
| Scapy | Creación y manipulación de paquetes en Python. | [Enlace](https://scapy.net) | 📚 |

## 🧪 Ataques DHCP

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Yersinia | Ataques a protocolos de capa 2 (DHCP starvation, STP, etc.). | [Enlace](https://github.com/tomac/yersinia) | 🎯 |
| DHCPig | Agota el pool de direcciones de un servidor DHCP (DHCP starvation). | [Enlace](https://github.com/kamorin/DHCPig) | 🎯 |
| mitm6 | Abusa de IPv6/DHCPv6 para posicionarse como MITM en redes Windows. | [Enlace](https://github.com/dirkjanm/mitm6) | 📚 |
| Hyenae | Generador de paquetes para pruebas de inundación y spoofing. | [Enlace](https://sourceforge.net/projects/hyenae/) | 🎯 |

## 🎭 Envenenamiento ARP y MITM

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Bettercap | Framework completo de MITM, sniffing y manipulación de tráfico. | [Enlace](https://www.bettercap.org) | 📚 |
| Ettercap | Suite clásica para ataques MITM y ARP poisoning. | [Enlace](https://www.ettercap-project.org) | 📚 |
| dsniff / arpspoof | Conjunto de herramientas de sniffing e interceptación (incluye arpspoof). | [Enlace](https://www.monkey.org/~dugsong/dsniff/) | 📚 |
| Responder | Envenenamiento LLMNR/NBT-NS/mDNS para capturar credenciales. | [Enlace](https://github.com/lgandx/Responder) | 📚 |
| MITMf | Framework de ataques MITM (mantenimiento detenido). | [Enlace](https://github.com/byt3bl33d3r/MITMf) | 🎯 |
| Habu | Utilidades de ataques de red para aprendizaje (ARP, DHCP, etc.). | [Enlace](https://github.com/portantier/habu) | 🎯 |

## 🛡️ Detección de ARP spoofing (defensa)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| ArpON | Demonio que protege contra ARP poisoning. | [Enlace](https://arpon.sourceforge.io) | 🎯 |
| shARP | Detecta y responde a ataques de ARP spoofing. | [Enlace](https://github.com/europa502/shARP) | 🎯 |
| XArp / ARP AntiSpoofer | Detección de envenenamiento ARP en la red local. | *sin enlace oficial confiable* | 🎯 |

## 🪪 Suplantación de MAC

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Technitium MAC Address Changer | Cambia la dirección MAC de los adaptadores en Windows. | [Enlace](https://technitium.com/tmac/) | 🎯 |
| SMAC | Cambiador de direcciones MAC para Windows. | [Enlace](https://www.klcconsulting.net/smac/) | 🎯 |
| macchanger | Cambia la MAC en Linux. | [Enlace](https://github.com/alobbs/macchanger) | 📚 |

## 🌐 Suplantación de DNS

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Evilgrade | Inyecta actualizaciones maliciosas abusando de mecanismos de update. | [Enlace](https://github.com/infobyte/evilgrade) | 🎯 |
| Ettercap (plugin dns_spoof) | Redirige dominios mediante envenenamiento DNS en MITM. | [Enlace](https://www.ettercap-project.org) | 📚 |

## 📶 Inalámbricas (WiFi / Bluetooth)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Aircrack-ng | Suite de auditoría WiFi (captura, inyección y cracking WEP/WPA). | [Enlace](https://www.aircrack-ng.org) | 📚 |
| Kismet | Detector de redes y sniffer inalámbrico. | [Enlace](https://www.kismetwireless.net) | 📚 |
| Wifite2 | Automatiza auditorías WiFi sobre aircrack-ng. | [Enlace](https://github.com/derv82/wifite2) | 🎯 |
| btlejack | Auditoría de Bluetooth Low Energy (BLE). | [Enlace](https://github.com/virtualabs/btlejack) | 🎯 |

## 📱 Sniffing en móvil

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Packet Capture | Captura de tráfico en Android sin root (MITM local). | *app de tienda, sin enlace oficial estable* | 🎯 |
| Sniffer Wicap | Sniffer de red para Android. | *app de tienda, sin enlace oficial estable* | 🎯 |

---

## 🧾 Comandos rápidos

```bash
# Captura filtrando por host
sudo tcpdump -i eth0 host 10.10.10.10 -w captura.pcap

# MITM con bettercap (solo en laboratorio autorizado)
sudo bettercap -iface eth0
```

## 📖 Referencias
- [Documentación de Wireshark](https://www.wireshark.org/docs/)
- [Wiki de Aircrack-ng](https://www.aircrack-ng.org/documentation.html)
