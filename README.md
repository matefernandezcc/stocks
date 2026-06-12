# 💰 Stocks - Calculadora de Inversión 70/20/10

¡Bienvenido a **Stocks**, tu gestor personal de excedentes y rebalanceo de cartera inteligente! 

Esta aplicación móvil (disponible para Android) te ayuda a tomar el control absoluto de tus finanzas personales aplicando la popular y efectiva **estrategia de inversión 70/20/10**. 

---

## 📈 ¿Qué es la estrategia 70/20/10?
No se trata de ahorrar a ciegas, sino de distribuir de forma inteligente cada excedente (ingresos menos gastos) y mantener tu patrimonio balanceado en tres frentes bien definidos:

1.  **El Fuerte (70% - S&P 500 / SPY)**: El motor de tu riqueza a largo plazo. Invierte en las 500 empresas más grandes de EE.UU. de forma automatizada.
2.  **El Candado (20% - FCIs / Cash / Renta Fija)**: Tu escudo de seguridad. Fondos comunes de inversión de liquidez rápida, bonos o efectivo para emergencias y oportunidades a corto plazo.
3.  **El Laboratorio (10% - Acciones Individuales / Cripto / Oportunidades)**: Tu espacio de experimentación. Activos volátiles con alto potencial de retorno donde puedes tomar riesgos controlados.

---

## ✨ Características Premium de la App

*   **🌓 Modo Oscuro y Claro Dinámico**: Diseñada con una estética moderna ultra-premium con tonos oscuros de espacio profundo y acentos de color vibrantes. Cambia de modo con un simple toque.
*   **📊 Gráficos de Dona SVG Interactivos**: Visualiza en tiempo real cómo se divide tu excedente mensual o cómo está balanceado tu patrimonio actual comparado con tus objetivos ideales.
*   **🧮 Intérprete Matemático en Vivo**: Escribe fórmulas matemáticas directamente en las entradas de texto (ej. `2500+250` o `1200000+198291`) y mira el subtotal calculado al instante, evitando tener que usar otra calculadora para sumar tus cuentas.
*   **💾 Almacenamiento 100% Local y Privado**: Tus datos financieros son tuyos y de nadie más. La app guarda tus configuraciones y montos en el almacenamiento local del dispositivo (`localStorage`), sin servidores externos ni conexiones a la nube.
*   **⚡ Funcionamiento Offline Completo**: Diseñada con Tailwind CSS compilado localmente. La app se abre al instante y funciona al 100% sin necesidad de internet.
*   **📱 Experiencia Móvil Nativa**:
    *   **Haptic Feedback**: Micro-vibraciones táctiles al tocar botones o ajustar valores.
    *   **Barra de Estado Adaptativa**: Sincronización del color de la barra superior de Android con el tema del teléfono.
    *   **Botones de Ajuste Rápido**: Suma valores rápidamente (`+500`, `+1k`, `+10k`, etc.) con controles cómodos para usar la pantalla con una sola mano.

---

## 🛠️ Stack Tecnológico
*   **Core**: HTML5 semántico & JavaScript ES6 (Vanilla JS para máximo rendimiento y ligereza).
*   **Estilos**: Tailwind CSS compilado y minificado localmente.
*   **Core Nativo**: Capacitor.js (para la conexión y empaquetado de plugins de Android).
*   **Construcción Móvil**: Gradle & Android SDK.

---

## 🚀 Instalación y Desarrollo Rápido

### Requisitos Previos
*   [Node.js](https://nodejs.org/) (versión 18 o superior)
*   [Android SDK](https://developer.android.com/studio) instalado (para compilar a APK nativo)

### Instrucciones de Configuración
1.  **Clonar el repositorio e instalar dependencias**:
    ```bash
    git clone <tu-repositorio-url>
    cd <directorio-del-proyecto>
    npm install
    ```

2.  **Compilar recursos web (HTML + Tailwind local)**:
    Este comando creará la carpeta `www/` con los recursos optimizados:
    ```bash
    npm run build
    ```

3.  **Sincronizar con Android (Capacitor)**:
    Copia los archivos de la app web al proyecto nativo de Android:
    ```bash
    npm run sync
    ```

4.  **Compilar y construir el APK de prueba**:
    Este script compilará el código de forma automática en un APK para tu teléfono:
    ```bash
    npm run build-apk
    ```
    El archivo APK final se generará en:
    `android/app/build/outputs/apk/debug/app-debug.apk` (y se copiará automáticamente al directorio raíz del proyecto como `app-debug.apk`).

---

## 🔒 Privacidad y Seguridad
Esta aplicación no recopila información personal, no utiliza cookies de seguimiento, no muestra anuncios ni envía ningún tipo de datos financieros por internet. Tus números permanecen únicamente en la memoria local de tu dispositivo móvil.
