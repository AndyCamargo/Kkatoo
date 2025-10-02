KKatoo - Sistema de Llamadas y SMS Masivos
Sistema web empresarial para el envío masivo de llamadas y mensajes de texto a múltiples destinatarios de forma rápida y económica.
📋 Descripción
KKatoo es una plataforma de comunicación masiva que permite a las empresas gestionar campañas de llamadas y SMS a gran escala. El sistema ofrece una interfaz intuitiva con carrusel de marcas asociadas, navegación fluida y diseño responsive.
✨ Características Principales

Envío Masivo: Comunicación con miles de contactos simultáneamente
Bajo Costo: Solución económica para campañas empresariales
Análisis en Tiempo Real: Seguimiento y análisis de campañas
Gestión de Contactos: Sistema organizado de bases de datos
Interfaz Intuitiva: Diseño moderno con slider de imágenes Jssor
Header Dinámico: Logo que cambia al hacer scroll

🚀 Tecnologías Utilizadas

HTML5: Estructura semántica
CSS3: Estilos personalizados con fuentes Ubuntu
JavaScript/jQuery: Interactividad y efectos
Jssor Slider: Carrusel avanzado de logos de marcas
Diseño Responsive: Adaptable a diferentes dispositivos

📁 Estructura del Proyecto
```
kkatoo/
│
├── index.html              # Página principal
├── nuevo.html              # Página de pruebas
├── style.css               # Estilos principales
│
├── js/
│   ├── jquery-1.11.3.min.js
│   ├── jssor.slider.mini.js
│   └── npm.js
│
├── imagenes/
│   ├── logo.png
│   ├── logo_kkatoo_header.png
│   ├── telefono.png
│   ├── contactos.png
│   ├── crear_mensaje.png
│   ├── envia_analiza.png
│   ├── fondo_personas.png
│   ├── textura.png
│   └── iconos (icon5.png, icon6.png, icon7.png, icon8.png)
│
├── img/                    # Logos de marcas para slider
│   ├── amazon.jpg
│   ├── google.jpg
│   ├── facebook.jpg
│   └── [otros logos]
│
└── fonts/
    ├── Ubuntu-R.ttf
    └── Ubuntu-L.ttf

```


🎨 Características de Diseño
Header Dinámico

Fondo semi-transparente
Logo que cambia al scrollear (después de 333px)
Navegación fija con enlaces a: Inicio, Precios, Soporte, Ingresar
Botón "Registrate" destacado

Secciones

Hero Section

Fondo texturizado
Llamado a la acción principal
Botón "Prueba gratis"


¿Cómo Funciona?

3 pasos visuales:

Agrega contactos
Crea mensajes
Envía y analiza




Call to Action

"KKATOO LLAMA POR TI"
Fondo destacado (#7e114e)


Beneficios

Sección con imagen de fondo
Valor agregado del servicio


Slider de Marcas

Carrusel automático con Jssor
Muestra logos de empresas confiables
7 columnas visibles
Velocidad: 1600ms
Auto-play continuo


Formulario de Contacto

Input con icono de email
Botón "Inicia ahora"


Footer

Tres columnas: Compañía, Recursos, Soporte
Redes sociales
Información de contacto
Copyright © 2015 Fonomarketing S.A.S.



🎨 Paleta de Colores

Principal: #7e114e (Morado oscuro)
Secundario: #800080 (Morado)
Texto: #A9A9A9 (Gris)
Fondo: #E0E0E0 (Gris claro)
Blanco: #FFFFFF
Negro semitransparente: rgba(33,25,21,0.3)

💻 Instalación y Uso

Clonar o descargar el proyecto

bashgit clone [url-del-repositorio]

Estructura de archivos requerida

Asegúrate de tener todas las carpetas (js, imagenes, img, fonts)
Verifica que las rutas de las imágenes coincidan


Abrir en navegador

Abre index.html directamente en tu navegador
O usa un servidor local (recomendado):



bash# Con Python 3
python -m http.server 8000

# Con Node.js (http-server)
npx http-server

Visualizar

Navega a http://localhost:8000



📱 Responsive Design
El sitio está optimizado para:

Escritorio (max-width: 1280px)
Tablets
Móviles

Viewport configurado: width=device-width, initial-scale=1
🔧 Configuración del Slider
El slider Jssor está configurado con:
javascript{
  $AutoPlay: true,
  $Idle: 0,
  $AutoPlaySteps: 4,
  $SlideDuration: 1600,
  $SlideEasing: $Jease$.$Linear,
  $PauseOnHover: 4,
  $SlideWidth: 140,
  $Cols: 7
}
📞 Contacto
Fonomarketing S.A.S.

Teléfono: +57 (1) 703 39 05
Ubicación: Bogotá, Colombia

📝 Notas Técnicas

jQuery: v1.11.3
Compatibilidad: IE9+, Chrome, Firefox, Safari, Edge
Hardware Acceleration: Activada para animaciones
SEO: Estructura semántica HTML5

🐛 Problemas Conocidos

Algunos textos tienen errores tipográficos (ej: "solucionn" en lugar de "solución")
Las rutas de imágenes en el slider pueden necesitar ajustes según el entorno
El diseño no es completamente responsive en dispositivos muy pequeños

🔄 Mejoras Futuras

 Corregir errores ortográficos
 Mejorar responsive design para móviles
 Actualizar jQuery a versión más reciente
 Optimizar imágenes para web
 Agregar lazy loading a imágenes
 Implementar sistema de backend funcional
 Añadir validación de formularios
 Mejorar accesibilidad (ARIA labels)

📄 Licencia
Copyright © 2015 Fonomarketing S.A.S. Todos los derechos reservados
