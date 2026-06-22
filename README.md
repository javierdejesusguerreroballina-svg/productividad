# Impulso Productivo — JavierWarrior

App web de productividad basada en psicología del rendimiento.  
Parte de [javierwarrior.com](https://javierwarrior.com)

## Descripción

Timer de sesiones de trabajo con tres modos diseñados desde la neurociencia del foco y la fatiga mental:

- **Modo Rush** — Ejecución urgente con presión sonora y mensajes de activación. Para tareas con entrega definida y tiempo limitado.
- **Modo Flow** — Trabajo profundo con ruido marrón de fondo para facilitar el estado de flujo. Sin interrupciones, sin urgencia.
- **Modo Reunión** — Gestión de juntas con timer y registro de distracciones y aportes.

## Características

- 100% HTML, CSS y JavaScript puro — sin dependencias ni frameworks
- Funciona offline una vez cargada
- Audio generado en tiempo real (Web Audio API)
- Wake Lock para mantener la pantalla activa durante sesiones
- Historial de sesiones en localStorage
- Optimizada para móvil

## Estructura

```
/
├── index.html       # App completa
├── README.md        # Este archivo
├── LICENSE          # Licencia MIT
└── .gitignore       # Archivos ignorados por Git
```

## Tecnologías

- HTML5 / CSS3 / JavaScript ES6+
- Web Audio API (generación de sonido)
- Screen Wake Lock API
- localStorage (historial)
- Google Fonts (Playfair Display + Lato)
- Cloudflare Pages (hosting)

## Despliegue

Cada push a la rama `main` despliega automáticamente vía Cloudflare Pages.

## Parte de

- [javierwarrior.com](https://javierwarrior.com) — Landing page
- [Calma Vital](https://github.com/javierdejesusguerreroballina-svg/calmavital) — Primeros auxilios neurobiológicos
- [Mind Zen](https://github.com/javierdejesusguerreroballina-svg/mindzen30puertas) — Técnicas de mindfulness

## Autor

Javier Guerrero Ballina — Zapopan, Jalisco, México  
[javierwarrior.com](https://javierwarrior.com)
