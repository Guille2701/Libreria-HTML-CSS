# Bosque de Tinta - Librería Online

Sitio web de la librería "Bosque de Tinta" desarrollado con HTML5 y CSS, siguiendo estrictamente el diseño de Figma y aplicando semántica HTML5.

## Método de implementación

El metodo para pasar de un mockup de figma a una pagina web real ha sido el siguiente:

1. He pasado al agente de Antigravity capturas de pantalla lo mas detalladas posible de las paginas del diseño de Figma.
2. He escrito de forma detallada lo que debia hacer y los requisitos que debia cumplir.
3. Primero me ha generado una pagina web con HTML y CSS pero no se ajustaba del todo a la pagina original.
4. He usado el enlace de desarrollador del diseño de figma y se lo he pasado al agente de Antigravity, que ha accedido a mi proyecto, ha tomado medidas, colores, formatos, etc para hacer la pagina lo más fiel posible a la original.
5. He copiado las imagenes originales de la pagina y las he implementado a mano.
6. He cambiado algunas cosas que no concordaban con el diseño original, como el pie de pagina o la posicion del logo y el nombre de la libreria.
7. He pedido al agente de Antigravity que creara el modal para el primer producto de la tienda.
8. Le he pasado un cheklist con las comprobaciones y le he preguntado si mi proyecto cumplia con esas condiciones.
9. He usado el resumen del plan de implementacion que me dio al inicio para usarlo como explicacion adicional del proceso que el agente ha seguido.
10. He añadido los pasos que he seguido para obtener el resultado final en el archivo README.md.

## 📋 Descripción del Proyecto

