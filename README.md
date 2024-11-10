
# Ejercicio 1 - Página Web Clínica con HTML y CSS

Este es un proyecto de una página web para la Clínica Clínica, diseñado con HTML y CSS. El sitio web presenta información básica de la clínica, incluyendo una página de bienvenida, detalles sobre el equipo médico y una sección de contacto.

## Descripción del Proyecto

La página web de la Clínica consta de tres secciones principales:

**1. Página de Bienvenida (index.html):** Página de bienvenida que incluye una introducción al hospital, un apartado sobre los servicios que ofrece y una sección de testimonios de pacientes, proporcionando confianza a los nuevos visitantes.

**2. Equipo Médico (equipo-medico.html):** Página que muestra el equipo médico con una foto de cada uno, una breve descripción de cada miembro y su especialidad.

**3. Contacto (contacto.html):** Página de contacto con un formulario para que los usuarios puedan enviar mensajes y un mapa interactivo que muestra la ubicación del hospital.

**4. Barra de Navegación (custom_navbar.html):** Es un elemento extra presente en todas las vistas, para mostrar una barra de navegación.

#### Tecnologías utilizadas
- HTML
- CSS

# Proyecto de Estilos

Este proyecto tiene como objetivo crear un diseño para una página web utilizando CSS para la modularización de los estilos. Se implementan media queries para asegurar que el diseño se adapte correctamente a diferentes tamaños de pantalla.

### Media Queries

Las media queries están basadas en los siguientes puntos de interrupción (breakpoints):

- **punto de quiebre pequeño:** 768px
- **punto de quiebre mediano:** 768px y superior

Se implementaron para que los *paddings* y *margins* del proyecto se ajusten de manera fluida dependiendo del tamaño de la pantalla.

### Estructura de los Archivos

La estructura de los archivos SASS y del proyecto en general está organizada de la siguiente manera para promover la reutilización y facilitar el mantenimiento:


        /evaluacion-m2-ejercicio-practico-1
        │
        ├── index.html                
        ├── equipo-medico.html         
        ├── contacto.html         
        ├── custom_navbar.html         
        │
        ├── css/
        │   ├── styles.css 
        ├── img/                  
        │    ├── dr1.jpg
        │    ├── dr2.jpg
        │    ├── dr3.jpg
        │    ├── dr4.jpg 
        │    ├── logo.jpg      
        │    ├── pac1.jpg   
        │    ├── pac2.jpg    
        │    ├── pac3.jpg  
        │    ├── ser1.jpg 
        │    ├── ser2.jpg    
        │    └── ser3.jpg           
        │
        ├── node_modules
        ├── .gitignore
        ├── package-lock.json
        ├── package.json
        └── README.md                 

## Instrucciones para Visualizar el Proyecto

### Requisitos Previos

- Tener **Node.js** y **npm** instalados.
- Tener **SASS** instalado globalmente. Puede instalarse ejecutando el siguiente comando:

        npm install -g sass

### Pasos para Ejecutar el Proyecto

1. Clona el repositorio en tu máquina local:

        git clone <URL del repositorio>
        cd <nombre del repositorio>
2. Instala las dependencias necesarias (si es que usas alguna para el proyecto):

3. Abre el archivo `index.html` (o cualquier otro archivo HTML del proyecto) en tu navegador:
- Utiliza Live Server (si estás trabajando en VS Code) para ver la página en tu navegador
- Haz clic derecho sobre `index.html`.
- Selecciona "Open with Live Server" para iniciar la página en tu navegador.

## Autor

- Martín Avendaño.
