# 01 · Reconocimiento y OSINT (Footprinting)

Recolección de información **pasiva** y semi-pasiva sobre un objetivo: dominios, subdominios, personas, correos, infraestructura, metadatos y presencia pública. Es la primera fase de una auditoría y la que define la superficie de ataque.

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

---

## 🔎 Búsqueda avanzada y Google Hacking

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Google Hacking Database (Exploit-DB) | Repositorio de *dorks* (operadores de búsqueda avanzada) para encontrar archivos, paneles y datos expuestos indexados por Google. | [Enlace](https://www.exploit-db.com/google-hacking-database) | 📚 |
| Búsqueda avanzada de Google | Formulario oficial de Google para filtrar resultados por sitio, tipo de archivo, fecha, idioma, etc. | [Enlace](https://www.google.com/advanced_search) | 📚 |

## 🕵️ Metabuscadores (orientados a privacidad)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Startpage | Metabuscador que entrega resultados de Google sin rastrear al usuario; útil para recon anónimo. | [Enlace](https://www.startpage.com) | 📚 |
| MetaGer | Metabuscador alemán de código abierto que combina varias fuentes y preserva la privacidad. | [Enlace](https://metager.org) | 📚 |
| eTools.ch | Metabuscador suizo que agrega resultados de múltiples motores y muestra de cuál proviene cada uno. | [Enlace](https://www.etools.ch) | 📚 |

## 📂 Buscadores de archivos y FTP públicos

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| NAPALM FTP Indexer | Motor que indexa servidores FTP públicos y permite buscar archivos expuestos en ellos. | [Enlace](https://www.searchftps.net) | 📚 |
| Globalfilesearch / FTP File Search | Buscador de archivos alojados en servidores FTP abiertos de todo el mundo. | [Enlace](https://globalfilesearch.com) | 📚 |
| FreewareWeb FTP Search | Buscador de archivos en repositorios FTP públicos. | *sin enlace oficial confiable* | 🎯 |

## 🌐 Buscadores de dispositivos e IoT

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Shodan | Buscador de dispositivos conectados a Internet (cámaras, servidores, ICS/SCADA, IoT) y sus servicios y banners. | [Enlace](https://www.shodan.io) | 📚 |
| Censys | Motor que escanea Internet continuamente para mapear hosts, puertos, certificados y la superficie de ataque. | [Enlace](https://search.censys.io) | 📚 |
| Thingful | Buscador geográfico de dispositivos IoT públicos (sensores de clima, energía, salud, transporte). | [Enlace](https://www.thingful.net) | 📚 |

## 🧬 Metadatos (archivos, imágenes y video)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| ExifTool | Lee y edita metadatos EXIF/IPTC/XMP de imágenes y documentos (autor, GPS, software, fechas). | [Enlace](https://exiftool.org) | 📚 |
| Metagoofil | Extrae metadatos de documentos públicos (pdf, docx, xlsx) de un dominio para perfilar usuarios y software. | [Enlace](https://github.com/laramies/metagoofil) | 📚 |
| Web Data Extractor | Extrae correos, teléfonos y metadatos de sitios web de forma masiva. | [Enlace](https://www.webextractor.com) | 📚 |
| YouTube Metadata | Extrae metadatos de un video de YouTube (fecha exacta de subida, miniaturas, geolocalización). | [Enlace](https://mattw.io/youtube-metadata/) | 📚 |
| YouTube DataViewer (Amnesty) | Verificación de videos: fecha real de subida e imágenes de miniatura para búsqueda inversa. | *puede estar fuera de servicio* | 🎯 |
| EZGif | Convierte y descompone videos/GIF en fotogramas para análisis forense visual. | [Enlace](https://ezgif.com) | 📚 |
| VideoReverser.com | Invierte o manipula video en línea como apoyo al análisis de contenido. | [Enlace](https://www.videoreverser.com) | 🎯 |

## 🌍 Subdominios, DNS y certificados

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Amass (OWASP) | Mapeo de superficie de ataque: enumeración de subdominios y activos externos por fuentes pasivas y activas. | [Enlace](https://github.com/owasp-amass/amass) | 📚 |
| subfinder | Enumeración pasiva y rápida de subdominios a partir de múltiples fuentes públicas. | [Enlace](https://github.com/projectdiscovery/subfinder) | 📚 |
| Sublist3r | Enumera subdominios usando buscadores y motores públicos. | [Enlace](https://github.com/aboul3la/Sublist3r) | 📚 |
| Knockpy | Enumera subdominios por diccionario sobre un dominio objetivo. | [Enlace](https://github.com/guelfoweb/knock) | 📚 |
| CTFR | Descubre subdominios abusando de los logs de Certificate Transparency (sin fuerza bruta). | [Enlace](https://github.com/UnaPibaGeek/ctfr) | 📚 |
| crt.sh | Búsqueda web en los registros de Certificate Transparency para hallar dominios y subdominios. | [Enlace](https://crt.sh) | 📚 |
| crt.sh CLI | Consulta crt.sh desde la terminal para automatizar el descubrimiento. | [Enlace](https://github.com/az7rb/crt.sh) | 🎯 |
| DNSdumpster | Herramienta web gratuita que descubre hosts y genera un mapa de la infraestructura DNS. | [Enlace](https://dnsdumpster.com) | 📚 |
| dnsx | Toolkit de DNS rápido y multipropósito (resolución masiva, filtrado de comodines). | [Enlace](https://github.com/projectdiscovery/dnsx) | 📚 |
| DNSRecon | Enumeración de DNS: registros, transferencias de zona y búsqueda inversa. | [Enlace](https://github.com/darkoperator/dnsrecon) | 📚 |
| SecurityTrails | Plataforma con histórico de DNS/WHOIS y datos de infraestructura para investigación. | [Enlace](https://securitytrails.com) | 📚 |
| katana | Crawler/spider de nueva generación para descubrir endpoints y URLs. | [Enlace](https://github.com/projectdiscovery/katana) | 📚 |
| Spoofy | Comprueba si un dominio es suplantable según sus registros SPF y DMARC. | [Enlace](https://github.com/MattKeeley/Spoofy) | 🎯 |
| Netcraft | Perfila la tecnología, el hosting y el historial de un sitio y su dominio. | [Enlace](https://www.netcraft.com) | 📚 |

## 🧭 Whois, IP y geolocalización

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| DomainTools Whois | Consulta WHOIS con histórico de propiedad y registros de dominios. | [Enlace](https://whois.domaintools.com) | 📚 |
| SmartWhois (TamoSoft) | Cliente WHOIS de escritorio que obtiene datos de dominios, IPs y redes. | [Enlace](https://www.tamos.com/products/smartwhois/) | 📚 |
| IPinfo | API y web con datos precisos de IP: geolocalización, ASN, operador, tipo de red. | [Enlace](https://ipinfo.io) | 📚 |
| IP2Location | Base de datos y servicio de geolocalización de direcciones IP. | [Enlace](https://www.ip2location.com) | 📚 |
| IP Location Finder (KeyCDN) | Geolocaliza una IP o dominio desde el navegador. | [Enlace](https://tools.keycdn.com/geo) | 📚 |
| Active Whois | Cliente WHOIS de escritorio para consultar dominios e IPs. | *sin enlace oficial confiable* | 🎯 |
| Batch IP Converter | Convierte y consulta lotes de IPs/dominios (whois, ping, trace). | *sin enlace oficial confiable* | 🎯 |
| WhoIs Analyzer Pro | Cliente WHOIS con reportes detallados. | *sin enlace oficial confiable* | 🎯 |

## 🛰️ Rutas de red, ASN y perímetro

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| ARIN | Registro regional de Internet para Norteamérica: consulta rangos de red y asignaciones. | [Enlace](https://www.arin.net) | 📚 |
| ASNLookup | Consulta información de ASN, organizaciones y rangos IP (IPv4/IPv6). | [Enlace](https://asnlookup.com) | 📚 |
| ASNmap | CLI/biblioteca para mapear rangos de red de una organización a partir de su ASN. | [Enlace](https://github.com/projectdiscovery/asnmap) | 🎯 |
| VisualRoute | Traceroute visual que muestra la ruta y geolocalización de cada salto. | [Enlace](https://www.visualroute.com) | 📚 |
| Path Analyzer Pro | Traceroute avanzado con análisis de rutas (descontinuada). | *descontinuada* | 🎯 |
| Hardenize | Monitoreo del perímetro: TLS, DNS, cabeceras de seguridad y correo de un dominio. | [Enlace](https://www.hardenize.com) | 🎯 |
| IPinfo (ver arriba) | También útil para mapear ASN y rangos de una organización. | [Enlace](https://ipinfo.io) | 📚 |

## 👤 Búsqueda de personas y correos

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| theHarvester | Recolecta correos, subdominios, hosts y nombres desde fuentes públicas (buscadores, PGP, etc.). | [Enlace](https://github.com/laramies/theHarvester) | 📚 |
| Sherlock | Busca un nombre de usuario en cientos de redes sociales y sitios. | [Enlace](https://github.com/sherlock-project/sherlock) | 📚 |
| Spokeo | Buscador de personas que agrega perfiles, teléfonos y direcciones de fuentes públicas (EE. UU.). | [Enlace](https://www.spokeo.com) | 📚 |
| RocketReach | Encuentra correos y perfiles profesionales (LinkedIn y otros) de personas y empresas. | [Enlace](https://rocketreach.co) | 📚 |
| Infoga | Recopila información de cuentas de correo desde distintas fuentes públicas. | [Enlace](https://github.com/m4ll0k/Infoga) | 🎯 |
| eMailTrackerPro | Analiza cabeceras de correo para rastrear origen (herencia, posiblemente fuera de servicio). | *sin enlace oficial confiable* | 🎯 |

## 📣 Redes sociales e inteligencia de audiencias

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Social Searcher | Busca y analiza menciones y contenido público en redes sociales en tiempo real. | [Enlace](https://www.social-searcher.com) | 📚 |
| BuzzSumo | Analiza qué contenido y perfiles tienen más alcance en redes sobre un tema o marca. | [Enlace](https://buzzsumo.com) | 📚 |
| Followerwonk | Analiza seguidores y biografías de Twitter/X para perfilar audiencias. | [Enlace](https://followerwonk.com) | 🎯 |
| Mention | Monitorea menciones de una marca o persona en web y redes sociales. | [Enlace](https://mention.com) | 🎯 |
| Gephi | Software de visualización y análisis de grafos y redes (relaciones entre entidades). | [Enlace](https://gephi.org) | 📚 |

## 🏢 Inteligencia competitiva y de empresas

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| OpenCorporates | Mayor base abierta de datos de empresas: registros, directivos y jurisdicciones. | [Enlace](https://opencorporates.com) | 📚 |
| MarketWatch | Noticias y datos financieros útiles para inteligencia competitiva. | [Enlace](https://www.marketwatch.com) | 🎯 |
| The Wall Street Transcript | Transcripciones y entrevistas corporativas para inteligencia estratégica. | [Enlace](https://www.twst.com) | 🎯 |
| Euromonitor | Investigación de mercados e inteligencia estratégica de industrias. | [Enlace](https://www.euromonitor.com) | 🎯 |
| Experian | Datos crediticios y de negocio sobre empresas y personas. | [Enlace](https://www.experian.com) | 🎯 |

## 🌐 Reconocimiento de sitios web (spiders, copiadoras y monitoreo)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Burp Suite | Proxy de intercepción y suite de pruebas web; en recon sirve para mapear el sitio (spider/crawl). | [Enlace](https://portswigger.net/burp) | 📚 |
| HTTrack Website Copier | Descarga un sitio web completo para analizarlo sin conexión. | [Enlace](https://www.httrack.com) | 📚 |
| Cyotek WebCopy | Copia sitios web localmente para su inspección offline. | [Enlace](https://www.cyotek.com/cyotek-webcopy) | 📚 |
| Wayback Machine (Archive.org) | Muestra versiones históricas de páginas y archivos ya eliminados. | [Enlace](https://web.archive.org) | 📚 |
| Photon | Crawler rápido que extrae URLs, correos y datos (incluye versiones de archive.org). | [Enlace](https://github.com/s0md3v/Photon) | 📚 |
| Octoparse | Extracción visual de datos (scraping) sin programar. | [Enlace](https://www.octoparse.com) | 🎯 |
| Netpeak Spider | Crawler SEO que audita y extrae URLs y estructura de un sitio. | [Enlace](https://netpeaksoftware.com/spider) | 🎯 |
| CeWL | Genera diccionarios de palabras a partir del contenido de un sitio objetivo. | [Enlace](https://github.com/digininja/CeWL) | 📚 |
| WebSite-Watcher | Detecta cambios y actualizaciones en páginas web monitoreadas. | [Enlace](https://www.aignes.com) | 🎯 |
| Visual Ping | Monitorea cambios en una página web y avisa cuando se actualiza. | [Enlace](https://visualping.io) | 🎯 |
| Follow That Page | Servicio que notifica cuando una página cambia. | [Enlace](https://www.followthatpage.com) | 🎯 |
| Web-Stat | Analítica de tráfico web en tiempo real (visitantes y ubicación). | [Enlace](https://www.web-stat.com) | 🎯 |
| Clicky | Analítica web en tiempo real de visitas y páginas vistas. | [Enlace](https://clicky.com) | 🎯 |
| Opentracker | Analítica de visitantes y comportamiento en sitios web. | [Enlace](https://www.opentracker.net) | 🎯 |
| Rank Tracker | Herramienta SEO para seguimiento de posiciones y análisis de sitios. | [Enlace](https://www.link-assistant.com/rank-tracker/) | 🎯 |

## 🧰 Frameworks y suites de footprinting / OSINT

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Maltego | Plataforma gráfica para mapear relaciones entre personas, dominios, IPs, correos y más. | [Enlace](https://www.maltego.com) | 📚 |
| Recon-ng | Framework modular de reconocimiento web estilo Metasploit. | [Enlace](https://github.com/lanmaster53/recon-ng) | 📚 |
| OSINT Framework | Directorio web que organiza cientos de recursos OSINT por categoría. | [Enlace](https://osintframework.com) | 📚 |
| FOCA | Analiza metadatos de documentos públicos para perfilar la infraestructura de una organización. | [Enlace](https://github.com/ElevenPaths/FOCA) | 📚 |
| OSRFramework | Conjunto de utilidades OSINT (usuarios, dominios, correos, fugas). | [Enlace](https://github.com/i3visio/osrframework) | 🎯 |
| Recon-Dog | Herramienta todo-en-uno que consulta múltiples APIs de recon. | [Enlace](https://github.com/s0md3v/ReconDog) | 🎯 |
| BillCipher | Recoge información de un sitio web o dirección IP desde varias fuentes. | [Enlace](https://github.com/GitHackTools/BillCipher) | 🎯 |
| GRecon | Automatiza búsquedas de recon (Google/Bing dorks) sobre un objetivo. | [Enlace](https://github.com/TebbaaX/GRecon) | 🎯 |
| Th3Inspector | Herramienta todo-en-uno para información de sitios, correos, teléfonos y tarjetas. | [Enlace](https://github.com/Moham3dRiahi/Th3inspector) | 🎯 |
| Raccoon | Herramienta de reconocimiento y escaneo de vulnerabilidades para recon ofensivo. | [Enlace](https://github.com/evyatarmeged/Raccoon) | 🎯 |
| reconFTW | Automatiza todo el flujo de reconocimiento (subdominios, hosts, vulnerabilidades). | [Enlace](https://github.com/six2dez/reconftw) | 🎯 |
| Jackdaw | Recolecta información de un dominio AD y la grafica para analizar rutas de ataque. | [Enlace](https://github.com/skelsec/jackdaw) | 🎯 |
| Pentest-Tools | Suite web con escáneres y utilidades de recon (subdominios, puertos, etc.). | [Enlace](https://pentest-tools.com) | 📚 |
| BashScan | Escáner de puertos en Bash puro (`/dev/tcp`) para sistemas sin nmap. | [Enlace](https://github.com/astryzia/BashScan) | 🎯 |
| naabu | Escáner de puertos rápido y confiable escrito en Go. | [Enlace](https://github.com/projectdiscovery/naabu) | 📚 |
| Nmap | Escáner de red de referencia; en recon identifica hosts y servicios. | [Enlace](https://nmap.org) | 📚 |
| proxify | Proxy "navaja suiza" para capturar y manipular tráfico en recon/pruebas. | [Enlace](https://github.com/projectdiscovery/proxify) | 🎯 |
| wtfis | Búsqueda pasiva de hosts, dominios e IP con salida legible (usa Passivetotal/VirusTotal). | [Enlace](https://github.com/pirxthepilot/wtfis) | 🎯 |
| Driftnet | Captura y reconstruye imágenes del tráfico de red observado. | [Enlace](https://github.com/deiv/driftnet) | 🎯 |
| Spyse | Motor de activos de Internet (descontinuado / integrado en otros). | *sin enlace oficial confiable* | 🎯 |
| Orb | Utilidad de reconocimiento de infraestructura. | *sin enlace oficial confiable* | 🎯 |
| Minimalistic Offensive Security Tools | Escáneres TCP/UDP minimalistas para entornos restringidos. | *sin enlace oficial confiable* | 🎯 |

---

## 🧾 Comandos rápidos

```bash
# Subdominios y correos con theHarvester
theHarvester -d ejemplo.com -b all

# Subdominios pasivos
subfinder -d ejemplo.com -silent

# Registros DNS
dig ejemplo.com ANY +noall +answer
```

## 📖 Referencias
- [OSINT Framework](https://osintframework.com/)
- [OWASP Amass — documentación](https://github.com/owasp-amass/amass)