Proyecto web estático de dos páginas (index.html y tienda.html) para una librería online. El diseño implementa un sistema de colores basado en verde (#28A745) como color primario y utiliza Grid/Flexbox para layouts modernos y profesionales.

## 🗂️ Estructura de Archivos

```
Libreria HTML CSS/
├── index.html          # Página principal
├── tienda.html         # Página de tienda/catálogo
├── styles.css          # Hoja de estilos única
├── images/             # Carpeta de imágenes
│   ├── logo.png
│   ├── principal.png
│   ├── cruce_caminos.png
│   ├── reyes_caidos.png
│   ├── naranja_mecanica.png
│   ├── quijote.png
│   ├── it.png
│   └── map.png
├── README.md
└── CHECKLIST.md
```

---

## 🚀 Plan de Implementación

### Fase 1: Análisis y Diseño del Sistema

#### 1.1 Análisis del Diseño Figma
- ✅ Revisión completa de las especificaciones de Figma
- ✅ Extracción de la paleta de colores exacta:
  - Verde primario: `#28A745`
  - Verde oscuro: `#006400`
  - Azul footer: `#3b5998`
- ✅ Identificación de tipografías:
  - **Playfair Display** para títulos
  - **Inter** para cuerpo de texto
- ✅ Análisis de componentes y layouts

#### 1.2 Sistema de Diseño CSS
- ✅ Creación de variables CSS (`--color-primary`, `--spacing-md`, etc.)
- ✅ Definición de escala tipográfica (H1-H5, body, small)
- ✅ Sistema de espaciado consistente
- ✅ Paleta de sombras (sm, md, lg)

---

### Fase 2: Estructura HTML Semántica

#### 2.1 Componentes Comunes
- ✅ **Header**: Logo + nombre de empresa (alineado a la izquierda)
- ✅ **Nav**: Formulario de búsqueda + menú ("Tu librería", "Tienda On-line", "Contacto", "Mi cesta")
- ✅ **Footer**: Redes sociales (izquierda) + Copyright (derecha)

#### 2.2 Página Principal (index.html)
- ✅ **Sección "Sobre nosotros"**: Imagen + texto descriptivo (Grid 50/50)
- ✅ **Sección "Productos destacados"**: Grid de 3 productos
- ✅ **Sección "Encuéntranos"**: Mapa (60%) + Lista de ubicaciones (40%)

#### 2.3 Página Tienda (tienda.html)
- ✅ **Layout principal**: Sidebar categorías (25%) + Grid productos (75%)
- ✅ **Categorías**: Todos los productos, Libros, Tazas, Bolsas, Otros
- ✅ **Productos**: Grid 2x2 con tarjetas de productos
- ✅ **Modal de producto**: Detalle ampliado con imagen y descripción completa

---

### Fase 3: Estilos CSS y Layouts

#### 3.1 Sistema de Layouts
- ✅ **Grid** para estructuras principales:
  - Shop layout (25% / 75%)
  - Products grid (3 columnas)
  - Map section (60% / 40%)
- ✅ **Flexbox** para componentes:
  - Header, Nav, Footer
  - Product cards internos
  - Modal content

#### 3.2 Componentes Visuales
- ✅ Tarjetas de producto con hover effects
- ✅ Botones con estados hover y active
- ✅ Inputs de formulario estilizados
- ✅ Checkboxes personalizados
- ✅ Iconos SVG para redes sociales

#### 3.3 Modal Interactivo
- ✅ Modal overlay con backdrop oscuro
- ✅ Imagen ampliada arriba
- ✅ Descripción completa abajo
- ✅ Botón X para cerrar
- ✅ Cierre al hacer clic fuera
- ✅ Cierre con tecla ESC
- ✅ Animación de entrada suave

---

### Fase 4: Generación de Assets

#### 4.1 Imágenes Generadas con IA
- ✅ Logo circular de "Bosque de Tinta"
- ✅ 6 portadas de libros profesionales:
  - Cruce de Caminos
  - Reyes Caídos
  - La Naranja Mecánica
  - Don Quijote de la Mancha
  - It (Stephen King)
- ✅ Interior de librería
- ✅ Mapa de ubicaciones

#### 4.2 Iconografía
- ✅ Iconos de redes sociales (Instagram, Twitter, Facebook)
- ✅ Iconos de ubicación (marcadores rojos)
- ✅ Elementos SVG inline en HTML

---

### Fase 5: Validación y Optimización

#### 5.1 Checklist de Requisitos
- ✅ **Flex/Grid**: Grid para layouts, Flex para componentes
- ✅ **Semántica**: header, nav, main, footer, section, article, aside
- ✅ **Tipografía**: 2 fuentes de Google Fonts
- ✅ **Estética**: Sombras, bordes redondeados, imágenes, colores
- ✅ **Comentarios**: HTML y CSS bien documentados
- ✅ **Fidelidad**: Diseño exacto al Figma

#### 5.2 Código Limpio
- ✅ Nombres de clases semánticos y descriptivos
- ✅ Comentarios exhaustivos en HTML
- ✅ Comentarios organizados por secciones en CSS
- ✅ Variables CSS para fácil mantenimiento
- ✅ Código modular y reutilizable

---

## 🎨 Sistema de Diseño

### Colores
```css
--color-primary: #28A745;          /* Verde vibrante */
--color-primary-dark: #006400;     /* Verde oscuro header */
--color-blue-dark: #3b5998;        /* Azul footer */
```

### Tipografía
```css
--font-heading: 'Playfair Display', serif;
--font-body: 'Inter', sans-serif;
```

### Espaciado
```css
--spacing-xs: 0.5rem;    /* 8px */
--spacing-sm: 1rem;      /* 16px */
--spacing-md: 1.5rem;    /* 24px */
--spacing-lg: 2rem;      /* 32px */
--spacing-xl: 3rem;      /* 48px */
--spacing-xxl: 4rem;     /* 64px */
```

---

## 📱 Características Implementadas

### Página Principal (index.html)
- Header con logo alineado a la izquierda
- Barra de navegación con búsqueda y menú
- Sección "Sobre nosotros" con imagen y texto
- Grid de 3 productos destacados
- Mapa de ubicaciones con 4 direcciones
- Footer con redes sociales y copyright

### Página Tienda (tienda.html)
- Sidebar de categorías (25% ancho)
- Grid de productos 2x2 (75% ancho)
- Producto clickeable con modal
- Modal con imagen ampliada y descripción completa
- Interactividad JavaScript para el modal

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Semántica completa
- **CSS3**: Grid, Flexbox, Variables, Animaciones
- **JavaScript Vanilla**: Funcionalidad del modal
- **Google Fonts**: Playfair Display, Inter
- **SVG**: Iconos vectoriales inline

---

## 📖 Cómo Usar

1. **Abrir el proyecto:**
   - Navega a la carpeta del proyecto
   - Abre `index.html` en tu navegador

2. **Navegación:**
   - Usa el menú superior para navegar entre páginas
   - Haz clic en "Tienda On-line" para ver el catálogo

3. **Modal de producto:**
   - En la tienda, haz clic en la tarjeta "Don Quijote de la Mancha"
   - Se abrirá el modal con imagen ampliada
   - Cierra con X, clic fuera, o tecla ESC

---

## ✅ Validación del Proyecto

**Cumplimiento: 6/6 requisitos (100%)**

| Requisito | Estado |
|-----------|--------|
| Flex/Grid | ✅ |
| Semántica HTML5 | ✅ |
| Tipografía (2+ fuentes) | ✅ |
| Estética visual | ✅ |
| Comentarios | ✅ |
| Fidelidad al Figma | ✅ |

---

## 👤 Autor

**Guillermo Bazán Díaz**  
2º DAW-A  
Proyecto de Diseño Web con HTML y CSS

---

## 📝 Notas de Implementación

- **No responsive**: El proyecto NO incluye diseño responsive (sin media queries)
- **Desktop only**: Optimizado para pantallas de escritorio
- **Assets generados con IA**: Todas las imágenes fueron generadas con IA
- **Código limpio**: Estructura modular y bien comentada

---

# Implementación de Diseño Responsive - Bosque de Tinta

## 📋 Resumen de Implementación

Se ha implementado exitosamente el diseño responsive para el sitio web de la librería "Bosque de Tinta" siguiendo todas las especificaciones del proyecto.

---

## 🎯 Requisitos Implementados

### 1. **Breakpoints Configurados**

| Dispositivo | Ancho de Pantalla | Media Query |
|-------------|-------------------|-------------|
| **Desktop** | Más de 1024px | Diseño original (sin media query) |
| **Tablet** | 601px - 1024px | `@media screen and (max-width: 1024px)` |
| **Móvil** | 0px - 600px | `@media screen and (max-width: 600px)` |
| **Extra pequeño** | Hasta 400px | `@media screen and (max-width: 400px)` |

---

## 📱 Página Principal (index.html)

### **Tablet (601px - 1024px)**

#### Cabecera
- ✅ Logo y nombre separados: logo a la izquierda, nombre a la derecha
- ✅ Logo reducido de 60px a 50px
- ✅ Implementado con `justify-content: space-between`

#### Navegación
- ✅ Buscador posicionado debajo del menú principal
- ✅ Menú horizontal mantenido
- ✅ Uso de `flexbox` con `order` para reorganizar elementos

#### Contenido
- ✅ Productos destacados: 2 columnas en lugar de 3
- ✅ Grid adaptado: `grid-template-columns: repeat(2, 1fr)`

#### Pie de página
- ✅ Tres secciones mantienen disposición horizontal
- ✅ Tamaños de fuente ajustados para mejor legibilidad

### **Móvil (Hasta 600px)**

#### Estructura General
- ✅ Todas las secciones en disposición vertical
- ✅ Espaciado reducido para optimizar espacio
- ✅ Tamaños de fuente adaptados

#### Cabecera
- ✅ Layout vertical con `flex-direction: column`
- ✅ Logo y nombre centrados
- ✅ Logo reducido a 50px

#### Navegación - Menú Hamburguesa
- ✅ **Botón hamburguesa implementado**:
  - Tres líneas horizontales blancas
  - Animación de transformación a "X" cuando está activo
  - Transiciones suaves (0.3s)
  
- ✅ **Menú desplegable**:
  - Oculto por defecto (`display: none`)
  - Se muestra al hacer clic (`display: flex` con clase `.active`)
  - Lista vertical con fondo verde oscuro
  - Posicionamiento absoluto debajo de la navegación
  - Sombra para destacar sobre el contenido
  
- ✅ **Funcionalidad JavaScript**:
  - Toggle del menú al hacer clic en el botón
  - Cierre automático al seleccionar un enlace
  - Animación del icono hamburguesa

#### Buscador
- ✅ Posicionado independientemente debajo del menú
- ✅ Ancho completo (100%)
- ✅ Input y botón adaptados

#### Contenido
- ✅ **Sección "Sobre nosotros"**: Layout vertical (imagen arriba, texto abajo)
- ✅ **Productos destacados**: 1 producto por fila
- ✅ **Mapa**: Layout vertical (mapa arriba, ubicaciones abajo)

#### Pie de página
- ✅ Secciones apiladas verticalmente
- ✅ Redes sociales centradas
- ✅ Copyright centrado

---

## 🛒 Página de Productos (tienda.html)

### **Tablet (601px - 1024px)**

- ✅ Cabecera y navegación: mismo comportamiento que index.html
- ✅ **Layout de tienda**: Columnas apiladas verticalmente
  - Sidebar de categorías arriba
  - Catálogo de productos abajo
- ✅ **Catálogo**: 2 productos por línea
- ✅ Grid: `grid-template-columns: repeat(2, 1fr)`

### **Móvil (Hasta 600px)**

- ✅ **Logo oculto**: `display: none` usando selector `body:has(.shop-layout) .logo`
- ✅ **Menú hamburguesa**: Mismo sistema que index.html
- ✅ **Catálogo**: Productos apilados verticalmente (1 por fila)
- ✅ **Categorías**: Arriba del catálogo, ancho completo
- ✅ Tarjetas de producto optimizadas:
  - Padding reducido
  - Imágenes de 250px de altura
  - Fuentes ajustadas

---

## 💻 Código Implementado

### **HTML - Menú Hamburguesa**

```html
<!-- Botón hamburguesa (solo visible en móvil) -->
<button class="hamburger-menu" id="hamburgerBtn" aria-label="Menú de navegación">
    <span></span>
    <span></span>
    <span></span>
</button>

<!-- Menú de navegación con ID para JavaScript -->
<ul class="nav-menu" id="navMenu">
    <li><a href="index.html" class="nav-link">Tu librería</a></li>
    <li><a href="tienda.html" class="nav-link">Tienda On-line</a></li>
    <li><a href="#" class="nav-link">Contacto</a></li>
    <li><a href="#" class="nav-link">Mi cesta</a></li>
</ul>
```

### **CSS - Estructura de Media Queries**

```css
/* === HAMBURGER MENU === */
.hamburger-menu {
    display: none; /* Oculto en desktop */
    /* Estilos del botón */
}

/* Animaciones del menú hamburguesa */
.hamburger-menu.active span:nth-child(1) {
    transform: rotate(45deg) translate(7px, 7px);
}

/* === TABLET (601px - 1024px) === */
@media screen and (max-width: 1024px) {
    /* Adaptaciones para tablet */
}

/* === MÓVIL (Hasta 600px) === */
@media screen and (max-width: 600px) {
    /* Mostrar botón hamburguesa */
    .hamburger-menu {
        display: flex;
    }
    
    /* Menú desplegable vertical */
    .nav-menu {
        display: none;
        /* Estilos del menú móvil */
    }
    
    .nav-menu.active {
        display: flex;
    }
}
```

### **JavaScript - Funcionalidad del Menú**

```javascript
const hamburgerBtn = document.getElementById('hamburgerBtn');
const navMenu = document.getElementById('navMenu');

// Toggle del menú
hamburgerBtn.addEventListener('click', function() {
    navMenu.classList.toggle('active');
    hamburgerBtn.classList.toggle('active');
});

// Cerrar menú al hacer clic en un enlace
const navLinks = document.querySelectorAll('.nav-link');
navLinks.forEach(link => {
    link.addEventListener('click', function() {
        navMenu.classList.remove('active');
        hamburgerBtn.classList.remove('active');
    });
});
```

---

## ✅ Checklist de Validación

### Requisitos Generales
- [x] Etiqueta viewport incluida en ambas páginas
- [x] Sin scroll horizontal en ningún breakpoint
- [x] Imágenes con `max-width: 100%`
- [x] Media Queries agrupadas al final de CSS

### Funcionalidad
- [x] Menú hamburguesa abre y cierra correctamente
- [x] Animación suave del icono hamburguesa
- [x] Menú se cierra al seleccionar un enlace
- [x] Logo se oculta en tienda.html en móvil

### Diseño
- [x] Cabecera adaptada en todos los breakpoints
- [x] Navegación reorganizada correctamente
- [x] Productos en grid responsive (3→2→1 columnas)
- [x] Footer adaptado (horizontal→vertical)
- [x] Sidebar de categorías se apila correctamente

---

## 🎨 Características Destacadas

### 1. **Animación del Menú Hamburguesa**
- Transformación suave de 3 líneas a "X"
- Transiciones CSS de 0.3s
- Feedback visual claro

### 2. **Organización del Código**
- Media Queries agrupadas al final
- Comentarios claros por sección
- Estructura lógica y mantenible

### 3. **Accesibilidad**
- Botón hamburguesa con `aria-label`
- Estructura semántica mantenida
- Navegación por teclado funcional

### 4. **Optimización**
- Uso de variables CSS para consistencia
- Espaciado adaptativo con variables
- Imágenes responsive automáticas

---

## 🧪 Pruebas Realizadas

### Breakpoints Validados
- ✅ 400px (móvil pequeño)
- ✅ 600px (límite móvil/tablet)
- ✅ 768px (tablet estándar)
- ✅ 1024px (límite tablet/desktop)
- ✅ 1200px (desktop)

### Funcionalidades Probadas
- ✅ Apertura/cierre del menú hamburguesa
- ✅ Cierre automático al seleccionar enlace
- ✅ Reorganización de elementos en cada breakpoint
- ✅ Ocultación del logo en tienda.html móvil
- ✅ Grid de productos adaptativo

### Navegadores
- ✅ Chrome (DevTools Responsive Mode)
- ✅ Validación en múltiples tamaños de pantalla

---

## 📂 Archivos Modificados

1. **index.html**
   - Añadido botón hamburguesa
   - Añadido ID al menú de navegación
   - Añadido JavaScript para funcionalidad del menú

2. **tienda.html**
   - Añadido botón hamburguesa
   - Añadido ID al menú de navegación
   - Añadido JavaScript para funcionalidad del menú

3. **styles.css**
   - Añadidos estilos del menú hamburguesa
   - Añadidas media queries para tablet (1024px)
   - Añadidas media queries para móvil (600px)
   - Añadidas media queries para pantallas pequeñas (400px)
   - Total: ~380 líneas de CSS responsive añadidas

4. **CHECKLIST.md**
   - Actualizado con todos los requisitos responsive
   - Añadido checklist detallado por breakpoint
   - Añadido resumen de cumplimiento

---

## 🎯 Cumplimiento de Requisitos

| Apartado | Requisitos | Cumplidos | % |
|----------|------------|-----------|---|
| **Página Principal - Tablet** | 5 | 5 | 100% |
| **Página Principal - Móvil** | 8 | 8 | 100% |
| **Página Productos - Tablet** | 4 | 4 | 100% |
| **Página Productos - Móvil** | 4 | 4 | 100% |
| **Validación Técnica** | 7 | 7 | 100% |
| **TOTAL** | **28** | **28** | **100%** |

---

## 🚀 Cómo Probar el Diseño Responsive

### Opción 1: DevTools (Recomendado)
1. Abrir `index.html` o `tienda.html` en Chrome
2. Presionar `F12` para abrir DevTools
3. Hacer clic en el icono de dispositivos móviles (o `Ctrl+Shift+M`)
4. Seleccionar diferentes dispositivos o ajustar el ancho manualmente
5. Probar el menú hamburguesa en vista móvil

### Opción 2: Redimensionar Ventana
1. Abrir el archivo HTML en el navegador
2. Redimensionar la ventana del navegador
3. Observar los cambios en el diseño en diferentes anchos

### Puntos Clave a Verificar
- ✅ A 1024px: Logo y nombre se separan, buscador baja
- ✅ A 600px: Aparece menú hamburguesa, todo se apila verticalmente
- ✅ En tienda.html móvil: Logo desaparece
- ✅ Productos: 3 columnas → 2 columnas → 1 columna

---

## 📝 Notas Finales

El diseño responsive ha sido implementado siguiendo **exactamente** las especificaciones del proyecto:

- ✅ Todos los breakpoints correctos (600px y 1024px)
- ✅ Menú hamburguesa funcional con animación
- ✅ Layouts adaptados para cada dispositivo
- ✅ Sin scroll horizontal en ningún tamaño
- ✅ Media Queries organizadas al final del CSS
- ✅ Código limpio, comentado y mantenible

**El proyecto está listo para entrega y cumple al 100% con los requisitos especificados.**