# ?? Chichi Burger - Landing Page Oficial

<p align="center">
  <img src="assets/logo.png" alt="Chichi Burger Logo" width="150px" style="border-radius: 50%;" />
</p>

<p align="center">
  <strong>El verdadero antojo de la noche en Cinco Colonias, Mérida.</strong>
</p>

<p align="center">
  <a href="https://vercel.com" target="_blank">
    <img src="https://img.shields.io/badge/Hosted_on-Vercel-black?style=for-the-badge&logo=vercel" alt="Vercel Badge" />
  </a>
  <img src="https://img.shields.io/badge/Made_with-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind Badge" />
  <img src="https://img.shields.io/badge/Language-HTML5/JS-orange?style=for-the-badge" alt="HTML/JS Badge" />
  <img src="https://img.shields.io/badge/PWA-Ready-purple?style=for-the-badge&logo=pwa" alt="PWA Ready Badge" />
</p>

---

## ?? Descripción del Proyecto

Este repositorio contiene la **Landing Page Oficial de Chichi Burger**, una aplicación web de una sola página (Single Page Application) diseñada con un enfoque moderno, premium y de alta conversión. Su propósito es servir como el canal digital informativo y de pedidos del negocio ubicado en la colonia Cinco Colonias, en Mérida, Yucatán.

La página cuenta con una interfaz responsiva, una estética oscura sofisticada (carbón, brasa y mostaza) y múltiples llamados a la acción (CTAs) que redirigen al usuario directo a realizar su orden mediante **WhatsApp**, optimizando las ventas en su modalidad de Pick Up. Recientemente optimizada para ofrecer una experiencia de usuario idéntica a la de una aplicación nativa móvil.

---

## ? Características Destacadas

### ?? Experiencia App Móvil (UX/UI Avanzada)
*   **PWA Ready:** Archivo `manifest.json` integrado. Los usuarios pueden instalar la página en su pantalla de inicio en iOS/Android como una aplicación nativa.
*   **Animaciones Fade-Up al Scroll:** Implementación nativa con `IntersectionObserver` que revela las secciones y tarjetas del menú suavemente mientras el usuario hace scroll, creando una experiencia dinámica y premium.
*   **Menú Drawer Deslizante:** Navegación móvil optimizada mediante un menú lateral tipo "hamburguesa" con efecto *glassmorphism* que mejora drásticamente la usabilidad en pantallas pequeñas.
*   **Retroalimentación Táctil (Active States):** Botones y elementos interactivos que reaccionan al toque del usuario (`scale-95`), emulando la sensación táctil de las apps nativas.

### ?? Menú Bento Grid Dinámico
*   **Diseño Moderno:** Presentación visual estilo *Bento Grid* para el menú, destacando las categorías principales (Hamburguesas, Hotdogs, Alitas, Fritas).
*   **Acordeones Interactivos:** Permite a los usuarios expandir cada producto para ver sus ingredientes detallados sin sobrecargar la pantalla visualmente.
*   **Nuevas Adiciones:** Incluye la reciente integración de *Alitas*, *Boneless* (con selección de sabores como BBQ, Buffalo, Mango Habanero) y *Papanachos*.

### ? Utilidades y Conversión
*   **Conversión Rápida por WhatsApp:** Botones de orden estratégicos en la cabecera, hero section y menú drawer.
*   **Indicador de Horario en Tiempo Real:** Un badge en la sección de ubicación que muestra el estado ("Está por abrir", "Abierto", "Cerrado") calculado en vivo con JavaScript.
*   **Integración de Google Maps:** Mapa embebido y botón "Cómo llegar" directo a la ubicación exacta de la sucursal.
*   **Preguntas Frecuentes (FAQ):** Sección clara sobre métodos de pago, tiempos de entrega y ausencia actual de servicio a domicilio.

---

## ??? Tecnologías Utilizadas

*   **HTML5** - Estructura semántica del sitio web.
*   **Tailwind CSS** - Framework de utilidades CSS integrado vía CDN con paleta de colores (`ember`, `mustard`, `char`) y animaciones personalizadas en el script de configuración.
*   **JavaScript (ES6)** - Lógica interactiva nativa (Vanilla JS) para el menú Drawer, Acordeones, Intersection Observer y estado de horario en vivo. Ninguna dependencia externa pesada.
*   **Vercel** - Optimización y configuración lista (`vercel.json`) para hosting estático de alto rendimiento.

---

## ?? Estructura del Proyecto

```text
ChichiBurguer/
+-- assets/
¦   +-- favicon/              # Favicons oficiales e íconos para PWA
¦   +-- logo.png              # Logotipo oficial del negocio
¦   +-- burgers_and_hotdogs.png # Imagen optimizada del Hero
+-- index.html                # Código fuente principal de la Landing Page
+-- manifest.json             # Manifiesto de PWA para instalación móvil
+-- vercel.json               # Configuración de rutas y caché para Vercel
+-- README.md                 # Documentación del proyecto
```

---

## ?? Cómo Ejecutar Localmente

Dado que el proyecto está construido con tecnologías web nativas, no necesitas herramientas complejas de compilación:

1.  **Clona este repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/ChichiBurguer.git
    ```
2.  **Entra a la carpeta del proyecto:**
    ```bash
    cd ChichiBurguer
    ```
3.  **Ejecuta el servidor:**
    Abre el archivo `index.html` en tu navegador o utiliza **Live Server** (en VS Code) para probar las funcionalidades como PWA y Service Workers correctamente.

---

## ?? Despliegue en Vercel

1. Instala el CLI de Vercel (opcional):
   ```bash
   npm i -g vercel
   ```
2. Ejecuta el comando de despliegue en la raíz del proyecto:
   ```bash
   vercel --prod
   ```

---

## ?? Chichi Burger Información de Negocio
*   **Ubicación:** C. 111 entre 48 y 50, Cinco Colonias, 97280 Mérida, Yuc.
*   **Horario:** Lunes a Domingo, de 7:00 p.m. a 12:00 a.m.
*   **Modalidad de Servicio:** Pick Up (Recoger en sucursal - sin servicio a domicilio por el momento).
*   **Métodos de Pago:** Efectivo, Transferencia y Tarjeta de Débito/Crédito.
*   **Contacto (WhatsApp):** [+52 999 304 3753](https://wa.me/529993043753)
*   **Redes Sociales:** [Facebook](https://www.facebook.com/people/Chichi-Burguer/61591155090389/) | [Instagram](https://www.instagram.com/oficialchichiburguer/) | [TikTok](https://www.tiktok.com/@chichiburgueroficial?lang=es)
