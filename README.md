# 🚀 MegaMenu Software - GrowBy

Un MegaMenu moderno y responsivo construido con Tailwind CSS y JavaScript vanilla, diseñado para la plataforma GrowBy.

## ✨ Características

- **MegaMenu Responsivo**: Panel ancho con 5 columnas organizadas por categorías
- **Diseño Moderno**: Minimalista, profesional con soft high contrast y bordes redondeados
- **Dark Mode**: Soporte completo con transiciones suaves y persistencia
- **Accesibilidad**: Roles ARIA, navegación por teclado y soporte para lectores de pantalla
- **Menú Móvil**: Navegación completa con acordeones para dispositivos móviles
- **Transiciones**: Animaciones suaves con fade y slide
- **Header Sticky**: Con efecto blur y sombra dinámica al hacer scroll

## 🛠️ Tecnologías

- **HTML5**: Semántico con `<nav>`, `<ul>`, `<li>`, `<a>`
- **Tailwind CSS**: Framework CSS utility-first via CDN
- **JavaScript Vanilla**: Sin frameworks, puro ES6+
- **Responsive Design**: Mobile-first approach
- **CSS Transitions**: Animaciones personalizadas

## 📱 Estructura del Menú

### Navegación Principal
- **Home** (`/`)
- **¿Quiénes Somos?** (`/quienes-somos/`)
- **Servicios** (MegaMenu con 5 columnas)
- **Soy Especialista** (Dropdown)
- **Recursos** (Dropdown)
- **Solicitar información** (`/contacto/`)
- **Registro** (Dropdown)

### Servicios - MegaMenu
1. **Desarrollo de Software** (10 sub-items)
2. **Diseño de Producto** (7 sub-items)
3. **Reclutamiento de Talento** (2 sub-items)
4. **Inteligencia Artificial** (3 sub-items)
5. **Ecommerce** (4 sub-items)

## 🚀 Despliegue

### Render (Recomendado)
1. Conecta tu repositorio de GitHub a Render
2. Selecciona "Static Site" como tipo de servicio
3. El archivo `render.yaml` ya está configurado
4. Render detectará automáticamente la configuración

### Otros Servicios
- **Netlify**: Drag & drop del archivo `index.html`
- **Vercel**: Importa el repositorio
- **GitHub Pages**: Activa en Settings > Pages

## 📁 Estructura del Proyecto

```
megamenu-software/
├── index.html          # Archivo principal con todo el código
├── render.yaml         # Configuración para Render
├── README.md           # Este archivo
└── .gitignore          # Archivos a ignorar en Git
```

## 🔧 Desarrollo Local

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/ben1998pe/megamenu-software.git
   cd megamenu-software
   ```

2. **Abre en el navegador**:
   - Doble clic en `index.html`
   - O usa un servidor local:
     ```bash
     python -m http.server 8000
     # Luego abre http://localhost:8000
     ```

## 🎨 Personalización

### Colores
Los colores primarios están definidos en la configuración de Tailwind:
```javascript
colors: {
  primary: {
    50: '#f0f9ff',
    500: '#3b82f6',
    600: '#2563eb',
    700: '#1d4ed8',
    900: '#1e3a8a'
  }
}
```

### Fuentes
- **Principal**: Inter (Google Fonts)
- **Fallback**: ui-sans-serif, system-ui

### Breakpoints
- **Mobile**: < 1024px (hamburger menu)
- **Desktop**: ≥ 1024px (MegaMenu y dropdowns)

## ♿ Accesibilidad

- **Roles ARIA**: `menubar`, `menu`, `aria-haspopup`, `aria-expanded`
- **Navegación por teclado**: Tab, Enter, Escape
- **Semántica HTML**: Estructura correcta para lectores de pantalla
- **Contraste**: Cumple estándares WCAG

## 📱 Responsive

- **Mobile First**: Diseño optimizado para móviles
- **Breakpoints**: Adaptación automática a diferentes tamaños
- **Touch Friendly**: Interacciones optimizadas para dispositivos táctiles

## 🔄 Funcionalidades JavaScript

- **MegaMenu**: Hover/focus en desktop, tap en móvil
- **Dropdowns**: Menús pequeños para navegación secundaria
- **Dark Mode**: Toggle con persistencia en localStorage
- **Scroll Effects**: Header sticky con sombra dinámica
- **Mobile Menu**: Full-screen con acordeones

## 📈 Performance

- **Tailwind CDN**: Sin build process
- **JavaScript Vanilla**: Sin dependencias externas
- **CSS Optimizado**: Solo las transiciones necesarias
- **Lazy Loading**: Menús se cargan solo cuando se necesitan

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

**Ben1998pe** - [GitHub](https://github.com/ben1998pe)

## 🙏 Agradecimientos

- **Tailwind CSS** por el framework CSS
- **GrowBy** por la inspiración del diseño
- **Inter Font** por la tipografía

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!
