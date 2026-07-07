# Tracking-food 🥗

App web personal para seguir mi plan de alimentación semanal (elaborado por mi nutricionista).

**Es de uso local/personal** — no está pensada para publicarse como producto ni para otros usuarios: los datos del plan están embebidos en el propio HTML y el progreso se guarda solo en el dispositivo (localStorage).

## Qué hace

- **Hoy**: las 5 comidas del día con horarios, resaltando la que corresponde según la hora, con check de "cumplida" y anillo de progreso diario.
- **Semana**: la grilla completa Lunes–Domingo del plan.
- **Notas**: aclaraciones del nutricionista + botón para descargar el plan como calendario (`.ics`) con recordatorios en cada horario de comida.

## Uso en iPhone

1. Abrir la URL de GitHub Pages en Safari.
2. Compartir → **Agregar a pantalla de inicio**.
3. Se instala como web app standalone (pantalla completa, ícono propio).

## Stack

Un solo `index.html` sin dependencias: HTML + CSS + JavaScript vanilla (Web Animations API para las animaciones). Tema claro/oscuro automático según el sistema.
