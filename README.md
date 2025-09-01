# Portafolio Digital Profesional - Vinicio Salto

Portafolio web moderno y responsive de Vinicio Salto - Desarrollador, Escritor e Innovador Educativo. Creado con HTML5, CSS3 y JavaScript vanilla, optimizado para Netlify.

## 🎯 Sobre Vinicio

**Enfoque actual:** Escritura de relatos y fábulas · Plantillas web mínimas · Experimentos con LLM  
**Metodología:** Iteración breve · Restricciones claras · Documentación abierta  
**Valores:** Pensamiento crítico · IA ética · Accesibilidad · Interdisciplinariedad  
**Idiomas:** Español (nativo) · Inglés (profesional)

## 🚀 Proyectos Destacados en el Portafolio

- **[InnovaEDU](https://github.com/MarcoS9309/InnovaEDU)** - Recursos y prototipos para innovación educativa con IA
- **[Historias](https://github.com/MarcoS9309/Historias)** - Relatos breves y experimentos narrativos con IA
- **[Fábulas Emocionales](https://github.com/MarcoS9309/fabulas-emocionales)** - Fábulas originales para reflexión y educación
- **[Senderos Arte](https://github.com/MarcoS9309/Senderos_arte)** - Talleres y guías para arte + humanidades con apoyo de IA
- **[Plantilla Web Mínima](https://github.com/MarcoS9309/plantilla-web-minima)** - Base HTML/CSS/JS ligera para proyectos rápidos
- **[Gaminifa Demo](https://github.com/MarcoS9309/gaminifa_demo)** - Demo de juego/experimento interactivo orientado a aprendizaje lúdico

## 🚀 Características

- **Diseño Responsive**: Perfectamente adaptado para todos los dispositivos
- **Rendimiento Optimizado**: Carga rápida y experiencia fluida
- **Accesibilidad**: Cumple con estándares web de accesibilidad
- **SEO Optimizado**: Meta tags y estructura semántica
- **Animaciones Suaves**: Transiciones y efectos visuales atractivos
- **Formulario de Contacto**: Sistema de contacto funcional
- **PWA Ready**: Preparado para funcionar como Progressive Web App

## 📁 Estructura del Proyecto

```
portafolio/
├── index.html              # Página principal
├── css/
│   └── styles.css          # Estilos principales
├── js/
│   └── script.js           # JavaScript principal
├── assets/
│   ├── images/             # Imágenes del portafolio
│   └── favicon.ico         # Favicon del sitio
├── netlify.toml            # Configuración de Netlify
├── README.md               # Este archivo
└── .github/
    └── copilot-instructions.md
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con Flexbox y Grid
- **JavaScript ES6+**: Funcionalidad interactiva
- **Font Awesome**: Iconos
- **Google Fonts**: Tipografía (Inter)

## 🎨 Personalización

### 1. Información Personal
Edita el archivo `index.html` y reemplaza los placeholders:
- `[Tu Nombre]` - Tu nombre completo
- `[X]` - Años de experiencia
- `tu-email@ejemplo.com` - Tu email real
- Links de redes sociales

### 2. Imágenes
Agrega tus imágenes en la carpeta `assets/images/`:
- `profile.jpg` - Tu foto de perfil (400x400px recomendado)
- `about.jpg` - Imagen para la sección about
- `project1.jpg`, `project2.jpg`, `project3.jpg` - Capturas de tus proyectos

### 3. Proyectos
Actualiza la sección de proyectos con:
- Nombres de tus proyectos
- Descripciones
- Tecnologías utilizadas
- Links a demos y repositorios

### 4. Habilidades
Modifica las habilidades técnicas según tu experiencia:
- Frontend technologies
- Backend technologies
- Herramientas y frameworks

### 5. Colores y Estilos
Personaliza los colores en `css/styles.css` modificando las variables CSS:
```css
:root {
    --primary-color: #2563eb;    /* Color principal */
    --secondary-color: #64748b;  /* Color secundario */
    --accent-color: #f59e0b;     /* Color de acento */
    /* ... más variables */
}
```

## 🚀 Despliegue en Netlify

### Opción 1: Despliegue Directo
1. Comprime todos los archivos en un ZIP
2. Ve a [Netlify](https://netlify.com)
3. Arrastra el ZIP a la zona de despliegue
4. ¡Listo!

### Opción 2: Desde Git
1. Sube el código a GitHub
2. Conecta tu repositorio con Netlify
3. Configuración automática con `netlify.toml`
4. Despliegue automático en cada commit

### Configuración de Dominio Personalizado
1. Ve a Domain Settings en Netlify
2. Agrega tu dominio personalizado
3. Configura los DNS según las instrucciones
4. Activa HTTPS automático

## 📱 Funcionalidades

### Navegación
- Menú responsivo con hamburger para móvil
- Scroll suave entre secciones
- Header con efecto al hacer scroll

### Formulario de Contacto
- Validación en tiempo real
- Sistema de notificaciones
- Compatible con Netlify Forms (opcional)

### Animaciones
- Animaciones de entrada para elementos
- Efecto de escritura en el título principal
- Contadores animados en estadísticas
- Partículas de fondo (opcional)

### Características Adicionales
- Botón "volver arriba"
- Lazy loading para imágenes
- Modo oscuro (implementación opcional)
- Optimización SEO

## 🔧 Desarrollo Local

1. Clona o descarga el proyecto
2. Abre `index.html` en tu navegador
3. Para un servidor local (opcional):
   ```bash
   # Con Python
   python -m http.server 8000
   
   # Con Node.js (http-server)
   npx http-server
   
   # Con PHP
   php -S localhost:8000
   ```

## 📊 Optimización

### Performance
- Imágenes optimizadas (WebP recomendado)
- CSS y JS minificados para producción
- Lazy loading implementado
- Cache headers configurados

### SEO
- Meta tags completos
- Estructura semántica HTML5
- Open Graph tags
- Sitemap.xml (generar si es necesario)

### Accesibilidad
- Navegación por teclado
- Textos alternativos en imágenes
- Contraste de colores adecuado
- Lectores de pantalla compatibles

## 🔒 Seguridad

El archivo `netlify.toml` incluye headers de seguridad:
- X-Frame-Options
- X-XSS-Protection
- Content-Security-Policy
- Y más...

## 📈 Analytics (Opcional)

Para añadir Google Analytics:
1. Obtén tu ID de tracking
2. Agrega el código en `<head>` de index.html
3. Configura eventos personalizados en script.js

## 🤝 Contribuir

Si encuentras bugs o tienes mejoras:
1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver `LICENSE` para más detalles.

## 📞 Soporte

Si necesitas ayuda:
- Crea un issue en GitHub
- Consulta la documentación de Netlify
- Revisa los comentarios en el código

---

**¡Hecho con ❤️ para desarrolladores!**

### 📝 Notas de Personalización

Recuerda reemplazar TODOS los placeholders antes del despliegue:
- [ ] Información personal en index.html
- [ ] Imágenes en assets/images/
- [ ] Enlaces de redes sociales
- [ ] Proyectos y descripciones
- [ ] Información de contacto
- [ ] Favicon personalizado
- [ ] Meta description y title

### 🎯 Próximos Pasos

1. **Personaliza el contenido** con tu información
2. **Agrega tus proyectos** reales
3. **Optimiza las imágenes** para web
4. **Testa en diferentes dispositivos**
5. **Despliega en Netlify**
6. **Configura tu dominio personalizado**
7. **Añade Google Analytics** (opcional)
8. **Comparte tu portafolio** con el mundo

¡Tu portafolio profesional está listo para impresionar! 🌟
