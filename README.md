Proyecto Grupal Fundamentos de HTML y CSS
Descripción General
 Proyecto grupal (3-4 personas)
 Tecnologías: HTML y CSS (sin JavaScript)
 Objetivo: Crear una web multipágina con navegación interna (navbar)
con temática libre, a consultar con los profesores.
Páginas obligatorias
La aplicación debe incluir al menos 4 páginas HTML conectadas entre sí:
 index.html → Página principal (Home)
 servicios.html → Servicios o Productos (debe incluir una tabla)
 equipo.html → Equipo/Staff
 sobre.html → Sobre nosotros (About us)
 contacto.html → Formulario de contacto
Importante: Usar etiquetas semánticas
(<header>, <main>, <section>, <article>, <footer>), imágenes con
atributo alt, enlaces internos y etiquetas de formulario con su label
correspondiente.
Estructura mínima del proyecto
/
├─ index.html (Home)
├─ servicios.html (o productos.html)
├─ equipo.html
├─ sobre.html
├─ contacto.html
├─ styles.css (hoja de estilos compartida)
├─ README.md
└─ /images (imágenes estáticas)
Checklist HTML
Estructura y semántica
 [ ] La aplicación incluye las 5 páginas mínimas (Home, Servicios, Equipo,
Sobre, Contacto)
 [ ] Estructura semántica clara con
etiquetas <header>, <main>, <section>, <article>, <footer>
 [ ] Uso de <section> para agrupar contenido relacionado
 [ ] Uso de <article> para contenido independiente (ej: tarjetas de
equipo, servicios individuales)
Listas, enlaces e imágenes
 [ ] Uso de listas (<ul>, <ol>, <li>) donde sea apropiado
 [ ] Navbar funcional con enlaces (<a>) a todas las páginas
 [ ] Enlaces internos y externos funcionan correctamente
Tablas
 [ ] Al menos una tabla con estructura
correcta: <table>, <thead>, <tbody>, <tr>, <th>, <td>
 [ ] La tabla debe tener sentido semántico (ej: comparación de servicios,
horarios, precios)
Formularios (elementos diversos)
El formulario de la página contacto.html debe incluir:
 [ ] Campos de texto: <input type="text"> y <textarea>
 [ ] Campo de email: <input type="email">
 [ ] Campo numérico o teléfono: <input type="tel"> o <input
type="number">
 [ ] Radio buttons: <input type="radio"> (mínimo 2 opciones)
 [ ] Checkboxes: <input type="checkbox"> (mínimo 1)
 [ ] Select/dropdown: <select> con múltiples <option>
 [ ] Botón de envío: <button type="submit"> o <input
type="submit">
Accesibilidad básica
Imágenes
 [ ] Todas las imágenes tienen atributo alt descriptivo
 [ ] El texto alternativo describe el contenido o función de la imagen
Formularios
 [ ] Cada <input>, <textarea> y <select> tiene
su <label> asociado
 [ ] Asociación correcta mediante atributos for (en label) e id (en input)
 [ ] Los labels son descriptivos y claros
Ejemplo correcto:
<label for="nombre">Nombre completo:</label>
<input type="text" id="nombre" name="nombre">
Encabezados
 [ ] Solo un <h1> por página
 [ ] Jerarquía clara y sin saltos: H1 → H2 → H3 (nunca H1 → H3)
 [ ] Los encabezados estructuran el contenido de forma lógica
Enlaces
 [ ] Los textos de los enlaces son descriptivos (evitar "click aquí")
 [ ] Los enlaces se distinguen visualmente del texto normal
Requisitos de CSS
 Una sola hoja de estilos externa: styles.css (compartida por todas
las páginas)
 Prohibido CSS inline → todo el estilo debe estar en la hoja externa
 Sin frameworks CSS (ni Bootstrap, ni Tailwind)
Fase 1: CSS básico
Permitido:
 Selectores: elemento, clase, id
 Propiedades básicas: color, background-color, font-size, font-family, textalign, etc.
 Modelo de caja: margin, padding, border, width, height
 Display: block, inline, inline-block
 Unidades: px, %, rem
Fase 2: Flexbox + responsive
 Flexbox (display: flex, justify-content, alignitems, gap, flex-wrap, etc.)
 Responsive básico (@media, layouts para móvil y desktop)
