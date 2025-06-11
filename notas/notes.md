> No olvidemos que podemos movernos entre las versiones anteriores de node
> 

### Inicialización Rápida

`npm init` → Inicializar con las configuraciónes de node 

---

### 1. **Tipos de Exportaciones** 🔄

**CommonJS** 📦

- Usa `require` y `module.exports`.
- **Extensión**: `.js`.
- **Ejecuta** de manera **síncrona**.
- Es el sistema predeterminado en Node.js.

**ES Modules** 📂

- Usa `import` y `export`.
- **Extensión**: `.mjs` o `.js` (si tienes `"type": "module"` en `package.json`).
- Es **asíncrona** por diseño.
- Introducido en **Node 12** y **estable** desde **Node 14**.

---

## 2. **Módulos Nativos** 🛠️

Node.js viene con varios módulos integrados, como:

- **`fs`**: Interactúa con el sistema de archivos (File System).
- **`http`**: Para crear servidores HTTP (servicios HTTPS).
- **`path`**: Para trabajar con rutas de archivos.
- **`os`**: Para obtener información sobre el sistema operativo.

## 3. **Módulos de Terceros** 🧑‍💻

- Puedes instalar **módulos externos** con: `npm install <name>`
- Algunos módulos básicos y populares son:
    - **`express`**: Framework para servidores web.
    - **`lodash`**: Utilidades para trabajar con objetos y arrays.
    - **`dotenv`**: Maneja variables de entorno.

---

---

## 🧑‍💻 **Recomendación**:

Aunque puedes usar ambos tipos de módulos, **se recomienda usar ES Modules** (`import/export`), ya que es el futuro y proporciona una mejor compatibilidad con otras herramientas.

---

<aside>
🤸🏽

> **TIP:** Podemos agregar en nuestro `package.json` en la parte de `scripts` la linea `"start": "node index.js"` que nos ayuda a correr el comando directamente con **`npm run start`**
> 
</aside>

---

## Ahora vamos a CREAR un paquete, VALIDARLO y PUBLICARLO

Primero tenemos que definir que es lo que va a hacer nuestro paquete. Definir la funciónes que se vana a expertar, hacer un readme.md y antes de publicarlo tenemos que probar si es que este funciona o no funciona. Con alugnos comando como `npm link` que nos permite utilizar el paquete de forma LOCAL sin instalarlo. Y despues en otro proyecto podemos poner `npm <nombreDeMiPaquete>` esto nos permite instalarlo si hacer el install realmente y aquí hacemos las pruebas correspondientes. Da el ejemplo de poner `const dateFormat = require('platzidate');` y algo interesante es que podemos ver el PESO de los paquetes con un pluggin y que debería estar en node_modules

> No olvidemos que podemos movernos entre las versiones anteriores de node
> 

### Inicialización Rápida

`npm init` → Inicializar con las configuraciónes de node 

---

### 1. **Tipos de Exportaciones** 🔄

**CommonJS** 📦

- Usa `require` y `module.exports`.
- **Extensión**: `.js`.
- **Ejecuta** de manera **síncrona**.
- Es el sistema predeterminado en Node.js.

**ES Modules** 📂

- Usa `import` y `export`.
- **Extensión**: `.mjs` o `.js` (si tienes `"type": "module"` en `package.json`).
- Es **asíncrona** por diseño.
- Introducido en **Node 12** y **estable** desde **Node 14**.

---

## 2. **Módulos Nativos** 🛠️

Node.js viene con varios módulos integrados, como:

- **`fs`**: Interactúa con el sistema de archivos (File System).
- **`http`**: Para crear servidores HTTP (servicios HTTPS).
- **`path`**: Para trabajar con rutas de archivos.
- **`os`**: Para obtener información sobre el sistema operativo.

## 3. **Módulos de Terceros** 🧑‍💻

- Puedes instalar **módulos externos** con: `npm install <name>`
- Algunos módulos básicos y populares son:
    - **`express`**: Framework para servidores web.
    - **`lodash`**: Utilidades para trabajar con objetos y arrays.
    - **`dotenv`**: Maneja variables de entorno.

---

---

## 🧑‍💻 **Recomendación**:

Aunque puedes usar ambos tipos de módulos, **se recomienda usar ES Modules** (`import/export`), ya que es el futuro y proporciona una mejor compatibilidad con otras herramientas.

---

<aside>
🤸🏽

> **TIP:** Podemos agregar en nuestro `package.json` en la parte de `scripts` la linea `"start": "node index.js"` que nos ayuda a correr el comando directamente con **`npm run start`**
> 
</aside>

---

## Ahora vamos a CREAR un paquete, VALIDARLO y PUBLICARLO

Primero tenemos que definir que es lo que va a hacer nuestro paquete. Definir la funciónes que se vana a expertar, hacer un readme.md y antes de publicarlo tenemos que probar si es que este funciona o no funciona. Con alugnos comando como `npm link` que nos permite utilizar el paquete de forma LOCAL sin instalarlo. Y despues en otro proyecto podemos poner `npm <nombreDeMiPaquete>` esto nos permite instalarlo si hacer el install realmente y aquí hacemos las pruebas correspondientes. Da el ejemplo de poner `const dateFormat = require('platzidate');` y algo interesante es que podemos ver el PESO de los paquetes con un pluggin y que debería estar en node_modules