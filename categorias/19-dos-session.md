# 19 · DoS/DDoS y Secuestro de Sesiones

Herramientas para pruebas de **denegación de servicio** y **secuestro de sesiones** en entornos autorizados, con sus respectivas **defensas**.

[⬅ Volver al índice](../README.md)

> **Estado:** ✅ la he utilizado · 📚 la conozco · 🎯 por aprender
>
> **Precio:** 🆓 gratuita / open source · 🟡 freemium (versión gratis + funciones de pago) · 💰 de pago

> 🔒 Las pruebas de DoS solo deben ejecutarse contra infraestructura **propia** o con autorización escrita y ventana acordada. Un ataque DoS no autorizado es delito y puede afectar a terceros.

---

## 💥 Herramientas de DoS / DDoS (laboratorio)

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| LOIC | Generador de carga de red para pruebas de estrés (Low Orbit Ion Cannon). | [Enlace](https://sourceforge.net/projects/loic/) | 🆓 | 🎯 |
| HULK | Genera peticiones HTTP únicas para saturar un servidor web. | [Enlace](https://github.com/grafov/hulk) | 🆓 | 🎯 |
| Slowloris | Agota conexiones manteniendo peticiones HTTP abiertas (bajo ancho de banda). | [Enlace](https://github.com/gkbrk/slowloris) | 🆓 | 🎯 |
| PyLoris | Herramienta de prueba de agotamiento de conexiones. | [Enlace](https://motoma.io/pyloris/) | 🆓 | 🎯 |
| Metasploit | Incluye módulos auxiliares de DoS para pruebas controladas. | [Enlace](https://www.metasploit.com) | 🟡 | 📚 |
| HOIC | Generador de carga HTTP de alto volumen (High Orbit Ion Cannon). | *sin enlace oficial confiable* | 🆓 | 🎯 |

## 🍯 Honeypots / detección

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Cowrie | Honeypot SSH/Telnet para capturar y estudiar ataques. | [Enlace](https://github.com/cowrie/cowrie) | 🆓 | 🎯 |
| Artillery | Honeypot y monitoreo con alertas (Binary Defense). | [Enlace](https://github.com/BinaryDefense/artillery) | 🆓 | 🎯 |
| KFSensor | IDS basado en honeypot para Windows. | [Enlace](https://www.keyfocus.net/kfsensor/) | 💰 | 🎯 |

## 🛡️ Protección DDoS

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Cloudflare | Mitigación de DDoS y WAF en la nube. | [Enlace](https://www.cloudflare.com) | 🟡 | 📚 |
| DDoS-GUARD | Servicio de protección contra DDoS. | [Enlace](https://ddos-guard.net) | 💰 | 🎯 |
| F5 DDoS Protection | Soluciones de mitigación de DDoS. | [Enlace](https://www.f5.com) | 💰 | 🎯 |
| Anti DDoS Guardian | Protección DDoS para servidores Windows. | [Enlace](https://www.beethink.com) | 💰 | 🎯 |

## 🪝 Secuestro de sesiones

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Bettercap | MITM y captura/manipulación de sesiones. | [Enlace](https://www.bettercap.org) | 🆓 | 📚 |
| Burp Suite | Intercepta y manipula tokens/cookies de sesión. | [Enlace](https://portswigger.net/burp) | 🟡 | 📚 |
| Hetty | Proxy HTTP para análisis de seguridad (alternativa open source a Burp). | [Enlace](https://github.com/dstotijn/hetty) | 🆓 | 🎯 |
| sslstrip | Degrada HTTPS a HTTP para interceptar sesiones (MITM). | [Enlace](https://github.com/moxie0/sslstrip) | 🆓 | 🎯 |
| WebSploit | Framework de ataques MITM y web. | [Enlace](https://github.com/The404Hacking/websploit) | 🆓 | 🎯 |
| DroidSniff | Captura de sesiones en redes WiFi desde Android. | [Enlace](https://github.com/evozi/DroidSniff) | 🆓 | 🎯 |

## 🛡️ Defensa de sesiones

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Fiddler | Proxy de depuración para inspeccionar tráfico y cookies. | [Enlace](https://www.telerik.com/fiddler) | 🆓 | 📚 |
| Checkmarx | SAST para detectar fallos de manejo de sesiones en el código. | [Enlace](https://checkmarx.com) | 💰 | 🎯 |

---

## 📖 Referencias
- [OWASP — Session Management Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html)
- [CISA — Understanding Denial-of-Service Attacks](https://www.cisa.gov/news-events/news/understanding-denial-service-attacks)
