# 🗺️ Rutas Cam - Tráfico Catalunya

Una aplicación web interactiva que permite a los usuarios visualizar el mapa de carreteras de Cataluña y consultar en tiempo real (simulado) las cámaras de tráfico activas a lo largo de una ruta específica.

## ✨ Características Principales

* **Mapa Interactivo:** Desarrollado con Leaflet y mapas de OpenStreetMap (estilo CARTO) para una visualización clara y rápida.
* **Cálculo de Rutas en Vivo:** Haz clic en cualquier punto del mapa y la aplicación trazará automáticamente la ruta en coche desde el origen (Roda de Barà) hasta el destino seleccionado.
* **Detección Inteligente de Cámaras:** El sistema analiza las coordenadas de la ruta calculada y detecta qué cámaras de tráfico se encuentran en un radio de menos de 10 km de tu trayecto.
* **Panel de Visualización Lateral:** Una barra lateral con diseño moderno y modo oscuro (Dark Mode) que muestra el estado "En Vivo" (LIVE) de las cámaras detectadas en tu ruta.
* **Totalmente Responsivo:** Interfaz adaptable construida con Tailwind CSS.

## 🛠️ Tecnologías Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla).
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (vía CDN).
* **Mapas y Geometría:** [Leaflet JS](https://leafletjs.com/).
* **Enrutamiento:** [Leaflet Routing Machine](https://www.liedman.net/leaflet-routing-machine/).

## 🚀 Cómo usar este proyecto localmente

Dado que es una aplicación que funciona íntegramente del lado del cliente (Frontend), no necesitas instalar dependencias complicadas ni levantar un servidor de base de datos.

1. Clona el repositorio en tu equipo:
   ```bash
   git clone https://github.com/Mangel-Gare/rutas-cam.git
   ```
2. Entra en la carpeta del proyecto:
   ```bash
   cd rutas-cam
   ```
3. Abre el archivo `index.html` directamente en tu navegador web favorito (Chrome, Firefox, Safari, Edge).

## 🌐 Despliegue en GitHub Pages

Este proyecto está preparado para alojarse de forma gratuita usando GitHub Pages. 
Para activarlo:
1. Ve a la pestaña **Settings** de tu repositorio.
2. Navega hasta la sección **Pages** en la barra lateral izquierda.
3. En **Source**, selecciona la rama `main` (o `master`) y guarda.
4. En unos minutos, tu página estará disponible públicamente.

## 📝 Notas sobre los Datos

*Actualmente, las coordenadas de las cámaras y las imágenes en tiempo real utilizan datos de prueba y marcadores de posición (`placehold.co`) para demostrar la funcionalidad y la interfaz. Para un entorno de producción real, se requeriría conexión directa a la API de Servei Català de Trànsit (SCT) o la DGT.*

---
*Desarrollado para facilitar la planificación de viajes por carretera en Cataluña.*