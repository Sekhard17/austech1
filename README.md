# Austech - Herramientas de Precisión

## 🛠️ Descripción
Austech es mi proyecto de sitio web corporativo para una empresa de herramientas de precisión. Decidí utilizar Astro como framework principal por su rendimiento excepcional y su capacidad de generar sitios estáticos, lo que resulta en una carga ultrarrápida y una excelente experiencia de usuario.

## 🚀 Tecnologías Utilizadas

### Core
- **Astro v5.5.4**: Framework principal elegido por su velocidad y enfoque "Islands Architecture"
- **React v19.0.0**: Para componentes interactivos específicos
- **TypeScript**: Para type-safety y mejor mantenibilidad del código

### Estilos y Animaciones
- **TailwindCSS v3.4.1**: Framework de CSS utility-first para un desarrollo ágil
- **Motion One**: Librería liviana para animaciones performantes
- **AOS (Animate On Scroll)**: Para animaciones al hacer scroll
- **Swiper**: Para el carrusel del hero section

## 🎨 Diseño y UI

### Paleta de Colores
- **Primary**: `#FF7800` (Naranja corporativo)
- **Background**: 
  - Light: `#F9FAFB` (gray-50)
  - Dark: `#111827`
- **Text**: 
  - Primary: `#111827` (gray-900)
  - Secondary: `#4B5563` (gray-600)

### Características UI/UX
- Diseño responsive optimizado para todos los dispositivos
- Animaciones suaves y performantes
- Micro-interacciones en hover states
- Loading lazy de imágenes
- Transiciones fluidas entre secciones

## 📦 Características Principales
- Landing page moderna y responsive
- Catálogo de productos con grid adaptativo
- Sección de partners con animaciones
- Carrusel hero con múltiples slides
- Navegación fluida y accesible
- Optimización SEO incorporada

## 🔜 Features Planeadas
1. **E-commerce Integration**
   - Integración con WooCommerce/Shopify
   - Carrito de compras
   - Sistema de pagos

2. **Área de Cliente**
   - Portal de cliente
   - Seguimiento de pedidos
   - Historial de compras

3. **Mejoras Técnicas**
   - PWA implementation
   - Caché offline
   - Notificaciones push
   - Integración con CMS headless

4. **Contenido**
   - Blog técnico
   - Fichas técnicas descargables
   - Videos tutoriales
   - Calculadora de especificaciones

## 🚀 Instalación y Uso

```bash
# Clonar el repositorio
git clone https://github.com/tuuser/austech.git

# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev

# Construir para producción
pnpm build
```

## 📝 Estructura del Proyecto
```
austech/
├── src/
│   ├── components/    # Componentes reutilizables
│   ├── layouts/      # Layouts base
│   ├── pages/        # Rutas y páginas
│   ├── styles/       # Estilos globales
│   └── assets/       # Imágenes y recursos
├── public/          # Archivos estáticos
└── astro.config.mjs # Configuración de Astro
```

## ⚡ Performance
- Lighthouse Score: 95+ en todas las métricas
- First Contentful Paint: < 1s
- Time to Interactive: < 2s
- Cumulative Layout Shift: < 0.1

## 🤝 Contribución
¿Tienes ideas para mejorar Austech? ¡Las contribuciones son bienvenidas! 

1. Fork el proyecto
2. Crea tu Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la Branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto
- Website: [austech.cl](https://austech.cl)

---
Hecho con ❤️ por Joaquín.


