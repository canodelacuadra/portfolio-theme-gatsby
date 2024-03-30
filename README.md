<p align="center">
  <a href="https://cara.lekoarts.de">
    <img alt="LekoArts" src="https://img.lekoarts.de/gatsby/gatsby-site-illustration.png" />
  </a>
</p>
<h1 align="center">
  Gatsby Starter Portfolio: Cara
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-starter-portfolio-cara/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-0BSD-blue.svg" alt="Gatsby Starter Portfolio: Cara is released under the 0BSD license." />
  </a>
  <a href="https://github.com/sponsors/LekoArts">
    <img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/LekoArts">
  </a>
  <a href="https://www.lekoarts.de?utm_source=cara&utm_medium=Starter">
    <img alt="Website" src="https://img.shields.io/badge/-website-blue">
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=lekoarts_de">
    <img src="https://img.shields.io/twitter/follow/lekoarts_de.svg?label=Follow%20@lekoarts_de" alt="Follow @lekoarts_de" />
  </a>
</p>

Portafolio divertido y colorido de una página con efectos y animaciones de Parallax. Usando el tema Gatsby [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

[**Demo Website**](https://cara.lekoarts.de)

Also be sure to check out other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de) and my [Personal Website](https://www.lekoarts.de?utm_source=cara&utm_medium=Starter).

## ✨ Features

- Theme UI-based theming
- react-spring Parallax Effect
- CSS Animations on Shapes

## ⏱️ Quick Start

Deploy this starter with one click on [Netlify](https://app.netlify.com/signup):

[<img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" />](https://app.netlify.com/start/deploy?repository=https://github.com/LekoArts/gatsby-starter-portfolio-cara)

## 🚀 Getting Started

### 1. **Crear un sitio  Gatsby .**

Use the Gatsby CLI to clone the site and install dependencies:

```sh
npx gatsby new gatsby-starter-portfolio-cara https://github.com/LekoArts/gatsby-starter-portfolio-cara
```

### 2. **Navegar hasta el nuevo proyecto**

```sh
cd gatsby-starter-portfolio-cara
```

### 3. **Lanzar una previsualización para poder personalizarlo**

Puede ver el sitio lanzando `npm run develop`.

Su sitio está corriendo en  `http://localhost:8000`!

Si desea obtener más información sobre cómo puede utilizar un iniciador de Gatsby configurado con un tema de Gatsby, puede consultar este tutorial  [shorter](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/using-a-gatsby-theme/) o [longer](https://www.gatsbyjs.com/tutorial/using-a-theme/) . Los tutoriales no se aplican exactamente a este iniciador, sin embargo, los conceptos son los mismos.

## 📝 Usando y modificando este theme starter

**Nota Importante:** Por favor,lea la guía [Shadowing in Gatsby Themes](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/) para entender cómo personalizar el tema subyacente!
> El sombreado o "Shadowing" en themes del marco JS Gatsby es una técnica poderosa que te permite personalizar partes específicas de un tema sin necesidad de modificarlo directamente. Te permite "superponer" tus propios archivos sobre los del tema, reemplazando o modificando su comportamiento.

#### ¿Qué puedes sombrear?

* Componentes: Puedes reemplazar componentes del tema por tus propios componentes personalizados.
* Estilos: Puedes modificar los estilos del tema, ya sea redefiniendo variables o creando nuevos estilos.
* Requisitos de datos (consultas GraphQL): Puedes modificar las consultas GraphQL que utiliza el tema para obtener datos.
¿Cómo funciona el sombreado?

El sombreado se basa en una convención de nombres simple. Para sombrear un archivo del tema, debes crear un archivo con el mismo nombre en una ubicación específica dentro de tu proyecto Gatsby. La ubicación del archivo sombreado depende del tipo de archivo que deseas modificar:

- Componentes: src/gatsby-theme-<nombre-del-tema>/components/<nombre-del-componente>.js
- Estilos: src/gatsby-theme-<nombre-del-tema>/styles/<nombre-del-archivo-de-estilos>.js
- Requisitos de datos (consultas GraphQL): src/gatsby-theme-<nombre-del-tema>/data/queries/<nombre-de-la-consulta>.js


>> Supongamos que estás usando el tema gatsby-theme-blog y deseas modificar el componente Bio. Para hacerlo, puedes crear un archivo llamado src/gatsby-theme-blog/components/bio.js en tu proyecto Gatsby. Este archivo reemplazará el componente Bio del tema por tu propia versión personalizada.

#### Beneficios del sombreado:

- Personalización flexible: Te permite personalizar tu sitio web sin necesidad de modificar el código del tema.
- Mantenimiento sencillo: Tus cambios se mantienen separados del código del tema, lo que facilita la actualización del tema sin perder tus personalizaciones.
- Escalabilidad: Puedes sombrear tantos archivos como necesites para personalizar tu sitio web.


Este iniciador crea un nuevo sitio Gatsby que instala y configura el tema. [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

Eche un vistazo al archivo README y a los archivos del tema para ver qué opciones están disponibles y cómo puede observar los diversos componentes, incluida la interfaz de usuario del tema. En términos generales, querrás colocar tus archivos en `src/@lekoarts/gatsby-theme-cara/` 
para ocultar/anular archivos. La configuración de la interfaz de usuario del tema se puede configurar ocultando sus archivos en`src/gatsby-plugin-theme-ui/`.

### Changing content

El contenido de este proyecto se define en cuatro archivo `.mdx` dentro del directorio   ` sections` del theme's . You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. Este starter ya ha creado sobreescrito todos los archivos de origen y podemos sobreescribirlos.

Puede usar los componentes  `<ProjectCard />` dentro de  `projects.mdx` para mostrar las cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### Cambiar los archivos de tu directorio  `static` 

El directorio  `static` contiene los iconos, imagenes de redes sociales y  `robots.txt`. ¡No olvides cambiar estos archivos también! Puedes usar [Real Favicon Generator](https://realfavicongenerator.net/) para generar archivos de imagen e incorporarlos a  `static`.

## 🤔 Problemas o preguntas?

If you have general questions or need help with Gatsby, please go to one of the [support platforms](https://www.gatsbyjs.com/contributing/community/#where-to-get-support) mentioned in Gatsby's documentation. If you have a specific question about this project, you can head to the [GitHub Discussions](https://github.com/LekoArts/gatsby-themes/discussions) of the repository.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on Gatsby's website](https://www.gatsbyjs.com/).

### Themes

Pueedes aprender más de los temas de Gatsby, Recomendamos chequear [theme docs](https://www.gatsbyjs.com/docs/themes/).

### General

- **For most developers, I recommend starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/docs/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to Gatsby's documentation](https://www.gatsbyjs.com/docs/).** In particular, check out the _How-to Guides_ and _Reference_ items in the primary navigation.

## 🌟 Supporting me

Thanks for using this project! I'm always interested in seeing what people do with my projects, so don't hesitate to tag me on [Twitter](https://twitter.com/lekoarts_de) and share the project with me.

Please star this project, share it on Social Media or consider supporting me on [GitHub Sponsors](https://github.com/sponsors/LekoArts)!
