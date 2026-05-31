# Desafío 3: Electric Car Store 🚗⚡

¡Bienvenido al repositorio de **Electric Car Store**! Este proyecto es una interfaz web moderna, responsiva y optimizada para la visualización y filtrado de vehículos eléctricos. El desarrollo se ha realizado aplicando metodologías modernas de maquetación en CSS, garantizando una experiencia de usuario fluida en cualquier dispositivo.

---
## ⚡ Previsualización

   [![Sitio Web](https://img.shields.io/badge/Demo-Sitio_En_Vivo-brightgreen?style=for-the-badge&logo=githubpages&logoColor=white)](https://jleival.github.io/desafio-3-electric-car-store/)
   [![GitHub Repository](https://img.shields.io/badge/GitHub-Repositorio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jleival/desafio-3-electric-car-store)

---
## 📱 Vista Previa del Proyecto (Responsive Design)

A continuación se presentan las capturas de pantalla de la interfaz de la tienda adaptada a diferentes resoluciones de pantalla:

### 🖥️ Vista de Escritorio (Desktop)
*Diseño con menú lateral persistente y cuadrícula completa de productos (4 columnas).*

![Vista de Escritorio](escritorio.png)

---

### 📑 Vista de Tablet
*El menú se traslada a la parte superior y la barra de ordenamiento se posiciona a la izquierda, reduciendo la cuadrícula a 2 columnas.*

![Vista de Tablet](Tablet.png)

---

### 📱 Vista de Móvil (Mobile)
*Diseño compacto con menú de navegación colapsable (hamburguesa) y flujo de productos en una sola columna para mejorar la experiencia táctil.*

![Vista de Móvil](mobil.png)
---

## 🚀 Características del Proyecto

* **Enfoque Mobile-First:** El diseño fue estructurado inicialmente para pantallas móviles y escalado progresivamente hacia resoluciones mayores mediante *Media Queries*.
* **Arquitectura CSS Grid:** Se utiliza `grid-template-areas` para gestionar de forma robusta la distribución del Layout en sus diferentes versiones.
* **Diseño 100% Responsivo:** Adaptación fluida para tres puntos de quiebre principales: Celular, Tablet y Escritorio de pantalla ancha.
* **Iconografía Integrada:** Uso de la librería de vectores tipográficos **Material Design Icons (MDI)**.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructuración semántica utilizando etiquetas de bloque como `<nav>`, `<main>`, `<article>` y `<footer>`.
* **CSS3:** Flexbox (para componentes internos) y CSS Grid (para la estructura del layout global).
* **Material Design Icons:** Para los elementos visuales e iconos de la marca y redes sociales.

---

## 📐 Estructura del Layout y Adaptabilidad

El proyecto reordena dinámicamente sus secciones principales (`nav`, `ordenar-contenedor`, `main`, `footer`) según el tamaño del dispositivo:

### 1. Vista Móvil (Por defecto)
* **Layout:** Una sola columna vertical fluida.
* **Menú:** El menú de navegación clásico se oculta para dar paso a un menú de hamburguesa (`.menu-hamburguesa`).
* **Grilla:** Los productos se muestran en formato de lista de 1 columna.

### 2. Vista Tablet (`576px` a `991px`)
* **Layout:** Estructura mixta. El filtro de ordenamiento se transforma en una barra lateral izquierda fija al lado del contenido principal.
* **Navegación:** Se despliega el menú horizontal superior completo.
* **Grilla:** Los productos se reestructuran automáticamente en **2 columnas**.

### 3. Vista Escritorio (`992px` en adelante)
* **Layout:** Estructura avanzada de 2 columnas principales. El menú (`nav`) se convierte en una barra lateral vertical izquierda de pantalla completa.
* **Filtros:** El contenedor de ordenamiento se posiciona en la parte superior del contenido central.
* **Grilla:** Distribución óptima de productos en **4 columnas fluidas**.
* **Footer:** Fijado de forma estable en la base de la barra lateral izquierda.

---

## 📁 # Estructura del Proyecto

```text
├── index.html                # Archivo HTML principal
└── assets/
    ├── css/
    │   └── style.css         # Estilos globales y Media Queries
    └── img/
        └── city-car.png      # Mockup de vehículo para las tarjetas
```

## Crear la estructura desde la terminal

```bash
mkdir -p assets/css assets/img
touch index.html assets/css/style.css assets/img/city-car.png
```
---
## ⚙️ Instrucciones de Instalación y Uso
Para ejecutar este proyecto de forma local, sigue estos sencillos pasos:

1. Clona este repositorio:
git clone https://github.com/jleival/desafio-3-electric-car-store.git

2. cd desafio-3-electric-car-store
3. Abre el proyecto:
Simplemente haz doble clic sobre el archivo index.html o utiliza extensiones de servidor local como Live Server en VS Code para visualizarlo en tiempo real.

---

## ✒️ Licencia
Este proyecto fue desarrollado por **Jorge Leiva** con fines educativos como parte de un desafío técnico de maquetación web para **Desafío Latam**. Sientete libre de usarlo como base para tus propios desarrollos.
