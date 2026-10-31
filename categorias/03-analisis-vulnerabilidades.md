# 03 · Análisis de Vulnerabilidades

Escáneres que identifican vulnerabilidades conocidas, malas configuraciones y exposiciones en hosts, redes y aplicaciones.

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

---

## 🧪 Escáneres de red y host

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Nessus | Escáner de vulnerabilidades comercial de referencia (versión Essentials gratuita). | [Enlace](https://www.tenable.com/products/nessus) | 📚 |
| OpenVAS / Greenbone | Escáner de vulnerabilidades de código abierto. | [Enlace](https://www.greenbone.net) | 📚 |
| Qualys | Plataforma comercial en la nube de gestión de vulnerabilidades. | [Enlace](https://www.qualys.com) | 📚 |
| GFI LanGuard | Escáner de vulnerabilidades y gestión de parches para redes. | [Enlace](https://www.gfi.com/products-and-solutions/network-security-solutions/languard) | 🎯 |
| Nmap NSE (vuln) | Scripts de detección de vulnerabilidades integrados en Nmap. | [Enlace](https://nmap.org/nsedoc/categories/vuln.html) | 📚 |
| Vulners Scanner (nmap-vulners) | Script NSE que correlaciona versiones de servicios con la base de datos de Vulners. | [Enlace](https://github.com/vulnersCom/nmap-vulners) | 🎯 |
| Vulners | Base de datos y motor de búsqueda de vulnerabilidades y exploits. | [Enlace](https://vulners.com) | 📚 |

## 🌐 Escáneres de aplicaciones y servidores web

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Nikto | Escáner de servidores web que detecta configuraciones y archivos peligrosos. | [Enlace](https://github.com/sullo/nikto) | 📚 |
| Wapiti | Escáner de vulnerabilidades de aplicaciones web (caja negra). | [Enlace](https://wapiti-scanner.github.io) | 🎯 |
| Nuclei | Escaneo basado en plantillas YAML, muy extensible y rápido. | [Enlace](https://github.com/projectdiscovery/nuclei) | 📚 |

## 📦 Contenedores e infraestructura

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Trivy | Escaneo de vulnerabilidades en imágenes, repos e infraestructura como código. | [Enlace](https://github.com/aquasecurity/trivy) | 📚 |

## 📱 Móvil

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Vulners Scanner (Android) | App que inventaria el software del dispositivo y busca vulnerabilidades conocidas. | [Enlace](https://vulners.com) | 🎯 |
| SecurityMetrics Mobile | Servicio de análisis de seguridad para dispositivos móviles. | [Enlace](https://www.securitymetrics.com) | 🎯 |

## 🔎 Búsqueda de exploits

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| searchsploit | Búsqueda offline en la base de datos de Exploit-DB. | [Enlace](https://www.exploit-db.com/searchsploit) | 📚 |

---

## 🧾 Comandos rápidos

```bash
# Nuclei sobre una lista de URLs
nuclei -l urls.txt -severity medium,high,critical

# Scripts de vulnerabilidades de Nmap
nmap --script vuln -p 80,443 10.10.10.10

# Buscar exploits por servicio/versión
searchsploit apache 2.4.49
```
