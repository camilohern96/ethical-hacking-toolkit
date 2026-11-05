# 12 · Cloud y Contenedores

Auditoría de configuraciones de nube (AWS, Azure, GCP), buckets de almacenamiento, contenedores y Kubernetes.

[⬅ Volver al índice](../README.md)

> **Estado:** ✅ la he utilizado · 📚 la conozco · 🎯 por aprender
>
> **Precio:** 🆓 gratuita / open source · 🟡 freemium (versión gratis + funciones de pago) · 💰 de pago

---

## ☁️ Auditoría multi-nube

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| ScoutSuite | Auditoría de configuración de seguridad en AWS, Azure y GCP. | [Enlace](https://github.com/nccgroup/ScoutSuite) | 🆓 | 📚 |
| Prowler | Evaluación de seguridad y cumplimiento (AWS/Azure/GCP/K8s). | [Enlace](https://github.com/prowler-cloud/prowler) | 🆓 | 📚 |
| CloudFox | Enumera la superficie de ataque y rutas de escalada en la nube. | [Enlace](https://github.com/BishopFox/cloudfox) | 🆓 | 🎯 |

## 🟠 AWS

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Pacu | Framework de explotación y post-explotación para AWS. | [Enlace](https://github.com/RhinoSecurityLabs/pacu) | 🆓 | 🎯 |
| S3Scanner | Encuentra y evalúa buckets S3 abiertos. | [Enlace](https://github.com/sa7mon/S3Scanner) | 🆓 | ✅ |
| lazys3 | Enumera buckets S3 por diccionario de nombres. | [Enlace](https://github.com/nahamsec/lazys3) | 🆓 | ✅ |
| Bucket Finder | Busca y lista buckets S3 accesibles. | [Enlace](https://digi.ninja/projects/bucket_finder.php) | 🆓 | 🎯 |
| s3-buckets-bruteforcer | Fuerza bruta de nombres de buckets S3. | [Enlace](https://github.com/gwen001/s3-buckets-finder) | 🆓 | ✅ |

## 🔵 Azure

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Azucar | Evalúa la postura de seguridad de un entorno Azure. | [Enlace](https://github.com/nccgroup/azucar) | 🆓 | 🎯 |

## 🐳 Contenedores y Kubernetes

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| Trivy | Escaneo de vulnerabilidades en imágenes, repos e IaC. | [Enlace](https://github.com/aquasecurity/trivy) | 🆓 | ✅ |
| Grype | Escáner de vulnerabilidades de imágenes de contenedor. | [Enlace](https://github.com/anchore/grype) | 🆓 | 🎯 |
| kube-hunter | Busca debilidades explotables en clústeres Kubernetes. | [Enlace](https://github.com/aquasecurity/kube-hunter) | 🆓 | 📚 |
| kube-bench | Comprueba el CIS Benchmark de Kubernetes. | [Enlace](https://github.com/aquasecurity/kube-bench) | 🆓 | 📚 |
| Kube-Scan | Puntúa el riesgo de las cargas de trabajo en Kubernetes. | [Enlace](https://github.com/octarinesec/kube-scan) | 🆓 | 🎯 |
| Kubesec | Análisis de riesgo de manifiestos de Kubernetes. | [Enlace](https://kubesec.io) | 🆓 | 🎯 |
| KubiScan | Detecta roles y cuentas con privilegios peligrosos en Kubernetes (CyberArk). | [Enlace](https://github.com/cyberark/KubiScan) | 🆓 | 🎯 |
| Sysdig | Seguridad y monitoreo de contenedores y Kubernetes en tiempo de ejecución. | [Enlace](https://sysdig.com) | 🟡 | 🎯 |
| Docker Bench for Security | Comprueba buenas prácticas de seguridad en Docker. | [Enlace](https://github.com/docker/docker-bench-security) | 🆓 | 📚 |

## 🔑 Búsqueda de secretos

| Herramienta | Para qué sirve | Enlace | Precio | Estado |
|-------------|----------------|--------| :------: |:------:|
| DumpsterDiver | Busca secretos y claves (alta entropía) en archivos y repos. | [Enlace](https://github.com/securing/DumpsterDiver) | 🆓 | ✅ |

---

## 📖 Referencias
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)
- [HackTricks Cloud](https://cloud.hacktricks.xyz/)
