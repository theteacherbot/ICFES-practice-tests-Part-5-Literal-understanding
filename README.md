# Prompt para IA Agéntica

# Exam Engine 2.0

## Part 05 -- Literal Comprehension Offline App

### Archivo: `part05-literal-comprehension-offline-50-exams.prompt.md`

### Versión 3.0 -- Offline

### Compatible con ExamJSON v2.0

---

# CONTEXTO

Actúa como un equipo multidisciplinario de arquitectura de software,
React, UX/UI, lingüística, evaluación ICFES, accesibilidad y desarrollo
frontend para construir una **APP 100 % OFFLINE** de práctica de la
**Parte 5 -- Literal Comprehension** del examen de Inglés Saber 11 (ICFES).

El objetivo es crear una aplicación educativa autónoma que incluya desde
su instalación un **banco local de exactamente 50 exámenes completos**.

Todo el contenido debe ser **100 % original**, manteniendo la estructura,
el nivel de dificultad y la competencia de comprensión literal.

---

# REGLA ABSOLUTA: OFFLINE

La aplicación debe funcionar completamente sin conexión a Internet.

## ELIMINAR POR COMPLETO

- API Keys.
- Botón de configuración de API Key.
- Modal de API Key.
- Pollinations API.
- OpenAI API.
- Cualquier API externa.
- Supabase.
- Firebase.
- Cualquier backend remoto.
- `fetch()` hacia servicios externos.
- Generación automática de preguntas mediante IA online.
- Generación automática de imágenes mediante IA online.
- Google Fonts.
- CDNs.
- Recursos externos.
- Servicios de autenticación.
- Servicios de analítica remota.
- Sincronización con servidores.

**No debe existir ninguna funcionalidad que requiera Internet.**

Todo el contenido necesario para ejecutar los 50 exámenes debe estar
incluido dentro del proyecto.

---

# OBJETIVO GENERAL

Construir una aplicación educativa offline que permita al estudiante:

1. Consultar un banco de 50 exámenes.
2. Seleccionar cualquier examen.
3. Leer el texto.
4. Resolver las preguntas.
5. Navegar entre preguntas.
6. Cambiar respuestas antes de finalizar.
7. Finalizar el examen.
8. Obtener el puntaje.
9. Revisar respuestas correctas e incorrectas.
10. Repetir el examen.
11. Consultar su progreso local.

La aplicación debe utilizar **ExamJSON v2.0** para estructurar el
contenido.

---

# COMPETENCIA EVALUADA

Evaluar exclusivamente **Literal Comprehension**.

La aplicación debe evaluar la capacidad para:

- Localizar información explícita.
- Identificar hechos y detalles.
- Reconocer personajes.
- Reconocer lugares.
- Reconocer fechas.
- Identificar secuencias.
- Encontrar información específica.
- Identificar datos directamente expresados en la lectura.

## NO EVALUAR

Nunca formular preguntas que dependan principalmente de:

- Inferencias profundas.
- Opinión personal.
- Interpretación subjetiva.
- Gramática.
- Traducción.
- Vocabulario aislado sin relación con la lectura.

La respuesta correcta de cada pregunta debe poder encontrarse
explícitamente en el texto.

---

# NIVEL LINGÜÍSTICO

Utilizar exclusivamente:

- A2
- A2+
- B1

Distribuir los niveles de manera equilibrada a lo largo de los 50
exámenes.

---

# BANCO LOCAL DE 50 EXÁMENES

La aplicación debe incluir **EXACTAMENTE 50 EXÁMENES** desde la primera
ejecución.

No crear 5 exámenes iniciales para después generar otros.

No utilizar generación dinámica para completar el banco.

Los 50 exámenes deben existir físicamente dentro del proyecto como datos
locales.

## DISTRIBUCIÓN

Crear 10 temáticas con 5 exámenes cada una:

### 1. Daily Life
- Exam 01
- Exam 02
- Exam 03
- Exam 04
- Exam 05

### 2. Education
- Exam 06
- Exam 07
- Exam 08
- Exam 09
- Exam 10

### 3. Technology
- Exam 11
- Exam 12
- Exam 13
- Exam 14
- Exam 15

