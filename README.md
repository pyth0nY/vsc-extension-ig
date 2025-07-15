# vsc-extension-ig
# IG Presence Connector para VSCode 🚀

 <!-- Reemplaza esta URL con la de tu propio icono si tienes una -->

¡Lleva tu "Rich Presence" al siguiente nivel! Esta extensión conecta tu actividad de Visual Studio Code con la extensión **[IG Presence para Chrome](https://github.com/pyth0nY/instagramPresent)**, permitiendo que tus amigos en Instagram vean en qué archivo y lenguaje estás programando, en tiempo real.

Inspirado en el Rich Presence de Discord, pero llevado directamente a tu perfil de Instagram.

---

## ✨ Características

*   **Actividad en Tiempo Real:** Muestra el archivo y el lenguaje en el que estás trabajando.
*   **Totalmente Integrado:** Se comunica a través de una base de datos central (Supabase) con la extensión de Chrome.
*   **Inteligente y Eficiente:** Solo envía actualizaciones cuando cambias de archivo o después de un par de segundos de inactividad para no saturar la red.
*   **Fácil de Configurar:** Un solo clic para configurar tu nombre de usuario.
*   **Privacidad:** La extensión solo actualiza el estado en la base de datos; al cerrar VSCode, la actividad de programación desaparece.

---

## ⚙️ Cómo Funciona

Esta extensión es una de las dos piezas del sistema IG Presence:

1.  **Extensión para VSCode (esta):** Detecta tu actividad de programación y la envía a la base de datos de Supabase.
2.  **Extensión para Chrome:** Lee tu estado y el de tus amigos de la base de datos y lo muestra en una UI flotante dentro de Instagram.

Ambas extensiones son necesarias para que la experiencia sea completa.

---

## 🚀 Guía de Instalación y Configuración

Instalar y poner en marcha IG Presence es muy fácil. ¡Sigue estos pasos!

### 1. Instala la Extensión de Chrome

Primero, necesitas la extensión principal que se encarga de mostrar la actividad en Instagram.
> 🔗 **[Descarga la extensión para Chrome aquí](URL_A_TU_EXTENSION_DE_CHROME_AQUI)** *(¡Importante! Reemplaza este enlace cuando la publiques)*

### 2. Instala esta Extensión para VSCode

Puedes instalarla directamente desde el Marketplace de Visual Studio Code buscando **"IG Presence Connector"**.

### 3. Configura tu Usuario

Una vez instalada, la configuración es súper sencilla:

1.  Abre Visual Studio Code.
2.  En la barra de estado de abajo a la izquierda, verás un nuevo icono:
    `$(person) IG Presence: Configurar`
3.  **Haz clic sobre él.**
4.  Aparecerá una caja de texto en la parte superior. **Introduce tu nombre de usuario de Instagram** (el mismo que usas en la red social, por ejemplo, `kasuto_16`).
5.  ¡Presiona Enter y listo!

 <!-- Un GIF aquí quedaría genial. Puedes crear uno con LICEcap o ScreenToGif -->

A partir de ese momento, la extensión comenzará a enviar tu actividad de programación. La barra de estado cambiará a `$(pulse) IG Presence: Programando...` para que sepas que está funcionando.

---

## 🤝 Contribuciones

Este es un proyecto open-source hecho con mucho cariño. Si tienes ideas para mejorarlo, encuentras un bug o quieres añadir nuevas funcionalidades, ¡eres bienvenido! Siéntete libre de abrir un *issue* o un *pull request* en el repositorio de GitHub.

> 🔗 **[Repositorio de GitHub](https://github.com/pyth0nY/vsc-extension-ig) 

---

**¡Disfruta de tu nuevo Rich Presence en Instagram! 🔥**
