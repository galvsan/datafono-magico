# Restaurante "Casa Adrián" - TPV Infantil

Una aplicación web progresiva (PWA) diseñada para que los niños jueguen a gestionar su propio restaurante. Es una herramienta educativa y divertida que simula un sistema de Punto de Venta (TPV) real con un diseño moderno y amigable.

## 🚀 Características principales

- **Menú de Productos**: Más de 50 productos organizados por categorías (Comida, Bebidas, Postres, Frutas).
- **Categorías Dinámicas**: Sistema de filtrado por "chips" para encontrar fácilmente cada producto.
- **Gestión de Pedidos**: Carrito de compras interactivo donde se pueden añadir y quitar productos, viendo el total en tiempo real.
- **Simulación de Cobro**:
  - **Efectivo**: Calculadora automática de cambio con botones de acceso rápido para billetes y monedas.
  - **Tarjeta (Contactless)**: Simulación de pago con animación NFC y soporte real para Web NFC API (en dispositivos compatibles).
- **Ticket Hiperrealista**: Generación de un ticket de compra con diseño de papel térmico, ubicado en Santa Cruz de Tenerife.
- **Compartir por WhatsApp**: Capacidad de capturar el ticket como imagen y compartirlo directamente por WhatsApp.
- **PWA (App Instalable)**: Se puede instalar en la pantalla de inicio tanto en Android como en iOS para una experiencia inmersiva.
- **Modo Offline**: Funciona sin conexión a internet gracias a su Service Worker.

## 🛠️ Tecnologías utilizadas

- **HTML5 & CSS3**: Diseño responsive y moderno.
- **JavaScript (Vanilla)**: Lógica de la aplicación sin dependencias pesadas.
- **html2canvas**: Para la captura del ticket como imagen.
- **Web Share API**: Para compartir el ticket de forma nativa.
- **PWA**: Service Workers y Web App Manifest.

## 📂 Estructura del proyecto

- `index.html`: El núcleo de la aplicación (vistas, lógica y estilos).
- `products.json`: Base de datos de productos.
- `manifest.json`: Configuración para la instalación como PWA.
- `sw.js`: Service Worker para el funcionamiento offline.

## 📱 Instalación

1. Abre la URL de la aplicación en Chrome (Android) o Safari (iOS).
2. Selecciona **"Añadir a la pantalla de inicio"**.
3. ¡Disfruta jugando en el Restaurante "Casa Adrián"!

---
*Desarrollado con ❤️ para jugar y aprender.*
