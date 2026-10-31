# 04 · Explotación

Frameworks, bases de datos de exploits y utilidades para validar vulnerabilidades.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| Metasploit Framework | Framework de explotación más usado (msfconsole, msfvenom) | [metasploit.com](https://www.metasploit.com/) | 📚 |
| Exploit-DB | Archivo público de exploits y PoCs | [exploit-db.com](https://www.exploit-db.com/) | 📚 |
| Armitage | Interfaz gráfica para Metasploit | [GitHub](https://github.com/r00t0v3rr1d3/armitage) | 📚 |
| Netcat / Ncat | "Navaja suiza" de TCP/UDP: listeners, transferencias | Kali / [nmap.org/ncat](https://nmap.org/ncat/) | 📚 |
| Socat | Relés y conexiones bidireccionales avanzadas | Kali | 📚 |
| pwncat-cs | Manejo mejorado de reverse shells | [GitHub](https://github.com/calebstewart/pwncat) | 📚 |
| Revshells.com | Generador de one-liners de reverse shell | [revshells.com](https://www.revshells.com/) | 📚 |
| pwntools | Librería Python para desarrollo de exploits / CTF | [GitHub](https://github.com/Gallopsled/pwntools) | 📚 |

## 🧾 Comandos rápidos

```bash
# Iniciar Metasploit y buscar un módulo
msfconsole -q
msf6 > search type:exploit name:smb

# Listener con netcat
nc -lvnp 4444

# Estabilizar una shell
python3 -c 'import pty; pty.spawn("/bin/bash")'
```
