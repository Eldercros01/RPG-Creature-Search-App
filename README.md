# RPG Creature Search App

Esta es una aplicación web moderna y responsiva que permite buscar criaturas de un RPG por nombre o ID, mostrando sus estadísticas, tipos e imagen. Utiliza la [RPG Creature API de freeCodeCamp](https://rpg-creature-api.freecodecamp.rocks/) para obtener los datos en tiempo real.

## Características

- Búsqueda por nombre o ID de criatura.
- Muestra nombre, ID, peso, altura, HP, ataque, defensa, ataque especial, defensa especial, velocidad, tipos e imagen.
- Mensaje de error si la criatura no existe.
- Interfaz responsiva y atractiva.
- Animaciones suaves con jQuery.
- Estilos modernos usando Sass (SCSS).

## Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/rpg-creature-search-app.git
   cd rpg-creature-search-app
   ```

2. **Instala dependencias (opcional, solo si usas herramientas de desarrollo):**
   ```bash
   npm install
   ```

3. **Compila el SCSS a CSS (si editas los estilos):**
   - Usa la extensión Live Sass Compiler de VS Code, o
   - Ejecuta:
     ```bash
     sass src/styles/style.scss src/styles/style.css
     ```

4. **Abre `index.html` en tu navegador.**

## Uso

- Escribe el nombre (por ejemplo, `Pyrolynx`) o el ID (por ejemplo, `2`) de una criatura y haz clic en **Buscar**.
- Si la criatura existe, verás sus datos y su imagen.
- Si no existe, aparecerá un mensaje de "Creature not found".

## Tecnologías

- HTML5
- CSS3 / Sass (SCSS)
- JavaScript (ES6)
- jQuery
- [RPG Creature API](https://rpg-creature-api.freecodecamp.rocks/)

## Créditos

- API y desafío por [freeCodeCamp](https://www.freecodecamp.org/).
- Diseño y desarrollo: [Eric Montero].

---

¡Disfruta buscando criaturas RPG!