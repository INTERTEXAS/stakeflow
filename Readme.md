# StakeFlow — Simulador de Stakeholders v3.0
### Simulador profesional de entrevistas de requerimientos de software

![Version](https://img.shields.io/badge/versión-3.0-emerald)
![License](https://img.shields.io/badge/licencia-MIT-zinc)
![AI](https://img.shields.io/badge/IA-Claude%20Sonnet-blue)

---

## Qué es esto?

Una herramienta interactiva para practicar y ejecutar **sesiones de elicitación de requerimientos de software** con stakeholders simulados por IA. Diseñada para estudiantes de Ingeniería de Software, Analistas de Requerimientos y cualquier persona que quiera mejorar sus habilidades de entrevista técnica.

## Características

- **4 casos de estudio** con 3 roles cada uno (Sponsor, Cliente, Usuario Final)
- **3 niveles de dificultad**: Cooperativo, Realista y Adversarial
- **Panel de captura en tiempo real** — captura requerimientos mientras entrevistas
- **Switch de roles** con gestión de contexto inteligente
- **Redirección dinámica** — los personajes te redirigen al stakeholder correcto según su área
- **Diseño profesional oscuro** — Interfaz optimizada basada en el sistema de diseño Zinc
- **Responsividad completa** — Uso fluido en dispositivos móviles y escritorio
- **Persistencia de API Key** en localStorage del navegador

## Casos de Estudio

| Caso | Descripción | Tensión Principal |
|------|-------------|-------------------|
| Clínica Médica | Gestión para clínica con 12 años en papel | Laura (más datos) vs Carlos (menos pasos) |
| Restaurante | Cadena de sucursales sin POS adecuado | Martín (bajo costo) vs Sofía (funcionalidad real) |
| Universidad | Plataforma académica para 8,000 alumnos | Elena (visión) vs Gómez (migración compleja) |
| Gimnasio | Centro con fraudes y accesos no controlados | Alejandro (reducir personal) vs Valeria (calidad) |

## Cómo usar

### Opción 1 — Directo en el navegador
1. Descarga `index.html`
2. Ábrelo en cualquier navegador moderno
3. Ingresa tu API Key de Anthropic
4. Empieza a practicar

### Opción 2 — Clonar el repositorio
```bash
git clone https://github.com/INTERTEXAS/stakeflow.git
cd stakeflow
# Abrir index.html en el navegador
```

## API Key

Necesitas una API Key de Anthropic:
1. Ve a [console.anthropic.com](https://console.anthropic.com)
2. Crea una cuenta y genera una API Key
3. La key se guarda solo en tu navegador (localStorage)

## Comandos durante la sesión

| Comando | Acción |
|---------|--------|
| Panel de Stakeholders | Cambia de personaje para obtener diferentes perspectivas |
| Botón + REQUISITO | Captura el requerimiento directamente desde el chat |
| Generar IEEE 830 | Prepara la base para tu documento formal |
| Evaluación | Recibe feedback sobre tu desempeño como analista |

## Stack Técnico

- **Frontend**: HTML5 + CSS3 (Zinc Dark Theme) + JavaScript Vanilla
- **Iconografía**: Lucide Icons
- **Tipografía**: Geist + JetBrains Mono
- **IA**: Claude 3.5 Sonnet via Anthropic API

## Estructura del Proyecto

```
stakeflow/
├── index.html    # Aplicación completa
└── README.md     # Documentación
```

## Licencia

MIT — Úsalo, modifícalo y compártelo libremente.

---
Construido para la comunidad de Ingeniería de Software