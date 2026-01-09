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

### Fase 5: Funcionalidad JavaScript

#### 5.1 Modal de Producto
```javascript
- ✅ openProductModal() - Abre modal y bloquea scroll
- ✅ closeProductModal() - Cierra modal y restaura scroll
- ✅ Event listener para clic fuera del modal
- ✅ Event listener para tecla ESC
- ✅ stopPropagation() en botón "Comprar"
```

---

### Fase 6: Validación y Optimización

#### 6.1 Checklist de Requisitos
- ✅ **Flex/Grid**: Grid para layouts, Flex para componentes
- ✅ **Semántica**: header, nav, main, footer, section, article, aside
- ✅ **Tipografía**: 2 fuentes de Google Fonts
- ✅ **Estética**: Sombras, bordes redondeados, imágenes, colores
- ✅ **Comentarios**: HTML y CSS bien documentados
- ✅ **Fidelidad**: Diseño exacto al Figma

#### 6.2 Código Limpio
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

