# 03 · Análisis de Vulnerabilidades

Escáneres que identifican vulnerabilidades conocidas y malas configuraciones.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| Nessus | Escáner de vulnerabilidades comercial (versión Essentials gratuita) | [tenable.com](https://www.tenable.com/products/nessus) | 📚 |
| OpenVAS / Greenbone | Escáner de vulnerabilidades open source | [greenbone.net](https://www.greenbone.net/) | 📚 |
| Nuclei | Escaneo basado en plantillas YAML, muy extensible | [GitHub](https://github.com/projectdiscovery/nuclei) | 📚 |
| Nikto | Escáner de servidores web | [GitHub](https://github.com/sullo/nikto) | 📚 |
| Nmap NSE (vuln) | Scripts de detección de vulnerabilidades en Nmap | [nmap.org/nsedoc](https://nmap.org/nsedoc/) | 📚 |
| Qualys | Plataforma comercial de gestión de vulnerabilidades | [qualys.com](https://www.qualys.com/) | 📚 |
| Trivy | Escaneo de vulnerabilidades en imágenes, repos e IaC | [GitHub](https://github.com/aquasecurity/trivy) | 📚 |
| searchsploit | Búsqueda offline en Exploit-DB | [Exploit-DB](https://www.exploit-db.com/searchsploit) | 📚 |

## 🧾 Comandos rápidos

```bash
# Nuclei sobre una lista de URLs
nuclei -l urls.txt -severity medium,high,critical

# Scripts de vulnerabilidades de Nmap
nmap --script vuln -p 80,443 10.10.10.10

# Buscar exploits por servicio/versión
searchsploit apache 2.4.49
```