### 4. Environment
- Exam 16
- Exam 17
- Exam 18
- Exam 19
- Exam 20

### 5. Travel
- Exam 21
- Exam 22
- Exam 23
- Exam 24
- Exam 25

### 6. Health
- Exam 26
- Exam 27
- Exam 28
- Exam 29
- Exam 30

### 7. Culture
- Exam 31
- Exam 32
- Exam 33
- Exam 34
- Exam 35

### 8. Science
- Exam 36
- Exam 37
- Exam 38
- Exam 39
- Exam 40

### 9. Sports
- Exam 41
- Exam 42
- Exam 43
- Exam 44
- Exam 45

### 10. Nature & Wildlife
- Exam 46
- Exam 47
- Exam 48
- Exam 49
- Exam 50

---

# ESTRUCTURA DE CADA EXAMEN

Cada uno de los 50 exámenes debe contener:

- Un título.
- Una temática.
- Un nivel A2, A2+ o B1.
- Una dificultad.
- Una lectura original en inglés.
- Una imagen local opcional.
- Un Ejemplo 0.
- Exactamente 10 preguntas calificables.
- Cuatro opciones por pregunta: A, B, C y D.
- Una única respuesta correcta por pregunta.

---

# LONGITUD DE LAS LECTURAS

- Mínimo: 300 palabras.
- Recomendado: 300-320 palabras.
- Máximo: 350 palabras.

Las lecturas deben utilizar lenguaje apropiado para A2, A2+ o B1.

Deben presentar situaciones y textos naturales relacionados con la
temática correspondiente.

---

# EJEMPLO 0

Cada examen debe incluir automáticamente un **Ejemplo 0**.

Características:

- No calificable.
- Respuesta correcta visible.
- Sirve para explicar al estudiante cómo responder.
- Tiene exactamente cuatro opciones A-D.
- Debe basarse en información explícita de la lectura.
- Debe tener la misma apariencia visual de las demás preguntas.
- No suma puntos.

Después del Ejemplo 0 comienzan las 10 preguntas calificables.

---

# PREGUNTAS

Cada examen debe contener exactamente **10 preguntas calificables**.

Numeración:

- Ejemplo 0 -- no calificable.
- Pregunta 1.
- Pregunta 2.
- Pregunta 3.
- Pregunta 4.
- Pregunta 5.
- Pregunta 6.
- Pregunta 7.
- Pregunta 8.
- Pregunta 9.
- Pregunta 10.

Cada pregunta tendrá exactamente tres opciones:

- A.
- B.
- C.

Debe existir una única respuesta correcta.

Las preguntas deben comprobar información que aparece explícitamente en
la lectura.

---

# TIPOS DE PREGUNTAS PERMITIDOS

Utilizar preguntas como:

- Who...?
- Where...?
- When...?
- What...?
- Which...?
- How many...?
- What happened first...?
- What did [person] do...?
- Where did [person] go...?
- What was [object/person/place] like...?

Evitar preguntas que requieran interpretar intenciones ocultas o realizar
inferencias complejas.

---

# DISTRACTORES

Los distractores deben:

- Ser gramaticalmente posibles.
- Ser plausibles.
- Relacionarse con información presente en la lectura.
- Ser claramente incorrectos cuando se compara la opción con el texto.
- No introducir información que convierta dos opciones en correctas.

Nunca crear dos respuestas correctas.

---

# REGLA DE ORIGINALIDAD

Los 50 exámenes deben ser diferentes.

No reutilizar:

- Lecturas.
- Preguntas.
- Conjuntos de opciones.
- Respuestas.
- Historias.
- Personajes de forma que produzcan duplicación evidente.

Cada examen debe funcionar como una unidad independiente.

---

# ARQUITECTURA OFFLINE

La aplicación debe ser frontend y autocontenida.

Tecnologías sugeridas:

- React.
- JavaScript o TypeScript.
- CSS local.
- JSON local.
- `localStorage` o `IndexedDB`.

## ESTRUCTURA SUGERIDA

