<h2 align="center">
  <picture>
    <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.webp" type="image/webp">
    <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="25" height="25">
  </picture> ¡Hola! Soy Davinia
</h2>

<p align="center">
  <a href="mailto:rodriguezportillodavinia@gmail.com"><img src="https://img.shields.io/badge/rodriguezportillodavinia@gmail.com-blue?logo=gmail&logoColor=white" alt="Email"></a>
</p>

🛠️ Desarrolladora backend con **Python y Django**. Trabajo en aplicaciones internas de empresa: una plataforma de **recursos humanos**, **login único (SSO) con doble factor**, permisos por roles y la infraestructura con **Docker** que las mantiene en marcha. Me gusta el trabajo bien hecho: probar las cosas antes de darlas por terminadas, documentar cada tarea y que el código lo pueda entender el siguiente que llegue.

<div align="center">

## 💼 Trabajo realizado

</div>

Casi todo vive en repositorios privados de empresa. Estos son los casos de estudio: la ingeniería que hay detrás, sin detalles internos.

### 🤖 Plataforma de automatización de procesos web

**Problema:** procesos web repetitivos que se hacían a mano, cada uno con su propio flujo, formularios, pasarela de pago y formas de fallar.

**Construido:** un núcleo común reutilizable (login, formularios, pagos con 3-D Secure, descargas, avisos) y un módulo pequeño por proceso. La estrategia de cada proceso se elige según lo que exige: HTTP directo cuando se puede, navegador completo con Selenium o Playwright cuando hace falta. Un lanzador en paralelo con timeouts y limpieza de procesos huérfanos, pools de proxies con aislamiento de red en Linux y simuladores para probar sin efectos reales.

**Resultado:** procesos desatendidos que corren en paralelo y, cuando algo falla, avisan en Slack, abren una incidencia y guardan capturas para diagnosticarlo.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white"> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"> <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Slack%20API-4A154B?style=flat&logo=slack&logoColor=white">

### 👥 Plataforma de recursos humanos

**Problema:** hacía falta un sistema de RRHH propio (empleados, ausencias, fichajes, nóminas y contratación) adaptado a la estructura de la empresa y a quién puede ver qué.

**Construido:** sobre **Horilla HR** (Django, código abierto): roles y permisos de grano fino (por ejemplo, quién ve el historial de un empleado), alta de empresas mediante migraciones de datos, edición de grupos sincronizada con el proveedor de identidad y generación de nóminas en PDF.

**Resultado:** en producción, con los permisos definidos en código y no a mano.

<img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white">

### 🔐 Inicio de sesión único y seguridad

**Problema:** cada aplicación interna tenía su propio inicio de sesión y sus propias contraseñas.

**Construido:** un proveedor de identidad con **Authentik** (OAuth2 / OIDC) con doble factor, acceso de emergencia y roles por grupos. La política de contraseñas se gestiona como configuración versionada (blueprints), con auditoría del MFA y un inicio de sesión personalizado con CSS limpio y mantenible.

**Resultado:** un único inicio de sesión con doble factor para las aplicaciones internas.

<img src="https://img.shields.io/badge/Authentik-FD4B2D?style=flat&logo=authentik&logoColor=white"> <img src="https://img.shields.io/badge/OAuth2%20%2F%20OIDC-000000?style=flat&logo=openid&logoColor=white"> <img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white">

### 🧠 Herramientas de IA y flujo de trabajo

- **Claude Code** con skills propias para redactar tickets, documentar cambios y preparar el QA.
- Git hooks y **GitHub Actions** que revisan los cambios antes de llegar a la rama principal.
- Pruebas con **pytest** y simuladores antes de dar nada por terminado.

<div align="center">

## 🌱 Ahora mismo

</div>

- 📚 Aprendiendo más sobre seguridad en aplicaciones web (SSO, MFA, permisos).
- 🧪 Preparando mis primeros proyectos personales para publicarlos aquí.
- 💬 ¿Quieres hablar de Django, Python o identidad? Escríbeme a <a href="mailto:rodriguezportillodavinia@gmail.com">rodriguezportillodavinia@gmail.com</a>.

<div align="center">

## 🛠️ Tecnologías

</div>

| **Categoría** | **Tecnologías** |
|---|---|
| **🌐 Lenguajes** | ![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=flat&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black) ![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-%231572B6.svg?style=flat&logo=css3&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-%23336791.svg?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-%234EAA25.svg?style=flat&logo=gnubash&logoColor=white) |
| **🖥️ Frameworks** | ![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=flat&logo=django&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-%237952B3.svg?style=flat&logo=bootstrap&logoColor=white) |
| **📦 Bases de datos** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1.svg?style=flat&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-%23DC382D.svg?style=flat&logo=redis&logoColor=white) |
| **🔐 Identidad** | ![Authentik](https://img.shields.io/badge/Authentik-%23FD4B2D.svg?style=flat&logo=authentik&logoColor=white) ![OIDC](https://img.shields.io/badge/OAuth2%20%2F%20OIDC-%23000000.svg?style=flat&logo=openid&logoColor=white) |
| **⚙️ Herramientas** | ![Git](https://img.shields.io/badge/Git-%23F05032.svg?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=flat&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat&logo=docker&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-%231F88C0.svg?style=flat&logo=caddy&logoColor=white) ![Hetzner](https://img.shields.io/badge/Hetzner-%23D50C2D.svg?style=flat&logo=hetzner&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-%230052CC.svg?style=flat&logo=jira&logoColor=white) ![DBeaver](https://img.shields.io/badge/DBeaver-%23382923.svg?style=flat&logo=dbeaver&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-%23FF6C37.svg?style=flat&logo=postman&logoColor=white) |
| **🖋️ Editores** | ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-%230078D7.svg?style=flat) ![Claude Code](https://img.shields.io/badge/Claude%20Code-%23D97757.svg?style=flat&logo=anthropic&logoColor=white) |

<table align="center">
  <tr>
    <td align="center" width="45%">
      <img width="100%" src="https://gh-readme-profile.vercel.app/api?username=daviniarodriguez&theme=neon-dark&border_width=0&border_radius=15.2&hide_border=true" alt="daviniarodriguez" />
    </td>
    <td align="center" width="55%">
      <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=daviniarodriguez&theme=2077" alt="daviniarodriguez" />
    </td>
  </tr>
</table>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=daviniarodriguez" alt="contador de visitas">
</p>
