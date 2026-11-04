# 10 · Forense, Reversing y Análisis de Malware

Análisis de binarios y malware, ingeniería inversa y forense digital (disco, memoria y red).

[⬅ Volver al índice](../README.md)

> **Estado:** ✅ la he utilizado · 📚 la conozco · 🎯 por aprender
>
> **Precio:** 🆓 gratuita / open source · 🟡 freemium (versión gratis + funciones de pago) · 💰 de pago

---

## 🔧 Desensambladores y decompiladores

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Ghidra | Suite de ingeniería inversa de la NSA (open source). | [Enlace](https://ghidra-sre.org/) | 🆓 | 📚 |
| IDA Free | Desensamblador y depurador de referencia. | [Enlace](https://hex-rays.com/ida-free/) | 🆓 | 📚 |
| radare2 / Cutter | Framework de reversing con interfaz de consola y gráfica. | [Enlace](https://rada.re) | 🆓 | 📚 |
| Binary Ninja | Plataforma de análisis de binarios. | [Enlace](https://binary.ninja/) | 💰 | 🎯 |

## 🐞 Depuradores

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| x64dbg | Depurador open source para binarios de Windows. | [Enlace](https://x64dbg.com) | 🆓 | 📚 |
| OllyDbg | Depurador clásico de 32 bits para Windows. | [Enlace](https://www.ollydbg.de) | 🆓 | 🎯 |
| WinDbg | Depurador oficial de Microsoft (kernel y usuario). | [Enlace](https://learn.microsoft.com/windows-hardware/drivers/debugger/) | 🆓 | 🎯 |
| GDB + pwndbg/GEF | Depurador de Linux con extensiones para exploiting. | [Enlace](https://github.com/pwndbg/pwndbg) | 🆓 | 📚 |

## 🪟 Análisis de binarios Windows (PE)

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| PE Explorer | Inspecciona y edita ejecutables PE (cabeceras, recursos). | [Enlace](https://www.heaventools.com/overview.htm) | 💰 | 🎯 |
| PEView | Visor ligero de la estructura de archivos PE. | [Enlace](http://wjradburn.com/software/) | 🆓 | 🎯 |
| Resource Hacker | Ver y editar recursos de ejecutables de Windows. | [Enlace](https://www.angusj.com/resourcehacker/) | 🆓 | 🎯 |
| Dependency Walker | Lista dependencias de DLL de un ejecutable. | [Enlace](https://www.dependencywalker.com) | 🆓 | 🎯 |
| pev (pescan) | Toolkit CLI para analizar ejecutables PE (incluye pescan). | [Enlace](https://github.com/merces/pev) | 🆓 | 🎯 |

## 🐧 ELF y 🍎 macOS

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| readelf / binutils | Inspecciona cabeceras y secciones de binarios ELF. | [Enlace](https://sourceware.org/binutils/) | 🆓 | 📚 |
| LIEF | Biblioteca para parsear y modificar ELF, PE y Mach-O. | [Enlace](https://lief.re) | 🆓 | 🎯 |
| otool / pagestuff | Herramientas nativas de macOS para inspeccionar Mach-O. | [Enlace](https://developer.apple.com/) | 🆓 | 🎯 |

## 📄 Macros de Office

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| oletools (oleid, oledump, olevba) | Analiza documentos OLE/Office y extrae macros VBA sospechosas. | [Enlace](https://github.com/decalage2/oletools) | 🆓 | 📚 |

## 🤖 Reversing de Android (APK)

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| APKTool | Decodifica y reempaqueta archivos APK. | [Enlace](https://apktool.org) | 🆓 | 📚 |
| jadx | Decompila Dalvik a código Java legible. | [Enlace](https://github.com/skylot/jadx) | 🆓 | 📚 |

## 🧫 Sandboxes y análisis dinámico de malware

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Hybrid Analysis | Servicio en línea de análisis automático de malware. | [Enlace](https://www.hybrid-analysis.com) | 🆓 | 📚 |
| Cuckoo Sandbox | Sandbox open source para análisis dinámico de malware. | [Enlace](https://cuckoosandbox.org) | 🆓 | 🎯 |
| Jotti's malware scan | Analiza un archivo con múltiples motores antivirus. | [Enlace](https://virusscan.jotti.org) | 🆓 | 🎯 |
| Valkyrie (Comodo) | Veredicto de archivos mediante análisis estático y dinámico. | [Enlace](https://valkyrie.comodo.com) | 🆓 | 🎯 |
| Intezer | Analiza reutilización de código para atribuir y clasificar malware. | [Enlace](https://www.intezer.com) | 🟡 | 🎯 |

## 📦 Análisis de dependencias (SCA)

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| OWASP Dependency-Check | Detecta dependencias con vulnerabilidades conocidas. | [Enlace](https://owasp.org/www-project-dependency-check/) | 🆓 | 🎯 |
| Snyk | Analiza dependencias, contenedores e IaC en busca de vulnerabilidades. | [Enlace](https://snyk.io) | 🟡 | 🎯 |
| Retire.js | Detecta librerías JavaScript con vulnerabilidades conocidas. | [Enlace](https://retirejs.github.io/retire.js/) | 🆓 | 🎯 |

## 🔬 Forense digital

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Autopsy / The Sleuth Kit | Suite de forense de discos. | [Enlace](https://www.sleuthkit.org) | 🆓 | 📚 |
| Volatility 3 | Análisis forense de memoria RAM. | [Enlace](https://github.com/volatilityfoundation/volatility3) | 🆓 | 📚 |
| Wireshark | Análisis forense de tráfico de red. | [Enlace](https://www.wireshark.org) | 🆓 | 📚 |
| binwalk | Análisis y extracción de firmware. | [Enlace](https://github.com/ReFirmLabs/binwalk) | 🆓 | 📚 |
| strings / xxd / file | Utilidades básicas de inspección de archivos. | [Enlace](https://www.gnu.org/software/binutils/) | 🆓 | 📚 |
| CyberChef | "Navaja suiza" de codificación y análisis en el navegador. | [Enlace](https://gchq.github.io/CyberChef/) | 🆓 | 📚 |

---

## 📖 Referencias
- [Documentación de Ghidra](https://ghidra-sre.org/CheatSheet.html)
- [MalwareBazaar (muestras para analistas)](https://bazaar.abuse.ch/)
- [microcorruption](https://microcorruption.com/) — retos de reversing
