# 🎭 StakeFlow — Simulador de Stakeholders v3.0
### Simulador profesional de entrevistas de requerimientos de software

![Version](https://img.shields.io/badge/versión-3.0-cyan)
![License](https://img.shields.io/badge/licencia-MIT-green)
![AI](https://img.shields.io/badge/IA-Claude%20Sonnet-purple)

---

## ¿Qué es esto?

Una herramienta interactiva para practicar y ejecutar **sesiones de elicitación de requerimientos de software** con stakeholders simulados por IA. Diseñada para estudiantes de Ingeniería de Software, Analistas de Requerimientos y cualquier persona que quiera mejorar sus habilidades de entrevista técnica.

## ✨ Características

- 🎭 **4 casos de estudio** con 3 roles cada uno (Sponsor, Cliente, Usuario Final)
- 🧠 **3 niveles de dificultad**: Cooperativo, Realista y Adversarial
- 📋 **Panel de captura en tiempo real** — captura requerimientos mientras entrevistas
- 🔄 **Switch de roles** con borrado de memoria (sandbox)
- 🏃 **La Patada** — los personajes te redirigen al stakeholder correcto
- 📄 **Generador IEEE 830** con matriz de trazabilidad y diagrama de tensiones
- 📊 **Evaluador de sesión** con puntaje, métricas y consejos personalizados
- 💾 **Persistencia de API Key** en localStorage del navegador

## 🏢 Casos de Estudio

| Caso | Descripción | Tensión Principal |
|------|-------------|-------------------|
| 🏥 Clínica Médica | Sistema de gestión para clínica con 12 años en papel | Laura (más datos) vs Carlos (menos pasos) |
| 🍽️ Restaurante | Cadena de 3 sucursales sin POS adecuado | Martín (bajo costo) vs Sofía (funcionalidad real) |
| 🎓 Universidad | Plataforma académica para 8,000 alumnos | Elena (visión) vs Gómez (migración compleja) |
| 💪 Gimnasio | Centro de bienestar con fraudes y accesos no controlados | Alejandro (reducir personal) vs Valeria (calidad de servicio) |

## 🚀 Cómo usar

### Opción 1 — Directo en el navegador
1. Descarga `index.html`
2. Ábrelo en cualquier navegador moderno
3. Ingresa tu API Key de Anthropic
4. ¡Empieza a practicar!

### Opción 2 — Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/stakeflow.git
cd stakeflow
# Abrir index.html en el navegador — no requiere servidor
```

### Opción 3 — Vercel (Demo en vivo)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/tu-usuario/stakeflow)

## 🔑 API Key

Necesitas una API Key de Anthropic:
1. Ve a [console.anthropic.com](https://console.anthropic.com)
2. Crea una cuenta (incluye $5 USD de crédito gratis)
3. Genera una API Key en la sección "API Keys"
4. Cada sesión cuesta aproximadamente $0.01–$0.03 USD

> ⚠️ Tu API Key se guarda solo en tu navegador (localStorage). Nunca se envía a servidores externos.

## 🎮 Comandos durante la sesión

| Comando | Acción |
|---------|--------|
| Botón **Cambiar Rol** | Cambia de personaje con borrado de memoria |
| Botón **+ REQ** en respuestas | Captura el requerimiento directamente |
| **Generar IEEE 830** | Genera documento formal con tus requerimientos |
| **Evaluar Sesión** | Recibe puntaje y feedback de tu desempeño |
| **Nueva Sesión** | Reinicia todo |

## 📄 Salida IEEE 830

El documento generado incluye:
- Introducción y alcance del sistema
- Descripción general del producto
- Requisitos Funcionales (RF-001, RF-002...)
- Requisitos No Funcionales (RNF-001...)
- Requisitos implícitos detectados `[IMPLÍCITO — REQUIERE VALIDACIÓN]`
- Áreas no cubiertas `[NO ELICITADO]`
- **Matriz de trazabilidad** (tabla Markdown)
- **Diagrama de tensiones** (código Mermaid)

## 🛠️ Stack Técnico

- **Frontend**: HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- **IA**: Claude Sonnet via Anthropic API
- **Fonts**: Syne + JetBrains Mono (Google Fonts)
- **Almacenamiento**: localStorage del navegador
- **Despliegue**: Cualquier hosting estático (Vercel, Netlify, GitHub Pages)

## 📁 Estructura del Proyecto

```
stakeflow/
└── index.html    ← App completa en un solo archivo
└── README.md     ← Este archivo
```

## 🤝 Contribuciones

¿Quieres agregar nuevos casos de estudio o mejorar los perfiles existentes? Las PRs son bienvenidas.

1. Fork el repositorio
2. Crea una rama: `git checkout -b feature/nuevo-caso`
3. Commit: `git commit -m 'Agrega caso: Banco Digital'`
4. Push: `git push origin feature/nuevo-caso`
5. Abre un Pull Request

## 📝 Licencia

MIT — Úsalo, modifícalo y compártelo libremente.

---

Construido con ❤️ para la comunidad de Ingeniería de Software