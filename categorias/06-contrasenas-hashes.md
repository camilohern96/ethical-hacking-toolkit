# 06 · Contraseñas y Hashes

Ataques a credenciales en entornos autorizados: *password spraying*, fuerza bruta online, cracking offline de hashes, extracción de hashes y recuperación forense de contraseñas.

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

---

## 💨 Password spraying

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| CrackMapExec / NetExec | "Navaja suiza" para evaluar redes AD; incluye *spraying* de credenciales (NetExec es su sucesor mantenido). | [Enlace](https://github.com/Pennyw0rth/NetExec) | 📚 |
| Kerbrute | Enumera y prueba credenciales contra Kerberos (AD). | [Enlace](https://github.com/ropnop/kerbrute) | 📚 |
| Invoke-DomainPasswordSpray | Script PowerShell para *spraying* de contraseñas en un dominio. | [Enlace](https://github.com/dafthack/DomainPasswordSpray) | 🎯 |
| Spray | Herramienta de *password spraying* controlado (evita bloqueos). | [Enlace](https://github.com/Greenwolf/Spray) | 🎯 |
| Omnispray | Framework modular de *spraying* y enumeración de usuarios. | [Enlace](https://github.com/0xZDH/omnispray) | 🎯 |

## 🔓 Cracking offline de hashes

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Hashcat | Cracking de hashes acelerado por GPU, el más rápido y versátil. | [Enlace](https://hashcat.net/hashcat/) | 📚 |
| John the Ripper | Cracking de hashes clásico, con utilidades `*2john` para múltiples formatos. | [Enlace](https://www.openwall.com/john/) | 📚 |
| RainbowCrack (rtgen) | Descifra hashes usando *rainbow tables* precalculadas. | [Enlace](https://project-rainbowcrack.com) | 🎯 |
| ophcrack | Recupera contraseñas de Windows mediante *rainbow tables*. | [Enlace](https://ophcrack.sourceforge.io) | 🎯 |
| L0phtCrack | Auditor de contraseñas de Windows (ahora de código abierto). | [Enlace](https://www.l0phtcrack.com) | 🎯 |
| CrackStation | Servicio web que busca hashes en tablas precalculadas. | [Enlace](https://crackstation.net/) | 📚 |

## 🌐 Fuerza bruta online

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| THC-Hydra | Fuerza bruta online contra decenas de protocolos (SSH, RDP, HTTP, etc.). | [Enlace](https://github.com/vanhauser-thc/thc-hydra) | 📚 |
| Medusa | Fuerza bruta online paralela y modular. | [Enlace](https://github.com/jmk-foofus/medusa) | 📚 |
| Secure Shell Bruteforcer (SSB) | Fuerza bruta rápida específica para SSH. | [Enlace](https://github.com/HightechSec/ssb) | 🎯 |

## 🗝️ Extracción / volcado de hashes

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Mimikatz | Extrae contraseñas, hashes y tickets Kerberos de la memoria de Windows. | [Enlace](https://github.com/gentilkiwi/mimikatz) | 📚 |
| pwdump7 | Vuelca los hashes de la SAM de Windows. | [Enlace](https://www.openwall.com/passwords/windows-pwdump) | 🎯 |
| PowerShell Empire | Framework de post-explotación con módulos de volcado de credenciales. | [Enlace](https://github.com/BC-SECURITY/Empire) | 🎯 |
| DSInternals | Módulo PowerShell para interactuar con la base de datos de AD (ntds.dit). | [Enlace](https://github.com/MichaelGrafnetter/DSInternals) | 🎯 |
| Ntdsxtract | Extrae información y hashes de volcados de `ntds.dit`. | [Enlace](https://github.com/csababarta/ntdsxtract) | 🎯 |

## 🔁 Recuperación forense de contraseñas

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Elcomsoft Distributed Password Recovery | Recuperación distribuida de contraseñas acelerada por GPU. | [Enlace](https://www.elcomsoft.com/edpr.html) | 🎯 |
| Passware Kit Forensic | Suite forense para recuperar contraseñas y descifrar archivos. | [Enlace](https://www.passware.com) | 🎯 |
| Password Recovery Toolkit (PRTK) | Herramienta forense de recuperación de contraseñas (AccessData/Exterro). | [Enlace](https://www.exterro.com) | 🎯 |
| PCUnlocker | Restablece contraseñas de cuentas locales de Windows. | [Enlace](https://www.pcunlocker.com) | 🎯 |

## 🧱 Generación de diccionarios

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| CeWL | Genera diccionarios a partir del contenido de un sitio web. | [Enlace](https://github.com/digininja/CeWL) | 📚 |
| Crunch | Generador de wordlists por patrones y rangos de caracteres. | [Enlace](https://sourceforge.net/projects/crunch-wordlist/) | 📚 |
| CUPP | Genera diccionarios personalizados a partir del perfil de una persona. | [Enlace](https://github.com/Mebus/cupp) | 📚 |

## 🔎 Identificación de hashes

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Name-That-Hash | Identifica el tipo de un hash desconocido. | [Enlace](https://github.com/HashPals/Name-That-Hash) | 📚 |
| hashid / hash-identifier | Identifican algoritmos de hash desde la terminal. | [Enlace](https://github.com/psypanda/hashID) | 📚 |

## 🔑 Bases de contraseñas por defecto

| Recurso | Para qué sirve | Enlace | Estado |
|---------|----------------|--------|:------:|
| CIRT.net | Base de datos de contraseñas por defecto de dispositivos. | [Enlace](https://cirt.net/passwords) | 📚 |
| RouterPasswords | Contraseñas por defecto de routers por fabricante. | [Enlace](https://www.routerpasswords.com) | 📚 |
| Open-Sez.me | Buscador de credenciales por defecto. | [Enlace](https://open-sez.me) | 🎯 |
| default-password.info | Listado de contraseñas por defecto por fabricante. | [Enlace](https://default-password.info) | 🎯 |
| DefaultPassword.us | Base de contraseñas por defecto. | [Enlace](http://www.defaultpassword.us) | 🎯 |
| FortyPoundHead | Repositorio de contraseñas por defecto. | [Enlace](https://www.fortypoundhead.com) | 🎯 |

---

## 🧾 Comandos rápidos

```bash
# Hashcat (modo 0 = MD5) con rockyou
hashcat -m 0 hashes.txt /usr/share/wordlists/rockyou.txt

# John con formato automático
john --wordlist=/usr/share/wordlists/rockyou.txt hashes.txt

# Hydra contra SSH (solo en entornos autorizados)
hydra -l usuario -P wordlist.txt ssh://10.10.10.10
```

📌 Tabla de modos de Hashcat: <https://hashcat.net/wiki/doku.php?id=example_hashes>