```text
src/
├── data/
│   └── part05/
│       ├── exam-001.json
│       ├── exam-002.json
│       ├── exam-003.json
│       ├── ...
│       └── exam-050.json
│
├── components/
│   ├── LiteralReadingRenderer
│   ├── ExamBank
│   ├── ExamCard
│   ├── ReadingTitle
│   ├── ReadingImage
│   ├── ReadingBody
│   ├── QuestionCard
│   ├── OptionsList
│   ├── ExampleCard
│   ├── Instructions
│   ├── ProgressBar
│   ├── ResultsPanel
│   └── ReviewPanel
│
├── services/
│   └── localStorageService
│
└── App
```

---

# DATOS LOCALES

Cada examen puede almacenarse como un archivo JSON independiente.

Ejemplo:

```text
exam-001.json
exam-002.json
...
exam-050.json
```

También se permite utilizar un único archivo local con los 50 exámenes,
siempre que la arquitectura mantenga cada examen como una entidad
independiente.

No cargar los exámenes desde Internet.

---

# PERSISTENCIA LOCAL

Utilizar `localStorage` o `IndexedDB` para almacenar únicamente datos del
usuario, por ejemplo:

- Exámenes realizados.
- Respuestas.
- Puntajes.
- Tiempo empleado.
- Mejor resultado.
- Promedio.
- Último intento.

No enviar estos datos a servidores.

---

# FUNCIONES DE LA APP

## PANTALLA INICIAL

Mostrar:

- Nombre de la aplicación.
- "Part 5 -- Literal Comprehension".
- "50 Offline Exams".
- Botón "Start".
- Botón "Exam Bank".
- Estadísticas locales.

---

# BANCO DE EXÁMENES

Mostrar los 50 exámenes mediante tarjetas o una lista organizada.

Cada tarjeta debe mostrar:

- Número.
- Título.
- Temática.
- Nivel.
- Dificultad.
- Estado de progreso.
- Mejor resultado.

Permitir:

- Buscar.
- Filtrar por temática.
- Filtrar por nivel.
- Filtrar por dificultad.
- Ordenar por número.

---

# PANTALLA DEL EXAMEN

Diseñar una interfaz clara y académica.

Debe incluir:

- Título de la lectura.
- Temática.
- Nivel.
- Texto completo.
- Imagen local opcional.
- Instrucciones.
- Ejemplo 0.
- Preguntas 1-10.
- Opciones A-C.
- Indicador de progreso.
- Botones Previous / Next.
- Botón Finish.

La lectura debe permanecer fácilmente visible mientras el estudiante
responde.

---

# CALIFICACIÓN

Al finalizar:

- Calcular respuestas correctas.
- Calcular respuestas incorrectas.
- Calcular porcentaje.
- Mostrar puntaje.
- Mostrar estado de cada pregunta.
- Permitir revisar las respuestas.
- Permitir volver al banco.
- Permitir repetir el examen.

El Ejemplo 0 nunca debe incluirse en el puntaje.

---

# ESTADÍSTICAS LOCALES

Mostrar:

- Exámenes realizados.
- Preguntas respondidas.
- Respuestas correctas.
- Porcentaje global.
- Mejor resultado.
- Promedio.
- Último examen realizado.

Toda esta información debe permanecer en el dispositivo.

---

# IMÁGENES

Las imágenes son opcionales.

Si se utilizan:

- Deben ser locales.
- Deben estar dentro del proyecto.
- Deben tener nombres de archivo estables.
- No deben cargarse desde URLs externas.
- No deben generarse mediante APIs.

Ejemplo:

```text
public/
└── images/
    └── part05/
        ├── exam-001.webp
        ├── exam-002.webp
        └── ...
```

Si una lectura no necesita imagen, no incluir una imagen artificialmente.

---

# COMPONENTE REACT

Utilizar:

`LiteralReadingRenderer`

Subcomponentes:

- `ReadingTitle`
- `ReadingImage`
- `ReadingBody`
- `QuestionCard`
- `OptionsList`
- `ExampleCard`
- `Instructions`
- `ProgressBar`
- `ResultsPanel`
- `ReviewPanel`
- `Toolbar`

---

# EXAMJSON v2.0

Cada examen debe ser compatible con ExamJSON v2.0.

Ejemplo mínimo:

