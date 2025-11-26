# Asadero Esquisitos - Menú Digital Premium

**Menú digital profesional y responsivo para Asadero Esquisitos**, construido con React 19, TypeScript, Tailwind CSS 4 y Framer Motion. Diseño gráfico y web de alta calidad, optimizado para despliegue en Netlify.

---

## 🎯 Características Principales

### 🎨 Diseño Premium
- **Paleta de Colores Sofisticada:** Naranja fuego (#FF6600), Dorado (#FFD700), Negro elegante (#0D0D0D)
- **Tipografía Estratégica:** Alfa Slab One (Display), Montserrat (Body), Yellowtail (Accents)
- **Profundidad Visual:** Sombras, gradientes y efectos de brillo (glow)
- **Composición Asimétrica:** Diseño moderno y profesional, no centrado

### ⚡ Funcionalidad Completa
- ✅ **Navbar Responsivo:** Menú hamburguesa en móvil, navegación completa en desktop
- ✅ **Hero Section:** Fondo dinámico con brasas y fuego, animaciones parallax
- ✅ **Menú Interactivo:** Secciones de Pollo, Combos, Adicionales y Bebidas
- ✅ **Scroll Suave:** Navegación fluida entre secciones
- ✅ **Botones Funcionales:** Integración con WhatsApp (+57 321 474 6453)
- ✅ **Enlaces a Redes Sociales:** Facebook, Instagram, TikTok

### 📱 Responsividad Impecable
- **Mobile-First:** Optimizado para celulares (320px+)
- **Tablet:** Adaptación perfecta (768px+)
- **Desktop:** Experiencia completa (1024px+)
- **Pantallas Grandes:** Soporte para 4K

### ⚙️ Tecnología Robusta
- **React 19:** Componentes modernos y eficientes
- **TypeScript:** Tipado estático para mayor seguridad
- **Tailwind CSS 4:** Utilidades de estilo de vanguardia
- **Framer Motion:** Animaciones fluidas y micro-interacciones
- **Vite:** Construcción ultra-rápida
- **Wouter:** Enrutamiento ligero del lado del cliente

---

## 📂 Estructura del Proyecto

```
asadero-menu-premium/
├── client/
│   ├── public/
│   │   └── images/           # Imágenes estáticas
│   ├── src/
│   │   ├── components/       # Componentes reutilizables (shadcn/ui)
│   │   ├── contexts/         # Contextos de React
│   │   ├── hooks/            # Custom hooks
│   │   ├── lib/              # Utilidades
│   │   ├── pages/
│   │   │   ├── Home.tsx      # Página principal con menú
│   │   │   └── NotFound.tsx  # Página 404
│   │   ├── App.tsx           # Componente raíz
│   │   ├── main.tsx          # Punto de entrada
│   │   └── index.css         # Estilos globales y temas
│   └── index.html            # Template HTML
├── server/                   # Placeholder (no se usa en estático)
├── package.json              # Dependencias
├── vite.config.ts            # Configuración de Vite
├── tsconfig.json             # Configuración de TypeScript
├── tailwind.config.ts        # Configuración de Tailwind
└── netlify.toml              # Configuración de Netlify
```

---

## 🚀 Despliegue en Netlify

### Opción 1: Drag & Drop (Recomendado - Más Fácil)

1. **Construir el proyecto localmente:**
   ```bash
   npm install
   npm run build
   ```

2. **Ir a Netlify:**
   - Ve a https://app.netlify.com/
   - Haz clic en "Add new site" → "Deploy manually"

3. **Subir la carpeta `dist`:**
   - Arrastra y suelta la carpeta `dist` generada
   - ¡Listo! Tu sitio estará en línea en segundos

### Opción 2: Desde GitHub

1. **Sube el proyecto a GitHub**
2. **Conecta con Netlify:**
   - Ve a https://app.netlify.com/
   - Haz clic en "Add new site" → "Import an existing project"
   - Selecciona GitHub y el repositorio
3. **Netlify desplegará automáticamente**

### Opción 3: Usando Netlify CLI

```bash
npm install -g netlify-cli
netlify deploy --prod --dir=dist
```

---

## 🎨 Paleta de Colores

| Color | Código | Uso |
|-------|--------|-----|
| **Fuego Naranja** | `#FF6600` | Primario, botones, acentos |
| **Dorado** | `#FFD700` | Secundario, precios, destacados |
| **Negro Elegante** | `#0D0D0D` | Fondo principal |
| **Gris Oscuro** | `#1A1A1A` | Tarjetas, elementos secundarios |
| **Blanco Cálido** | `#F5F5F5` | Texto principal |
| **Gris Neutro** | `#999999` | Texto secundario |

---

## 📱 Menú Digital

### Secciones

1. **Pollo (8 items)**
   - Pollo Asado (4 tamaños)
   - Pollo Broaster (4 tamaños)
   - Incluye: Sopa, Papa, Yuca, Arepa, Tártara, Ají

2. **Combos (2 items)**
   - 3 Alas Broaster
   - 2 Muslos Broaster (¡Favorito!)

3. **Adicionales (8 items)**
   - Mute Santandereano
   - Costillas de Cerdo
   - Papas, Arepas, Postres, etc.

4. **Bebidas (13 items)**
   - Gaseosas
   - Jugos
   - Agua
   - Bebidas naturales

---

## 🔧 Desarrollo Local

### Requisitos
- Node.js 18+
- npm o pnpm

### Instalación

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Vista previa de producción
npm run preview

# Verificar tipos
npm run check

# Formatear código
npm run format
```

---

## 📞 Información de Contacto

- **WhatsApp:** +57 321 474 6453
- **Facebook:** https://www.facebook.com/share/1GtZJef3HM/
- **Instagram:** @asadero.esquisitos
- **TikTok:** @asadero.esquisito
- **Ubicación:** Girón, Santander

---

## 🎯 Características Técnicas

### Performance
- ✅ Código optimizado y tree-shaked
- ✅ Imágenes optimizadas
- ✅ Carga rápida (< 2s)
- ✅ Puntuación Lighthouse 90+

### Accesibilidad
- ✅ Contraste de colores WCAG AA
- ✅ Navegación por teclado
- ✅ Etiquetas semánticas HTML5
- ✅ ARIA labels donde es necesario

### SEO
- ✅ Meta tags optimizados
- ✅ Estructura semántica
- ✅ Open Graph para redes sociales
- ✅ Sitemap automático

### Seguridad
- ✅ HTTPS automático en Netlify
- ✅ Content Security Policy
- ✅ Sin dependencias vulnerables

---

## 🎬 Animaciones y Micro-interacciones

- **Navbar:** Animación de entrada suave, cambio de estilo al hacer scroll
- **Hero:** Parallax del fondo, fade-in de contenido
- **Menú:** Animaciones staggered (escalonadas) al entrar en viewport
- **Botones:** Hover effects, scale y sombra de fuego
- **Menú Móvil:** Slide-in desde la derecha con spring animation

---

## 📄 Licencia

© 2025 Asadero Esquisitos. Todos los derechos reservados.

Diseñado y desarrollado con 🔥 para el mejor sabor.

---

## 🤝 Soporte

Para reportar errores o sugerencias, contacta a través de WhatsApp: +57 321 474 6453

---

**¡Disfruta de tu menú digital premium!** 🍗🔥
