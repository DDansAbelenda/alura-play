# Alura Play

Este proyecto es una página web que presenta una galería de videos, permitiendo además agregar nuevos videos a la colección. Utiliza JSON Server para simular una API con una base de datos `db.json`. Este proyecto forma parte de la formación de [Alura Latam](http://www.aluracursos.com/) y permite desarrollar habilidades en HTML5, CSS3 y JavaScript, así como conocimientos sobre el manejo de APIs y JSON Server.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Características](#características)
- [Conocimientos Desarrollados](#conocimientos-desarrollados)
- [Contribuir](#contribuir)
- [Licencia](#licencia)
- [Créditos](#créditos)

## Descripción

La página web permite a los usuarios ver una galería de videos y agregar nuevos videos a la colección. Utiliza JSON Server para simular una API RESTful, proporcionando una experiencia interactiva y dinámica. Este proyecto es una excelente oportunidad para aprender sobre el manejo de datos y la creación de aplicaciones web dinámicas.

## Tecnologías Utilizadas

- **HTML5**: Para la estructura de la página.
- **CSS3**: Para el diseño y la presentación visual.
- **JavaScript**: Para la interactividad y la funcionalidad dinámica.
- **JSON Server**: Para simular una API con una base de datos JSON.
- **Node.js y npm**: Para gestionar dependencias y ejecutar el servidor JSON.

## Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio a tu máquina local.

```bash
git clone https://github.com/DDansAbelenda/alura-play.git
cd alura-play
```

2. Instala JSON Server.

```bash
npm install -g json-server
```

3. Inicia el servidor JSON.

```bash
npx json-server --watch db.json --port 3000
```

4. Abre el archivo `index.html` en tu navegador web favorito.

```bash
open index.html
```

## Uso

Sigue estos pasos para utilizar la página web:

1. Abre la página en tu navegador.
2. Navega a través de la galería de videos para ver los videos disponibles.
3. Utiliza el formulario para agregar nuevos videos a la galería.
4. Los videos se añadirán a la base de datos y aparecerán en la galería.

## Características

- Visualización de una galería de videos.
- Formulario para agregar nuevos videos.
- Simulación de una API RESTful utilizando JSON Server.
- Diseño responsivo que se adapta a diferentes tamaños de pantalla.
- Interfaz de usuario intuitiva y fácil de usar.

## Conocimientos Desarrollados

Este proyecto permite desarrollar los siguientes conocimientos:

- **Simulación de una API**: Aprender a utilizar JSON Server para simular una API RESTful.
- **Trabajo con Node y npm**: Instalar y utilizar Node.js y npm para gestionar dependencias y ejecutar servidores.
- **Utilización de JSON Server**: Configurar y utilizar JSON Server para manejar datos de manera eficiente.
- **Realización de solicitudes GET y POST**: Obtener datos de una API y enviar datos para registrarlos en la base de datos.
- **Refuerzo de conocimientos de JavaScript asíncrono**: Manejar operaciones asíncronas utilizando Promises y async/await.
- **Manejo de errores de solicitud**: Detectar y gestionar posibles errores devueltos por la API.
- **Conversión de una página estática en dinámica**: Transformar una página HTML estática en una aplicación web interactiva y dinámica.

## Contribuir

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto o agregar nuevas características, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios.
4. Haz un commit de tus cambios (`git commit -m 'Agrega nueva característica'`).
5. Empuja tu rama (`git push origin feature/nueva-caracteristica`).
6. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## Créditos

Este proyecto fue desarrollado como parte de la formación de [Alura Latam](http://www.aluracursos.com/). Agradecimientos especiales a los instructores y a la comunidad de [Alura](http://www.aluracursos.com/) por su apoyo y recursos.