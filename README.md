# 🌟 **AsciiShadow**: Generador de Texto en Formato Sombra ASCII 🌟

**AsciiShadow** es una herramienta poderosa y flexible para generar texto en formato ASCII con un estilo de sombra. Utiliza caracteres ASCII para crear una representación visual impactante de tu texto. ¡Convierte tu texto en arte ASCII de manera sencilla!

## 🚀 Características

- 🖤 Convierte texto simple en una representación visual de sombra utilizando el estilo ASCII.
- 🎨 **Personalización**: Modifica el diccionario de fuentes para adaptarlo a diferentes estilos de sombra.
- ⚡ Fácil de usar desde la línea de comandos.
- 🧑‍💻 Compatible con cualquier tipo de texto (mayúsculas y minúsculas).
- 📜 Basado en el formato ASCII, ideal para proyectos, presentaciones o simplemente para darle un toque artístico al texto.

## 🛠️ Instalación

### Requisitos

Para usar **AsciiShadow**, necesitarás tener Python 3.x instalado en tu sistema. Además, el script utiliza la biblioteca estándar `argparse`, que facilita el manejo de argumentos en la línea de comandos. Asegúrate de que esté instalada (aunque en la mayoría de las versiones modernas de Python ya lo está).

### Pasos de Instalación

1. **Clona o descarga el repositorio**:

   ```bash
   git clone https://github.com/tuusuario/asciishadow.git
   ```

2. **Accede al directorio del proyecto**:

   ```bash
   cd asciishadow
   ```

3. **Instala la librería `argparse`** (si no la tienes instalada):

   ```bash
   pip install argparse
   ```

   Asegúrate de que Python 3.x esté instalado en tu sistema.

## 💻 Uso

### Ejecutar el generador de sombra desde la línea de comandos:

1. Abre la terminal o línea de comandos.
2. Navega al directorio donde se encuentra el archivo `asciishadow.py`.
3. Ejecuta el siguiente comando, proporcionando el texto que deseas convertir en formato sombra:

   ```bash
   python asciishadow.py "Texto a convertir"
   ```

   **Ejemplo**:

   ```bash
   python asciishadow.py "Hola Mundo"
   ```

   Esto generará una salida similar a la siguiente (dependiendo del diccionario de sombra definido):

  ```
  ██╗  ██╗   ██████╗   ██╗        █████╗
  ██║  ██║  ██╔═══██╗  ██║       ██╔══██╗
  ███████║  ██║   ██║  ██║       ███████║
  ██╔══██║  ██║   ██║  ██║       ██╔══██║
  ██║  ██║  ╚██████╔╝  ███████╗  ██║  ██║
  ╚═╝  ╚═╝   ╚═════╝   ╚══════╝  ╚═╝  ╚═╝
  ```

### Argumentos

- **texto**: El texto que se convertirá en su versión de sombra en formato ASCII.

## ✨ Personalización

Puedes personalizar el estilo de las sombras editando el diccionario `shadow_font` en el código. Este diccionario contiene las representaciones gráficas de cada carácter en forma de lista de cadenas. Cada lista representa una fila de caracteres para un carácter específico.

## 📜 Licencia

Este proyecto está bajo la licencia [MIT License](LICENSE).
