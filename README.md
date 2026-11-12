# Mesa de decisiones

Herramienta web local para organizar ideas y comparar alternativas de nuestros proyectos. Permite guardar una decisión, sus objetivos, opciones, criterios y datos pendientes en el navegador, y preparar un texto de contexto para analizarla con un asistente.

## Problema y alcance

Las ideas aparecen en distintas conversaciones y es fácil perder qué se comparó y qué quedó por decidir. Esta primera versión reúne esas notas en una ficha, sin tomar decisiones por Iván.

## Objetivos verificables

- Antes de cerrar el curso, crear una ficha con tema y alternativas desde el navegador.
- Al guardar, conservarla tras recargar la página en el mismo navegador y dispositivo.
- Probar entrada vacía y una ficha válida; ofrecer exportación local para respaldo.

## Uso

Abrir `index.html` en un navegador moderno. Completar el tema, objetivo, alternativas, criterios y pendientes. Guardar, revisar las fichas y copiar el contexto para trabajar con IA. El botón Exportar descarga un JSON local como respaldo.

## Límites y tecnologías

HTML, CSS y JavaScript sin dependencias. Los datos se guardan en localStorage del navegador; no sincronizan entre dispositivos y pueden perderse al borrar datos del navegador. Esta versión no consulta IA ni conecta n8n automáticamente, no tiene usuarios, pagos ni base de datos remota. No cargar claves ni información sensible. El contexto generado debe revisarse antes de compartirlo.

El desarrollo aplica ciclos de instrucciones, implementación y pruebas de Vibe Coding. La documentación de alcance está en `docs/alcance.md` y el contexto de trabajo en `ai-context.md`.

