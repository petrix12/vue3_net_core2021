# Aplicación de tareas con Vue 3 + Net Core + EFC
+ **URL Curso**: https://www.udemy.com/course/vue3-netcore
+ **URL Repositorio**: 
+ **URL App en producción**: 

## Antes de iniciar:
1. Crear proyecto en la página de [GitHub](https://github.com) con el nombre: **vue3_net_core2021**.
    + **Description**: Proyecto para seguir el curso de "Aplicación de tareas con Vue 3 + Net Core + EFC", de Tomas Ruiz Diaz en Udemy.
    + **Public**.
2. En la ubicación raíz del proyecto en la terminal de la máquina local:
    + $ git init
    + $ git add .
    + $ git commit -m "Commit 00: Antes de iniciar"
    + $ git branch -M main
    + $ git remote add origin https://github.com/petrix12/vue3_net_core2021.git
    + $ git push -u origin main

## Sección 1: FrontEnd

### Video 01. Instalación NodeJS y VueCLI
1. Programas requeridos:
    + [Node Js](https://nodejs.org)
    + [Visual Studio Code](https://code.visualstudio.com/download)
2. Instalación de **Vue CLI**:
    + Abrir terminal como administrador.
    + $ npm install -g @vue/cli
        + [Vue CLI](https://cli.vuejs.org/guide/installation.html)
3. Consultar las versiones de los programas:
    + Node Js:
        + $ node --version
    + NPM:
        + $ npm --version
    + Vue CLI:
        + $ vue --version
4. Commit Video 01:
    + $ git add .
    + $ git commit -m "Commit 01: Instalación NodeJS y VueCLI"
    + $ git push -u origin main

### Video 02. Creación del Proyecto - Instalación de extensiones y agregamos bootstrap
1. Crear proyecto:
    + $ vue create 29vue3_net_core
    + Seleccionar: Default (Vue 3) ([Vue 3] babel, eslint)
2. Ingresar y levantar el proyecto:
    + $ cd 29vue3_net_core
    + $ npm run serve
3. Instalar las siguientes extensiones de VSCode:
    + Vetur v0.35.0
        + Pine Wu
        + Vue tooling for VS Code
    + Vue VSCode Snippets v2.2.1
        + sarah.drasner
        + Snippets that will supercharge your Vue workflow
4. Commit Video 02:
    + $ git add .
    + $ git commit -m "Commit 02: Creación del Proyecto - Instalación de extensiones y agregamos bootstrap"
    + $ git push -u origin main

### Video 03. Creación TareaComponent y Agregamos bootstrap
1. Agregar el CDN CSS de Bootstrap en public\index.html:
    ```html
    <!DOCTYPE html>
    <html lang="">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <link rel="icon" href="<%= BASE_URL %>favicon.ico">
        <title><%= htmlWebpackPlugin.options.title %></title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    </head>
    <body>
        <noscript>
            <strong>We're sorry but <%= htmlWebpackPlugin.options.title %> doesn't work properly without JavaScript enabled. Please enable it to continue.</strong>
        </noscript>
        <div id="app"></div>
        <!-- built files will be auto injected -->
    </body>
    </html>
    ```
    + https://getbootstrap.com/docs/5.1/getting-started/introduction
2. Eliminar el componente **src\components\HelloWorld.vue**.
3. Modificar **src\App.vue**:
    ```vue
    <template>
        <Tarea />
    </template>

    <script>
    import Tarea from '@/components/Tarea'

    export default {
        name: 'App',
        components: {
            Tarea
        }
    }
    </script>

    <style>
    </style>
    ```
4. Crear el componente **src\components\Tarea.vue**:
    ```vue
    <template>
        <div>
            <h1>Soluciones++</h1>
        </div>
    </template>

    <script>
        export default {
            name: 'Tarea'
        }
    </script>

    <style scoped>

    </style>
    ```
5. Commit Video 03:
    + $ git add .
    + $ git commit -m "Commit 03: Creación TareaComponent y Agregamos bootstrap"
    + $ git push -u origin main

### Video 04. TareaComponent HTML



### Video 05. Agregamos FontAwesome
### Video 06. Agregamos tarea al listado
### Video 07. Eliminar Tarea
### Video 08. Editar Tarea### Video 0
### Video 09. Deploy

## Sección 2: BackEnd

### Video 10. Creación del BackEnd
### Video 11. Creación del Modelo
### Video 12. Instalacion de dependencias
### Video 13. Creación del DbContext y Migraciones
### Video 14. Creación TareaController y Get Tareas
### Video 15. POST Guardar Tarea
### Video 16. PUT Actualizar Tarea
### Video 17. DELETE Tarea
### Video 18. Cors

## Sección 3: Integración FrontEnd y BackEnd

### 19. Instalación Axios y obtenemos las tareas
### 20. Integramos eliminar tarea
### 21. Integramos guardar tarea
### 22. Integramos actualizar tarea
### 23. Deploy BackEnd Azure
### 24. Deploy FrontEnd
### 25. Conexión remota SQLServer (Azure)
### 26. Despedida

0.45 - x
1 - 321



    ≡
    ```vue
    ```
    ```js
    ```
    npm run serve

## Comandos Git:
+ Historial de commit:
    + git log --pretty=oneline
+ Borrar ultimo commit:
    + git reset HEAD^ --soft
+ Forzar push
    + git push origin -f