Mantener el diseño sencillo y enfocado en practicar los fundamentos (primero
estructura, luego layout).
Checklist CSS
Configuración básica
 [ ] Hoja externa styles.css enlazada desde todas las páginas HTML
mediante <link>
 [ ] Sin estilos inline en ninguna página
 [ ] Sin frameworks CSS (Bootstrap, Tailwind, etc.)
Selectores
 [ ] Uso de selectores de elemento (ej: h1, p, table)
 [ ] Uso de selectores de clase (ej: .card, .nav-item) - preferir para
estilos reutilizables
 [ ] Uso de selectores de id (ej: #header, #footer) - usar con
moderación
 [ ] Selectores claros y bien nombrados
Propiedades básicas
 [ ] Colores: color, background-color
 [ ] Tipografía: font-size, font-family, font-weight, text-align
 [ ] Espaciado: margin, padding
 [ ] Bordes: border, border-radius
 [ ] Dimensiones: width, height
Modelo de caja (Box Model)
 [ ] Uso correcto de margin para espaciado externo
 [ ] Uso correcto de padding para espaciado interno
 [ ] Uso de border para delimitar elementos
 [ ] Comprensión de cómo interactúan margin, padding y border
Display
 [ ] Uso de display: block cuando sea necesario
 [ ] Uso de display: inline cuando sea necesario
 [ ] Uso de display: inline-block para elementos que necesiten
propiedades de ambos
Unidades
 [ ] Uso de px para valores fijos
 [ ] Uso de % para valores relativos al contenedor padre
 [ ] Uso de rem para tipografía escalable (opcional)
Consistencia visual
 [ ] Paleta de colores consistente en todas las páginas
 [ ] Navbar y footer estilizados y consistentes
 [ ] Espaciado coherente entre secciones
Trabajo en equipo y control de versiones
Repositorio compartido en GitHub
 Un solo repositorio para todo el equipo
 Objetivo educativo: aprender a resolver conflictos de Git
Documentación dentro del código (obligatorio)
 Cada fichero debe empezar con un cabecero con:
o Nombre de la persona que lo crea
o Fecha
 Los cambios relevantes deben ir acompañados de comentarios
con nombre + fecha
Ejemplo:
// (Manuel 12/03/2026) Ajuste de estilos del navbar
Nota: aunque el ejemplo sea con //, en HTML/CSS podéis usar también <!--
... --> o /* ... */ según corresponda.
Distribución del trabajo
 Cada persona lidera una página HTML (Home / Servicios / Equipo /
Sobre / Contacto)
 Si el grupo tiene menos de 4 personas, algún miembro lidera 2 páginas
 Responsabilidades del líder de página:
o Crear la estructura HTML de su página
o Aplicar estilos CSS específicos de su página
o Asegurar que cumple todos los requisitos
o Documentar su trabajo en el README
Archivos con riesgo de conflicto
Los siguientes archivos serán editados por varias personas al mismo tiempo:
 styles.css (archivo crítico)
 Header y Navbar (presente en todas las páginas)
 Footer (si es común)

Estrategia para minimizar conflictos
En styles.css:
 Acordar bloques de estilos con prefijos por página:
o .home para estilos de la página principal
o .servicios para estilos de servicios
o .equipo para estilos del equipo
o .sobre para estilos de sobre nosotros
o .contacto para estilos de contacto
 Un bloque global para:
o .layout (estilos generales de layout)
o .nav (estilos del navbar)
o .footer (estilos del footer)
Flujo de trabajo para evitar conflictos:
1. Antes de editar styles.css o archivos compartidos:
git pull origin main
2. Realizar tus cambios en tu sección asignada
3. Antes de hacer push:
git pull origin main
4. Si hay conflicto:
o Mantener las reglas globales al inicio del archivo
o Mantener las reglas específicas de página en bloques
separados
o Comentar brevemente la decisión en el CSS o en el commit
message
5. Hacer push:
git add .
git commit -m "fix-conflict: Descripción clara de los
cambios"
git push origin main
Entregas
 Enlace al repositorio de GitHub compartido en University
 README.md completo con:
o Descripción del proyecto (como si fuera el portfolio de un
desarrollador profesional)
o Tecnologías usadas (HTML, CSS)
o Estructura de archivos
o Decisiones técnicas: Breve explicación de 3-5 decisiones
técnicas importantes que tomasteis y por qué
o Contribuciones de cada miembro del equipo
o Instrucciones para abrir el proyecto localmente
o (Opcional) Capturas de pantalla de la web