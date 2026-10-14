# 🌐 Portafolio Personal — Jesús Reyes

Sitio web de una sola página (**one-page**) que presenta mi perfil como estudiante de Ingeniería de Software: quién soy, mi formación, las tecnologías que manejo y mis canales de contacto.

> 🚧 **PROYECTO EN CONSTRUCCIÓN.** Este sitio está en desarrollo activo: todavía le faltan secciones por completar y mejoras pendientes (ver *Próximos pasos*).

> **Este es mi primer proyecto de desarrollo web.** Lo construí desde cero con **HTML5 y CSS3** como parte de mi aprendizaje autónomo, y representa mis primeros pasos en la maquetación, el diseño y la estructuración de sitios web.

---

## ✨ Características

- **Navegación flotante:** menú fijo con efecto *glass* (desenfoque), navegación por anclas y resaltado del enlace activo.
- **Sección de inicio (hero):** presentación personal y botón de descarga del CV.
- **Sobre mí:** información personal, formación académica y enfoque actual.
- **Tecnologías & habilidades:** tarjetas organizadas en *Formación Académica* (Java, C#, PostgreSQL) y *Aprendizaje Autónomo* (Python, HTML5, CSS3).
- **Contacto:** accesos directos a WhatsApp, correo y GitHub con iconos representativos.
- **Diseño oscuro con acentos morados:** tipografía *Outfit*, gradiente radial de fondo y microanimaciones al pasar el cursor.
- **Scroll suave:** desplazamiento animado entre secciones (`scroll-behavior: smooth`).

---

## 🛠️ Tecnologías

| Categoría | Detalle |
| --- | --- |
| Lenguajes | HTML5, CSS3 |
| Interactividad | JavaScript (script para marcar el enlace activo del menú) |
| Estilos | Flexbox, gradientes, `backdrop-filter`, transiciones |
| Tipografía | Google Fonts — *Outfit* |
| Iconos | Boxicons y Devicon |
| Herramientas | Editor de código + Git/GitHub |

---

## 📦 Estructura del proyecto

```
Portafolio/
├── index.html              # Estructura del sitio (una sola página)
├── style.css               # Estilos y diseño visual
└── assets/
    ├── img/
    │   ├── perfil.jpg          # Foto de perfil (sección Inicio)
    │   └── programacion-2.jpg  # Imagen decorativa (sección Sobre mí)
    └── docs/
        └── CV - Jesús Reyes.pdf # Currículum descargable
```

---

## 📱 Secciones del sitio

| Sección | ID | Contenido |
| --- | --- | --- |
| Inicio | `#inicio` | Presentación, rol y descarga del CV |
| Sobre mí | `#sobremi` | Datos personales, educación y experiencia |
| Tecnologías | `#stack` | Habilidades en tarjetas por área |
| Proyectos | `#proyectos` | *(pendiente de completar)* |
| Contacto | `#contacto` | WhatsApp, correo y GitHub |

---

## 🚀 Cómo verlo

No requiere instalación ni compilación. Tienes dos opciones:

1. **Abrir directamente** el archivo `index.html` con doble clic en tu navegador.
2. **Servidor local** (recomendado para que se resuelvan bien las rutas de los recursos):

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000` en el navegador.

---

## 📋 Próximos pasos (mejoras previstas)

- [ ] Completar la sección **Proyectos** con tarjetas de trabajos reales.
- [ ] Hacer el diseño **responsive** (media queries para móvil y tablet), ya que hoy está pensado para pantallas de escritorio.
- [ ] Implementar resaltado automático del enlace activo al hacer scroll (*scroll-spy* con `IntersectionObserver`).
- [ ] Añadir un formulario de contacto propio.
- [ ] Publicar el sitio con **GitHub Pages**.

---

## 🎓 Contexto

**Primer proyecto de desarrollo web**, realizado como parte de mi aprendizaje autónomo de HTML y CSS mientras curso la carrera de Ingeniería de Software. Más que un producto terminado, es el punto de partida de mi camino en el desarrollo web: me permitió entender cómo se estructura una página, cómo se enlazan los estilos y cómo se construye una interfaz desde cero.

---

## 📄 Licencia

Proyecto personal de uso educativo y de portafolio. El contenido, las imágenes y el CV son de uso personal.
