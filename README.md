# Language Mirror · Prototype 001

## Publicarlo hoy
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html` y `course.json` a la raíz.
3. Settings → Pages → Deploy from branch → rama principal → `/ (root)`.
4. Abre la URL de GitHub Pages.

## Qué prueba este MVP
- Dos modos espejo: español→inglés e inglés→español.
- WHY contrastivo.
- Trampas de transferencia del idioma nativo.
- Mini-quiz.
- El prompt de IA incorpora automáticamente los tipos de error detectados.
- Pronunciación mediante la voz del navegador.
- Feedback y comentario libre.
- Informe copiable/exportable.

## Privacidad
No usa Dropbox ni backend.
El progreso y el feedback se guardan solo en `localStorage` del navegador.
`course.json` contiene únicamente el contenido de la lección.

## Próxima iteración
Si funciona, el siguiente paso puede ser sincronizar feedback/progreso de forma remota o mantenerlo local según lo que realmente necesitéis.