```json
{
  "part": 5,
  "metadata": {
    "examNumber": 3,
    "topic": "Science",
    "bank": "Part 05 Offline",
    "level": "A2+",
    "competency": "Literal Comprehension",
    "difficulty": "Medium"
  }
}
```

El objeto completo debe incluir además la lectura, el Ejemplo 0, las 10
preguntas, las cuatro opciones de cada pregunta y las respuestas
correctas.

---

# VALIDACIONES

Antes de entregar la aplicación verificar automáticamente:

- El banco contiene exactamente 50 exámenes.
- Los exámenes están numerados del 01 al 50.
- Existen 5 exámenes por cada una de las 10 temáticas.
- Cada examen tiene una lectura.
- Cada lectura tiene entre 300 y 350 palabras.
- Cada examen tiene exactamente 10 preguntas calificables.
- Cada examen tiene un Ejemplo 0.
- Cada pregunta tiene exactamente tres opciones A-C.
- Cada pregunta tiene una única respuesta correcta.
- La respuesta correcta aparece explícitamente en la lectura.
- No hay preguntas duplicadas.
- No hay lecturas duplicadas.
- Los niveles son A2, A2+ o B1.
- No existen llamadas a APIs externas.
- No existen URLs externas para contenido esencial.
- No existen dependencias CDN.
- La APP funciona sin conexión.

---

# PRUEBA DE OFFLINE

Antes de considerar terminado el proyecto:

1. Desactivar la conexión a Internet.
2. Abrir la aplicación.
3. Comprobar que aparece el banco de 50 exámenes.
4. Abrir al menos tres exámenes diferentes.
5. Resolver preguntas.
6. Finalizar un examen.
7. Verificar la calificación.
8. Revisar respuestas.
9. Cerrar y volver a abrir la aplicación.
10. Comprobar que las estadísticas locales permanecen disponibles.

Si alguna función falla sin Internet, corregirla antes de entregar.

---

# EXPORTACIONES

Las exportaciones son opcionales.

Si se implementan, deben funcionar sin Internet.

Formatos posibles:

- ExamJSON v2.0.
- JSON.
- HTML.
- Markdown.
- PDF mediante generación local.

No utilizar servicios externos para convertir archivos.

---

# DISEÑO UX/UI

La interfaz debe ser:

- Moderna.
- Limpia.
- Académica.
- Responsive.
- Accesible.
- Fácil de usar.
- Adecuada para estudiantes de secundaria.

Utilizar:

- Tarjetas.
- Barra de progreso.
- Estados visuales.
- Tipografía legible.
- Buen contraste.
- Botones grandes.
- Navegación sencilla.

No sacrificar la legibilidad del texto por elementos decorativos.

---

# RESTRICCIONES TÉCNICAS

No utilizar:

- APIs.
- Backend.
- Base de datos remota.
- Servicios de IA online.
- CDN.
- Recursos externos.
- Autenticación online.
- Analítica online.

La aplicación debe ser autocontenida.

---

# CRITERIO DE ÉXITO

Entregar una **APP profesional, responsive y 100 % offline** para practicar
la **Parte 5 -- Literal Comprehension** de Saber 11.

La aplicación debe:

1. Incluir exactamente **50 exámenes completos**.
2. Tener los 50 exámenes disponibles desde la primera ejecución.
3. Organizar los exámenes en 10 temáticas con 5 exámenes cada una.
4. Contener lecturas originales.
5. Incluir un Ejemplo 0 resuelto y no calificable.
6. Incluir exactamente 10 preguntas calificables por examen.
7. Utilizar cuatro opciones A-D.
8. Evaluar exclusivamente comprensión literal.
9. Calificar automáticamente.
10. Mostrar revisión de respuestas.
11. Guardar estadísticas localmente.
12. Utilizar ExamJSON v2.0.
13. Utilizar `LiteralReadingRenderer`.
14. Funcionar sin Internet.
15. No solicitar API Keys.
16. No utilizar Pollinations.
17. No utilizar ninguna API externa.
18. No generar preguntas o imágenes mediante servicios externos durante
    la ejecución.

## PRIORIDAD FINAL

**OFFLINE > BANCO LOCAL DE 50 EXÁMENES > FUNCIONALIDAD > DISEÑO**

La aplicación no debe depender de Internet para ninguna función esencial.
