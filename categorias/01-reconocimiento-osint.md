# 01 · Reconocimiento y OSINT

Recolección de información **pasiva** (sin interactuar directamente con el objetivo) y semi-pasiva.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| theHarvester | Correos, subdominios, hosts y nombres desde fuentes públicas | [GitHub](https://github.com/laramies/theHarvester) | 📚 |
| Maltego | Análisis gráfico de relaciones entre entidades (personas, dominios, IPs) | [maltego.com](https://www.maltego.com/) | 📚 |
| Recon-ng | Framework modular de reconocimiento web | [GitHub](https://github.com/lanmaster53/recon-ng) | 📚 |
| SpiderFoot | Automatización de OSINT con +200 módulos | [GitHub](https://github.com/smicallef/spiderfoot) | 📚 |
| Amass | Mapeo de superficie de ataque y enumeración de subdominios (OWASP) | [GitHub](https://github.com/owasp-amass/amass) | 📚 |
| Subfinder | Enumeración pasiva de subdominios | [GitHub](https://github.com/projectdiscovery/subfinder) | 📚 |
| Shodan | Buscador de dispositivos y servicios expuestos en Internet | [shodan.io](https://www.shodan.io/) | 📚 |
| Censys | Buscador de hosts y certificados | [censys.io](https://search.censys.io/) | 📚 |
| crt.sh | Búsqueda en logs de Certificate Transparency | [crt.sh](https://crt.sh/) | 📚 |
| Google Dorks / GHDB | Búsquedas avanzadas en Google | [Exploit-DB GHDB](https://www.exploit-db.com/google-hacking-database) | 📚 |
| Wayback Machine | Versiones históricas de sitios web | [archive.org](https://web.archive.org/) | 📚 |
| whois / dig / nslookup | Consultas de registro y DNS | Incluidas en Linux | 📚 |
| DNSDumpster | Mapeo visual de registros DNS | [dnsdumpster.com](https://dnsdumpster.com/) | 📚 |
| Sherlock | Búsqueda de nombres de usuario en redes sociales | [GitHub](https://github.com/sherlock-project/sherlock) | 📚 |
| ExifTool | Lectura de metadatos de archivos | [exiftool.org](https://exiftool.org/) | 📚 |
| OSINT Framework | Directorio de recursos OSINT | [osintframework.com](https://osintframework.com/) | 📚 |

## 🧾 Comandos rápidos

```bash
# Subdominios y correos con theHarvester
theHarvester -d ejemplo.com -b all

# Subdominios pasivos
subfinder -d ejemplo.com -silent

# Registros DNS
dig ejemplo.com ANY +noall +answer
```
