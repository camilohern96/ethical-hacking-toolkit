# 08 · Post-Explotación y Escalada de Privilegios

Fase posterior al acceso inicial en ejercicios autorizados: enumeración local, escalada de privilegios, movimiento lateral, pivoting, persistencia, Command & Control y borrado de rastros. Incluye además **contramedidas defensivas**.

[⬅ Volver al índice](../README.md)

> Leyenda de estado: ✅ utilizada · 📚 conocida · 🎯 por aprender

---

## ⬆️ Enumeración local y escalada de privilegios

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| PEASS-ng (LinPEAS / WinPEAS) | Enumera vectores de escalada en Linux y Windows de forma automatizada. | [Enlace](https://github.com/peass-ng/PEASS-ng) | 📚 |
| GTFOBins | Catálogo de binarios Unix abusables para *bypass* y escalada. | [Enlace](https://gtfobins.github.io/) | 📚 |
| LOLBAS | Catálogo de binarios/scripts legítimos de Windows abusables. | [Enlace](https://lolbas-project.github.io/) | 📚 |
| pspy | Monitorea procesos y tareas cron sin privilegios (Linux). | [Enlace](https://github.com/DominicBreuker/pspy) | 📚 |
| BeRoot | Comprueba configuraciones que permiten escalar privilegios (Win/Linux/Mac). | [Enlace](https://github.com/AlessandroZ/BeRoot) | 🎯 |
| PowerSploit | Conjunto de módulos PowerShell para post-explotación y escalada. | [Enlace](https://github.com/PowerShellMafia/PowerSploit) | 📚 |
| FullPowers | Restaura los privilegios de una cuenta de servicio en Windows. | [Enlace](https://github.com/itm4n/FullPowers) | 🎯 |
| WES-NG (Windows Exploit Suggester) | Sugiere exploits de escalada según el nivel de parches de Windows. | [Enlace](https://github.com/bitsadmin/wesng) | 🎯 |

## ↔️ Movimiento lateral y ejecución remota

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| PsExec (Sysinternals) | Ejecuta procesos en sistemas Windows remotos. | [Enlace](https://learn.microsoft.com/sysinternals/downloads/psexec) | 📚 |
| CrackMapExec / NetExec | Ejecución y movimiento lateral masivo en redes AD. | [Enlace](https://github.com/Pennyw0rth/NetExec) | 📚 |
| Pupy | RAT multiplataforma de post-explotación y C2. | [Enlace](https://github.com/n1nj4sec/pupy) | 🎯 |
| PDQ Deploy | Despliegue remoto de software (abusable para ejecución). | [Enlace](https://www.pdq.com) | 🎯 |
| Dameware Remote Support | Soporte y control remoto de equipos. | [Enlace](https://www.dameware.com) | 🎯 |
| ManageEngine Endpoint Central | Gestión y despliegue centralizado de endpoints. | [Enlace](https://www.manageengine.com/products/desktop-central/) | 🎯 |

## 🕳️ Túneles y pivoting

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Chisel | Túneles TCP/UDP sobre HTTP para pivoting. | [Enlace](https://github.com/jpillora/chisel) | 📚 |
| ligolo-ng | Pivoting mediante una interfaz TUN, cómodo y rápido. | [Enlace](https://github.com/nicocha30/ligolo-ng) | 🎯 |

## 🛰️ Command & Control (C2)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Sliver | Framework C2 open source para *adversary simulation*. | [Enlace](https://github.com/BishopFox/sliver) | 📚 |
| Mythic | Framework C2 modular y colaborativo. | [Enlace](https://github.com/its-a-feature/Mythic) | 🎯 |
| PowerShell Empire | Framework C2 basado en PowerShell/Python. | [Enlace](https://github.com/BC-SECURITY/Empire) | 🎯 |
| Cobalt Strike | Plataforma comercial de *adversary simulation*. | [Enlace](https://www.cobaltstrike.com/) | 📚 |

## 🧩 Secuestro de DLL / Dylib (auditoría)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Dependency Walker | Lista las DLL de las que depende un ejecutable Windows. | [Enlace](https://www.dependencywalker.com) | 🎯 |
| DLLSpy | Detecta DLL *hijacking* en procesos y servicios de Windows (CyberArk). | [Enlace](https://github.com/cyberark/DLLSpy) | 🎯 |
| Dylib Hijack Scanner | Detecta *hijacking* de dylib en macOS (Objective-See). | [Enlace](https://objective-see.org/products/dhs.html) | 🎯 |

## ⌨️ Keyloggers y monitoreo (software)

> Herramientas de monitoreo/registro de actividad. En pentest se estudian como vectores de captura; su uso solo es legítimo con autorización explícita del dueño del equipo.

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| Spyrix Free Keylogger | Registra pulsaciones y actividad en Windows. | [Enlace](https://www.spyrix.com) | 🎯 |
| REFOG Keylogger | Monitoreo de actividad y pulsaciones. | [Enlace](https://www.refog.com) | 🎯 |
| StaffCop | Monitoreo de actividad de empleados (entornos corporativos). | [Enlace](https://www.staffcop.com) | 🎯 |
| Spytech SpyAgent | Software de monitoreo de actividad. | [Enlace](https://www.spytech-web.com) | 🎯 |
| KeyGrabber (hardware) | Keylogger físico USB/PS2 (referencia de hardware). | [Enlace](https://www.keelog.com) | 🎯 |

## 🧹 Borrado de rastros (anti-forense)

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| BleachBit | Limpia archivos temporales, caché e historial del sistema. | [Enlace](https://www.bleachbit.org) | 🎯 |
| CCleaner | Limpieza de rastros y archivos temporales en Windows. | [Enlace](https://www.ccleaner.com) | 🎯 |
| Privacy Eraser | Borra historial y rastros de actividad. | [Enlace](https://www.cybertronsoft.com) | 🎯 |
| DBAN | Borrado seguro de discos completos. | [Enlace](https://dban.org) | 🎯 |
| cipher.exe / fsutil | Comandos nativos de Windows para sobrescribir espacio libre y gestionar marcas de tiempo. | [Enlace](https://learn.microsoft.com/windows-server/administration/windows-commands/cipher) | 🎯 |

## 🛡️ Contramedidas defensivas

| Herramienta | Para qué sirve | Enlace | Estado |
|-------------|----------------|--------|:------:|
| KeyScrambler | Cifra las pulsaciones del teclado para frustrar keyloggers. | [Enlace](https://www.qfxsoftware.com) | 🎯 |
| SpyShelter | Anti-keylogger y protección contra spyware. | [Enlace](https://www.spyshelter.com) | 🎯 |
| GMER | Detección y eliminación de rootkits en Windows. | [Enlace](http://www.gmer.net) | 🎯 |
| Malwarebytes Anti-Rootkit | Detecta y elimina rootkits. | [Enlace](https://www.malwarebytes.com) | 🎯 |
| TDSSKiller (Kaspersky) | Elimina rootkits de la familia TDSS y similares. | [Enlace](https://www.kaspersky.com/downloads/tdsskiller) | 🎯 |
| StreamArmor | Detecta flujos de datos alternativos (ADS) ocultos en NTFS. | [Enlace](https://securityxploded.com/streamarmor.php) | 🎯 |

---

## 📖 Referencias
- [HackTricks](https://book.hacktricks.xyz/) — metodología de escalada y post-explotación
- [MITRE ATT&CK](https://attack.mitre.org/) — tácticas y técnicas
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)
