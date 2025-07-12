![GitHub release downloads](https://img.shields.io/github/downloads/CyberiusCompany/Cyberius-Unzip-Cracker/latest/total)
![Versión](https://img.shields.io/badge/versión-1.0.0-blue)
![Sistema](https://img.shields.io/badge/windows-x64-green)
![Sistema](https://img.shields.io/badge/linux-x64-green)
![Licencia](https://img.shields.io/badge/licencia-Privada-red)
![Uso](https://img.shields.io/badge/uso-solo%20legal-important)
![Python](https://img.shields.io/badge/python-3.7%2B-yellow)
![Tested on](https://img.shields.io/badge/tested%20on-Windows%2010%2F11%20%7C%20Ubuntu%2022.04-blue)

<p align="center">
  <img src="https://flagcdn.com/w40/es.png" alt="Español" title="Español">
  <strong>Español</strong>
  &nbsp;|&nbsp;
  <a href="README.en.md">
    <img src="https://flagcdn.com/w40/us.png" alt="English" title="English">
    <strong>English</strong>
  </a>
  &nbsp;|&nbsp;
  <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0&list=RDxvFZjo5PgG0&start_radio=1&pp=ygUTcmljayByb2xsaW5nIG5vIGFkc6AHAQ%3D%3D">
    <img src="https://flagcdn.com/w40/jp.png" alt="日本語" title="Japanese">
    <strong>日本語</strong>
  </a>
</p>

# CyDorker

CyDorker es una herramienta de reconocimiento pasivo que automatiza y simplifica la fase de recolección de información en auditorías de ciberseguridad. Está orientada a OSINT (Open Source Intelligence) sobre nombres de dominio, facilitando el acceso a datos públicos útiles para análisis iniciales.

- Github Pages de este Proyecto: https://cyberiuscompany.github.io/CyDorker/
- DeepWiki de la herramienta: https://deepwiki.com/cyberiuscompany/CyDorker

---

<p align="center">
  <img src="icono.png" alt="Banner" width="500"/>
</p

---

## 🔍 Dorkers disponibles en CyDorker (27)

1. 🌐 **Open Redirect** – Detecta redirecciones abiertas
2. 🤖 **Robots.txt** – Inspecciona reglas de rastreo del sitio
3. 🔑 **Password files** – Busca ficheros como `.env`, `.htpasswd`, `passwd`, etc.
4. 📂 **Directory Listing** – Encuentra índices de carpetas sin protección
5. 🗃️ **Database related** – Localiza ficheros `.sql`, `.db`, `.sqlite`
6. ⚙️ **Config and log files** – Busca archivos `.conf`, `.log`, `.ini`
7. 💾 **Backup files** – Detecta `.zip`, `.bak`, `.tar`, `.old`, etc.
8. 🔐 **Login Pages** – Identifica paneles de inicio de sesión
9. 💻 **phpinfo()** – Detecta páginas expuestas con `phpinfo()`
10. 🐱 **Search in GitHub** – Busca exposiciones en código público
11. 🌍 **Find Subdomains** – Encuentra subdominios relacionados
12. 🔁 **Reverse IP Lookup** – Dominios alojados en la misma IP
13. 📜 **crt.sh Lookup** – Certificados SSL públicos indexados
14. 🪣 **S3 Bucket Discovery** – Busca buckets públicos de Amazon S3
15. 💬 **StackOverflow Search** – Consultas relacionadas en StackOverflow
16. 📄 **Pasting Sites** – Busca filtraciones en Pastebin, Ghostbin, etc.
17. 🧩 **What CMS?** – Detecta el sistema de gestión de contenidos (CMS)
18. 📝 **WordPress Contents** – Inspecciona archivos comunes de WordPress
19. 🔍 **WordPress Deep Search** – Búsqueda más avanzada de contenido WP
20. 🛡️ **Vulnerable Search Strings** – Busca patrones usados en ataques
21. ✅ **SSL Server Test** – Verifica estado y fuerza del certificado SSL
22. 🕰️ **Wayback Machine Search** – Accede a versiones archivadas del sitio
23. 🛰️ **Shodan Search** – Información de dispositivos o puertos expuestos
24. 🧠 **grep.app Search** – Búsqueda profunda en repos públicos
25. 🛑 **Check Security Headers** – Verifica encabezados de seguridad HTTP
26. 🌐 **Passive Subdomain Resolution** – Resolución pasiva de DNS
27. 🧾 **Sensitive Strings & Exposed Configs** – Palabras clave sensibles indexadas

---

## 🖼️ Vista Previa

### Index Principal
![index](./index.png)

### Iniciando una búsqueda de ejemplo de (PDF Sensibles)
![Iniciando Búsqueda](./Iniciando%20Busqueda.png)

### Resultados de la búsqueda de (PDF Sensibles)
![Resultado de la Búsqueda](./Resultado%20Busqueda.png)

---

## 🧩 Estructura del Proyecto

```plaintext
CYDORKER/
├── files/                 # Archivos JS, CSS, etc.
├── images/                # Recursos gráficos adicionales
├── icono.ico              # Ícono del navegador
├── index.html             # Archivo principal HTML
├── index.js               # Lógica principal del buscador
├── test.svg / test.js     # Archivos de prueba
├── README.md              # Este archivo
└── *.png                  # Capturas para documentación
```
---

## 📄 Documentación adicional

- [🔐 Seguridad](.github/SECURITY.md)
- [📜 Licencia](LICENSE)
- [🤝 Código de Conducta](.github/CODE_OF_CONDUCT.md)
- [📬 Cómo contribuir](.github/CONTRIBUTING.md)
- [📢 Soporte](.github/SUPPORT.md)
- [⚠️ Aviso legal](DISCLAIMER.md)

---

## ⚙️ ¿Cómo usarlo?

1. Clona el repositorio:
   ```bash
   git clone https://github.com/cyberiuscompany/CyDorker.git
   cd CyDoker
   index.html # Puedes añadir ese fichero a un navegador
   [Alternativa] Github Pages : https://cyberiuscompany.github.io/CyDorker/
    ```
