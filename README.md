# 👋 Hola, soy Carlos Arnanz

**Desarrollador de software.** Me gusta construir herramientas que funcionen de verdad y que se puedan usar sin instalar nada: apps web estáticas, utilidades de escritorio y stacks completos con backend y base de datos.

Todos mis proyectos son **open source** y están en [github.com/carlosarnu](https://github.com/carlosarnu). Cuando algo es una app web, la dejo **desplegada para que se pueda probar desde el navegador** sin instalar nada.

## 🚀 Proyectos

| Proyecto | Descripción | Pruebas |
|---|---|---|
| [🧹 **Space Cleaner**](https://github.com/carlosarnu/space-cleaner) | App de escritorio para Windows que indexa todos tus archivos y te ayuda a liberar espacio, con recomendaciones que explican el porqué (PowerShell + interfaz web local, sin dependencias) | [Código](https://github.com/carlosarnu/space-cleaner) |
| [👥 **Gestor de Clientes**](https://github.com/carlosarnu/gestor-de-clientes) | Gestión de clientes con filtros múltiples por tipo y provincia, listado, impresión/PDF y app de escritorio Electron | [**Demo**](https://carlosarnu.github.io/gestor-de-clientes/) · [Código](https://github.com/carlosarnu/gestor-de-clientes) |
| [📚 **Diario de Estudio**](https://github.com/carlosarnu/MyStudyDiary) | Registro de sesiones de estudio con racha, mapa de calor, objetivo semanal y buscador | [**Demo**](https://carlosarnu.github.io/MyStudyDiary/) · [Código](https://github.com/carlosarnu/MyStudyDiary) |
| [🎓 **Proyecto Symfony + Angular**](https://github.com/carlosarnu/Proyecto_Symfony_Angular) | Backend Symfony 7 (PHP 8.3) + frontend Angular 20 + PostgreSQL con Docker | [Código](https://github.com/carlosarnu/Proyecto_Symfony_Angular) |

## 🧰 Tecnologías

- **Frontend:** HTML5, CSS3, JavaScript (vanilla), Angular
- **Backend:** PHP (Symfony), Node.js, PowerShell
- **Escritorio:** Electron
- **Datos:** PostgreSQL, `localStorage`, archivos JSON
- **Infraestructura y herramientas:** Docker, Git, GitHub Actions, GitHub Pages

## ✅ Cómo trabajo

- **Tests primero.** La lógica pura va separada de la interfaz y se prueba con el runner nativo de Node (`node --test`). Cada proyecto lleva su badge de CI en verde: la prueba de que el código funciona está en el propio repositorio.
- **Especificación antes que código.** Sigo Spec-Driven Development: especifico, planifico, implemento y verifico. Las specs quedan documentadas en `specs/`.
- **Sin dependencias de más.** Cuando basta con HTML/CSS/JS puro, no meto frameworks ni build. Menos piezas que se rompan.
- **Privacidad.** Mis apps guardan los datos en tu propio equipo; no hay servidores ni cuentas de por medio.

## 🤖 Desarrollo asistido con agentes de IA

Desarrollo con **agentes de IA** como parte de mi flujo de trabajo, siguiendo **Spec-Driven Development**. En cada proyecto:

- **El agente de IA** implementa a partir de la especificación y escribe/ejecuta los tests.
- **Yo** defino los requisitos, tomo las decisiones de diseño y de modelo de datos, reviso cada cambio y valido el resultado final (incluida la verificación visual y las pruebas manuales en un equipo real).

Puedes ver el flujo completo en los archivos `AGENTS.md` y `MEMORY.md` de cada repositorio, y las especificaciones en `specs/`.

## 📫 Contacto

- **GitHub:** [carlosarnu](https://github.com/carlosarnu)

> 💡 Todas las apps web anteriores tienen **demo desplegada con GitHub Pages**: haz clic en «Demo» y pruébalas al instante.
