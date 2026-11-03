# 02 · Escaneo y Enumeración

Descubrimiento de hosts, puertos, servicios y versiones (**escaneo**) y extracción detallada de información de cada servicio: usuarios, recursos compartidos, grupos, etc. (**enumeración**).

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

---

## 🎯 Descubrimiento de hosts y escaneo de puertos

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Nmap | Escáner de puertos y servicios de referencia, con motor de scripts NSE para detección y enumeración. | [Enlace](https://nmap.org) | 📚 |
| Masscan | Escáner de puertos de altísima velocidad, capaz de barrer Internet en minutos. | [Enlace](https://github.com/robertdavidgraham/masscan) | 📚 |
| RustScan | Escáner ultrarrápido que detecta puertos abiertos y los pasa a Nmap automáticamente. | [Enlace](https://github.com/RustScan/RustScan) | 📚 |
| Naabu | Escáner de puertos rápido y confiable escrito en Go. | [Enlace](https://github.com/projectdiscovery/naabu) | 📚 |
| NetScanTools Pro | Suite comercial con decenas de utilidades de red (ping, trace, DNS, whois, escaneo). | [Enlace](https://netscantools.com) | 📚 |
| Angry IP Scanner | Escáner de IPs y puertos multiplataforma, ligero y de código abierto. | [Enlace](https://angryip.org) | 📚 |
| Advanced IP Scanner | Escáner de red para Windows que lista hosts, recursos compartidos y permite control remoto. | [Enlace](https://www.advanced-ip-scanner.com) | 📚 |
| SoftPerfect Network Scanner | Escáner de red con detección de hosts, puertos y recursos compartidos. | [Enlace](https://www.softperfect.com/products/networkscanner/) | 📚 |
| Fing | Escáner de red para móvil y escritorio que identifica dispositivos conectados. | [Enlace](https://www.fing.com) | 📚 |
| IP Scanner | Escáner de red para macOS que mapea los dispositivos de la red local. | [Enlace](https://10base-t.com) | 🎯 |
| Netdiscover | Descubrimiento de hosts por ARP en redes locales. | [Enlace](https://github.com/netdiscover-scanner/netdiscover) | 📚 |
| arp-scan | Escaneo ARP de la red local para encontrar hosts activos. | [Enlace](https://github.com/royhills/arp-scan) | 📚 |

## 🧱 Enumeración NetBIOS / SMB

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| enum4linux-ng | Enumeración de SMB/NetBIOS: usuarios, grupos, recursos compartidos y políticas. | [Enlace](https://github.com/cddmp/enum4linux-ng) | 📚 |
| smbmap | Enumera y mapea permisos sobre recursos compartidos SMB. | [Enlace](https://github.com/ShawnDEvans/smbmap) | 📚 |
| NetBIOS Enumerator | Enumera nombres NetBIOS y recursos compartidos en redes Windows. | *sin enlace oficial confiable* | 🎯 |
| Global Network Inventory | Auditoría e inventario de equipos en red (hardware/software). | *sin enlace oficial confiable* | 🎯 |
| Hyena | Herramienta de administración y enumeración de usuarios, grupos y equipos Windows/AD. | [Enlace](https://systemtools.com/hyena/) | 🎯 |
| Nsauditor Network Security Auditor | Auditoría de red que enumera servicios, puertos y debilidades. | [Enlace](https://www.nsauditor.com/network_security) | 🎯 |
| PsTools (Sysinternals) | Suite de utilidades de línea de comandos para administrar y enumerar sistemas Windows. | [Enlace](https://learn.microsoft.com/sysinternals/downloads/pstools) | 📚 |
| net view | Comando nativo de Windows para listar equipos y recursos compartidos del dominio. | [Enlace](https://learn.microsoft.com/windows-server/administration/windows-commands/net-view) | 📚 |

## 📡 Enumeración SNMP

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| snmp-check | Enumera información de dispositivos vía SNMP de forma legible. | [Enlace](https://gitlab.com/kalilinux/packages/snmpcheck) | 📚 |
| onesixtyone | Fuerza bruta de *community strings* SNMP. | [Enlace](https://github.com/trailofbits/onesixtyone) | 📚 |
| OpUtils | Conjunto de herramientas de red de ManageEngine (IP, switch port, SNMP). | [Enlace](https://www.manageengine.com/products/oputils/) | 🎯 |
| SolarWinds Network Performance Monitor | Monitoreo de red que usa SNMP para descubrir y vigilar dispositivos. | [Enlace](https://www.solarwinds.com/network-performance-monitor) | 🎯 |
| SoftPerfect Network Scanner | También enumera SNMP y recursos de los hosts descubiertos. | [Enlace](https://www.softperfect.com/products/networkscanner/) | 🎯 |

## 🗂️ Enumeración LDAP / Active Directory

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Softerra LDAP Administrator/Browser | Cliente para explorar y enumerar directorios LDAP/AD. | [Enlace](https://www.ldapadministrator.com) | 🎯 |
| Nmap `ldap-brute` (NSE) | Script de Nmap para fuerza bruta y enumeración de cuentas LDAP. | [Enlace](https://nmap.org/nsedoc/scripts/ldap-brute.html) | 📚 |
| AD Explorer (Sysinternals) | Visor avanzado de Active Directory para navegar objetos y atributos. | [Enlace](https://learn.microsoft.com/sysinternals/downloads/adexplorer) | 📚 |

## 🕒 Enumeración NTP

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| PRTG Network Monitor | Monitoreo de red que incluye sensores NTP y de servicios. | [Enlace](https://www.paessler.com/prtg) | 🎯 |
| Wireshark | Analiza tráfico NTP para identificar servidores y clientes. | [Enlace](https://www.wireshark.org) | 📚 |
| Nmap (scripts NTP) | Scripts NSE `ntp-info` / `ntp-monlist` para enumerar servidores NTP. | [Enlace](https://nmap.org/nsedoc/scripts/) | 📚 |

## 📁 Enumeración NFS / RPC

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| SuperEnum | Script que automatiza la enumeración de múltiples servicios (incluido NFS). | [Enlace](https://github.com/p4pentest/SuperEnum) | 🎯 |
| RPCScan | Enumera servicios RPC/portmapper de un objetivo. | [Enlace](https://github.com/loveshell/RPCSCAN) | 🎯 |
| NetScanTools | Incluye utilidades para consultar servicios RPC. | [Enlace](https://netscantools.com) | 🎯 |

## ✉️ Enumeración SMTP

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| smtp-user-enum | Enumera usuarios válidos de un servidor SMTP (VRFY/EXPN/RCPT). | [Enlace](https://github.com/pentestmonkey/smtp-user-enum) | 📚 |
| Nmap (scripts SMTP) | Scripts NSE para enumerar comandos y usuarios SMTP. | [Enlace](https://nmap.org/nsedoc/scripts/) | 📚 |
| Metasploit | Módulos auxiliares para enumeración SMTP. | [Enlace](https://www.metasploit.com) | 📚 |

## 🌐 Enumeración DNS

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| DNSRecon | Enumeración de registros, transferencias de zona y búsqueda inversa de DNS. | [Enlace](https://github.com/darkoperator/dnsrecon) | 📚 |
| Knockpy | Enumeración de subdominios por diccionario. | [Enlace](https://github.com/guelfoweb/knock) | 📚 |
| Subfinder | Enumeración pasiva de subdominios. | [Enlace](https://github.com/projectdiscovery/subfinder) | 📚 |
| Raccoon | Reconocimiento que incluye enumeración DNS y de subdominios. | [Enlace](https://github.com/evyatarmeged/Raccoon) | 🎯 |

## 🔐 Otros servicios (IPsec, VoIP, Telnet, FTP, usuarios Unix, IPv6)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| ike-scan | Descubre y enumera gateways VPN IPsec/IKE. | [Enlace](https://github.com/royhills/ike-scan) | 🎯 |
| SIPVicious (svmap) | Suite para auditar y enumerar servicios VoIP/SIP. | [Enlace](https://github.com/EnableSecurity/sipvicious) | 🎯 |
| rusers / rwho / finger | Comandos Unix para enumerar usuarios y sesiones en servicios r* y finger. | [Enlace](https://linux.die.net/man/1/finger) | 🎯 |
| PortQry | Utilidad de Microsoft para consultar puertos y servicios (útil en FTP/RPC). | [Enlace](https://www.microsoft.com/download/details.aspx?id=24009) | 🎯 |
| Enyx | Obtiene direcciones IPv6 de un host vía SNMP. | [Enlace](https://github.com/trickster0/Enyx) | 🎯 |
| IPv6 Hackit | Herramienta de escaneo y enumeración sobre IPv6. | *sin enlace oficial confiable* | 🎯 |

## 🛡️ Detección y prevención de escaneos (defensa)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| ExtraHop | Análisis de tráfico de red (NDR) que detecta escaneos y comportamiento anómalo. | [Enlace](https://www.extrahop.com) | 🎯 |
| Splunk | Plataforma SIEM que correlaciona logs para detectar escaneos y ataques. | [Enlace](https://www.splunk.com) | 📚 |

---

## 🧾 Comandos rápidos

```bash
# Escaneo completo de puertos TCP
nmap -p- --min-rate 5000 -n -Pn 10.10.10.10 -oN allports.txt

# Versiones y scripts por defecto sobre puertos encontrados
nmap -sC -sV -p 22,80,445 10.10.10.10 -oN servicios.txt

# Enumeración SMB
enum4linux-ng -A 10.10.10.10
```
