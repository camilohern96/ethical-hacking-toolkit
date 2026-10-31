# 06 · Contraseñas y Hashes

Identificación de hashes, cracking offline y fuerza bruta online contra servicios autorizados.

[⬅ Volver al índice](../README.md)

| Herramienta | Descripción | Enlace | Estado |
|-------------|-------------|--------|:------:|
| Hashcat | Cracking de hashes acelerado por GPU | [hashcat.net](https://hashcat.net/hashcat/) | 📚 |
| John the Ripper | Cracking de hashes clásico (+ utilidades *2john) | [openwall.com/john](https://www.openwall.com/john/) | 📚 |
| Hydra | Fuerza bruta online contra múltiples protocolos | [GitHub](https://github.com/vanhauser-thc/thc-hydra) | 📚 |
| Medusa | Fuerza bruta online paralela | [GitHub](https://github.com/jmk-foofus/medusa) | 📚 |
| hash-identifier / hashid / Name-That-Hash | Identificación del tipo de hash | [GitHub](https://github.com/HashPals/Name-That-Hash) | 📚 |
| CeWL | Genera wordlists a partir del contenido de un sitio web | [GitHub](https://github.com/digininja/CeWL) | 📚 |
| Crunch | Generador de wordlists por patrones | Kali | 📚 |
| CUPP | Wordlists basadas en perfil de una persona | [GitHub](https://github.com/Mebus/cupp) | 📚 |
| CrackStation | Búsqueda online de hashes en tablas | [crackstation.net](https://crackstation.net/) | 📚 |

## 🧾 Comandos rápidos

```bash
# Hashcat (modo 0 = MD5) con rockyou
hashcat -m 0 hashes.txt /usr/share/wordlists/rockyou.txt

# John con formato automático
john --wordlist=/usr/share/wordlists/rockyou.txt hashes.txt

# Convertir un zip protegido para John
zip2john archivo.zip > zip.hash

# Hydra contra SSH (solo en entornos autorizados)
hydra -l usuario -P wordlist.txt ssh://10.10.10.10
```

📌 Tabla de modos de Hashcat: <https://hashcat.net/wiki/doku.php?id=example_hashes>
