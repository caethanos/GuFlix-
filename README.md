# Study Garden — plataforma de estudios

Plataforma estática de una sola página con trilhas de inglés A1 y español. Las unidades de español 05 (Salud y Bienestar) y 06 (Las Finanzas) combinan el catálogo visual de trilhas del HTML de referencia con el formato pedagógico y los temas del archivo de instrucciones.

## Contenido y funciones

- Flashcards, quiz de opción múltiple, desafíos situacionales y escritura libre.
- Inglés A1 y español: salud según la OMS, estrés y técnicas de relajación, diminutivos afectivos, historia del dinero, trueque, divisas digitales, ahorro e intereses.
- Las preguntas de español siguen una estructura con `unit_id`, opciones marcadas, explicación, error común y sugerencia visual.
- Revisión de preguntas falladas, selección de módulos, XP, racha y registro de etapas en `localStorage`.
- La corrección generativa todavía no está conectada; la práctica escrita usa las respuestas y reglas incluidas en el archivo.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube `index.html` a la raíz.
2. Abre **Settings → Pages**.
3. Elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`; pulsa **Save**.
4. Abre la dirección que GitHub muestre en Pages cuando termine la publicación.

## Publicar en Netlify

1. Conecta Netlify con tu cuenta de GitHub.
2. Selecciona **Add new site → Import an existing project** y elige el repositorio.
3. Deja vacío **Build command** y usa `.` como **Publish directory**.
4. Pulsa **Deploy site**. También puedes publicar manualmente arrastrando la carpeta que contiene `index.html`.

El avance se guarda en el navegador y no se sincroniza entre dispositivos. La integración de Supabase/IA requerirá configurar el proyecto y sus credenciales por separado.

## Modo intensivo

El quiz abre primero una pantalla de preparación con la explicación y un ejemplo del módulo antes de cada pregunta. En modo intensivo, una respuesta incorrecta devuelve al alumno a la explicación y no permite avanzar hasta acertar. La plataforma registra las preguntas dominadas y muestra el avance por módulo. El alumno puede cambiar al modo directo cuando quiera.


Banco actual: 30 preguntas en cada una de las cuatro unidades de inglés (120 en total), más 11 preguntas en las dos unidades de español. Las cuatro unidades de inglés suman 120 preguntas de quiz.
