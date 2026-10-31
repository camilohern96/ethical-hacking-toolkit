# 05 · Aplicaciones Web

Proxies de intercepción, fuzzing de contenido y pruebas de inyección.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| Burp Suite | Proxy de intercepción y suite completa de pruebas web | [portswigger.net](https://portswigger.net/burp) | 📚 |
| OWASP ZAP | Proxy de intercepción y escáner web open source | [zaproxy.org](https://www.zaproxy.org/) | 📚 |
| Caido | Proxy web ligero y moderno | [caido.io](https://caido.io/) | 📚 |
| ffuf | Fuzzer web muy rápido (directorios, parámetros, vhosts) | [GitHub](https://github.com/ffuf/ffuf) | 📚 |
| Gobuster | Fuerza bruta de directorios, DNS y vhosts | [GitHub](https://github.com/OJ/gobuster) | 📚 |
| Feroxbuster | Descubrimiento recursivo de contenido | [GitHub](https://github.com/epi052/feroxbuster) | 📚 |
| dirsearch | Descubrimiento de rutas web | [GitHub](https://github.com/maurosoria/dirsearch) | 📚 |
| sqlmap | Detección y explotación automatizada de SQL Injection | [sqlmap.org](https://sqlmap.org/) | 📚 |
| WPScan | Escáner de seguridad para WordPress | [wpscan.com](https://wpscan.com/) | 📚 |
| Dalfox | Escáner de XSS | [GitHub](https://github.com/hahwul/dalfox) | 📚 |
| Commix | Detección de inyección de comandos | [GitHub](https://github.com/commixproject/commix) | 📚 |
| jwt_tool | Análisis y pruebas sobre JSON Web Tokens | [GitHub](https://github.com/ticarpi/jwt_tool) | 📚 |
| Arjun | Descubrimiento de parámetros HTTP ocultos | [GitHub](https://github.com/s0md3v/Arjun) | 📚 |
| Katana | Crawler web (ProjectDiscovery) | [GitHub](https://github.com/projectdiscovery/katana) | 📚 |
| Postman / Insomnia | Pruebas manuales de APIs | [postman.com](https://www.postman.com/) | 📚 |

## 🧾 Comandos rápidos

```bash
# Fuzzing de directorios
ffuf -u http://objetivo/FUZZ -w /usr/share/seclists/Discovery/Web-Content/common.txt

# Gobuster de directorios con extensiones
gobuster dir -u http://objetivo -w wordlist.txt -x php,txt,html

# sqlmap sobre una petición guardada desde Burp
sqlmap -r peticion.txt --batch --dbs
```

## 📖 Referencias
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [OWASP WSTG](https://owasp.org/www-project-web-security-testing-guide/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
