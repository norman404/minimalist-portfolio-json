
<div align="center">
<h2>
    <em>Résumé</em> minimalista maquetado para web y pdf con soporte multi idioma
</h2>
<p>
    Esquema del JSON de CV de <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>
<p>
    Basado en el diseño de <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a> y extendido con soporte multi idioma.
</p>
</div>

<div align="center">
    <a href="#🚀-empezar">
        Empezar
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🧞-comandos">
        Comandos
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="https://cv.molcajete.dev">
        Personal
    </a>
</div>

## 🛠️ Stack
- [**Astro**](https://astro.build/) - El framework web de la nueva época.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript con sintaxis de tipado.
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Menú desplegable con atajos de teclado hecho en puro Javascript.

## 🚀 Empezar

### 1. Usa este [repo](https://github.com/norman404/minimalist-portfolio-json) como _template_ de un proyecto de Astro

- Este proyecto utiliza `npm` como gestor de dependencias.

```bash
# Clona el repositorio
git clone https://github.com/norman404/minimalist-portfolio-json
cd minimalist-portfolio-json

# Instala las dependencias
npm install

# Inicializa el proyecto
npm run setup
```

### 2. Añade tu contenido:
Edita los archivos `cv.json` y `cv-es.json` para crear tu propio Portafolio/CV imprimible en inglés y español respectivamente.

### 3. Lanza el servidor de desarrollo:

```bash
# Disfruta del resultado
npm run dev
```

1. Abre [**http://localhost:4321**](http://localhost:4321/) en tu navegador para ver el resultado 🚀

## 🧞 Comandos

|     | Comando          | Acción                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `dev` o `start` | Lanza un servidor de desarrollo local en  `localhost:4321`.  |
| ⚙️  | `build`          | Comprueba posibles errores y hace un empaquetado de producción en `./dist/`.      |
| ⚙️  | `preview`        | Vista previa en local `localhost:4321` |
