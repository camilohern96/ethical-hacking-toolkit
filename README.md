# 🛡️ Ethical Hacking Toolkit

Repositorio personal donde consolido las herramientas que **he utilizado** o que **conozco** en el mundo del Ethical Hacking / Pentesting, organizadas por fase de una auditoría.

> ⚠️ **Aviso legal:** Todo el contenido de este repositorio tiene fines **educativos** y está pensado para usarse **únicamente** en sistemas propios, laboratorios o entornos donde exista **autorización expresa y por escrito**. El uso no autorizado de estas herramientas es ilegal. Ver [DISCLAIMER.md](DISCLAIMER.md).

---

## 🏷️ Leyenda de estado

Cada herramienta lleva una marca para saber en qué punto estoy con ella:

| Marca | Significado |
|:-----:|-------------|
| ✅ | La he **utilizado** en práctica / laboratorio / proyecto |
| 📚 | La **conozco** (teoría, documentación, cursos) |
| 🎯 | **Por aprender** / pendiente de probar |

---

## 📂 Categorías

| # | Categoría | Descripción |
|---|-----------|-------------|
| 01 | [Reconocimiento y OSINT](categorias/01-reconocimiento-osint.md) | Recolección pasiva de información |
| 02 | [Escaneo y Enumeración](categorias/02-escaneo-enumeracion.md) | Puertos, servicios, hosts |
| 03 | [Análisis de Vulnerabilidades](categorias/03-analisis-vulnerabilidades.md) | Escáneres automatizados |
| 04 | [Explotación](categorias/04-explotacion.md) | Frameworks y bases de exploits |
| 05 | [Aplicaciones Web](categorias/05-aplicaciones-web.md) | Proxies, fuzzing, inyecciones |
| 06 | [Contraseñas y Hashes](categorias/06-contrasenas-hashes.md) | Cracking y fuerza bruta |
| 07 | [Redes e Inalámbricas](categorias/07-redes-wireless.md) | Sniffing, MITM, WiFi |
| 08 | [Post-Explotación y Escalada](categorias/08-post-explotacion.md) | PrivEsc, pivoting, C2 |
| 09 | [Active Directory](categorias/09-active-directory.md) | Entornos Windows / dominio |
| 10 | [Forense y Reversing](categorias/10-forense-reversing.md) | Análisis de binarios y evidencias |
| 11 | [Móvil](categorias/11-movil.md) | Android / iOS |
| 12 | [Cloud y Contenedores](categorias/12-cloud-contenedores.md) | AWS, Azure, GCP, Docker, K8s |
| 13 | [Ingeniería Social](categorias/13-ingenieria-social.md) | Simulaciones de phishing autorizadas |
| 14 | [Distros, Labs y Práctica](categorias/14-labs-practica.md) | Entornos para entrenar |
| 15 | [Wordlists y Recursos](categorias/15-wordlists-recursos.md) | Diccionarios, cheatsheets, referencias |

---

## 🗂️ Estructura del repositorio

```
ethical-hacking-toolkit/
├── README.md              ← Índice general (este archivo)
├── DISCLAIMER.md          ← Aviso legal y uso ético
├── CONTRIBUTING.md        ← Cómo agregar herramientas
├── LICENSE
├── categorias/            ← Una ficha por categoría con tablas de herramientas
├── notas/                 ← Apuntes propios, writeups, comandos favoritos
├── scripts/               ← Scripts propios (helpers, automatizaciones)
└── plantillas/            ← Plantilla para documentar nuevas herramientas
```

---

## ➕ Cómo agregar una herramienta

1. Abre el archivo de la categoría correspondiente en `categorias/`.
2. Añade una fila a la tabla con: nombre, descripción, enlace oficial y estado (✅ 📚 🎯).
3. Si quieres documentarla a fondo, copia [`plantillas/herramienta.md`](plantillas/herramienta.md) a `notas/` y complétala.
4. Haz commit con un mensaje claro: `git commit -m "feat(web): agregar ffuf"`.

Más detalles en [CONTRIBUTING.md](CONTRIBUTING.md).

---

## 📈 Metodología de referencia

Las categorías siguen, a grandes rasgos, las fases de un pentest:

```
Reconocimiento → Escaneo/Enumeración → Análisis de vulnerabilidades
      → Explotación → Post-explotación → Reporte
```

Marcos de referencia útiles: **PTES**, **OWASP Testing Guide (WSTG)**, **MITRE ATT&CK**, **NIST SP 800-115**.
