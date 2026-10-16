# Revisión de simuladores · 2ª convocatoria 2026

Revisiones pregunta por pregunta de los simuladores de Brillium para que los alumnos repasen: cuántos contestaron mal, qué eligieron, en qué se equivocaron, cómo cachar el error y el fundamento real. Sólo porcentajes del grupo, sin resultados individuales.

## Estructura

```
index.html                      ← portada: el alumno elige el módulo
modulo-1/simulador-2/index.html ← Módulo 1 · Simulador 2 · Área 1
modulo-2/simulador-2/index.html ← Módulo 2 · Simulador 2 · Área 2
modulo-3/simulador-2/index.html ← Módulo 3 · Simulador 2 · Área 3
```

## Cómo agregar una revisión desde otro proyecto

1. En el proyecto del módulo, usa la skill `revision-simulador-360educa` con el reporte de Brillium.
2. Guarda la página en `modulo-N/simulador-X/index.html` (por ejemplo `modulo-1/simulador-2/index.html`).
3. El enlace «← Elegir módulo» de la página debe apuntar a `../../index.html`.
4. En `index.html` (portada), cambia «Próximamente» del módulo por un enlace a su revisión, con el mismo formato de la tarjeta del Módulo 3.
