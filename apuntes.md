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




## Sección 01: Introducción

### Video 001. Introducción
+ **Contenido:** Conocimientos previos y que esperar del curso.
1. Commit Video 001:
    + $ git add .
    + $ git commit -m "Commit 001: Introducción"
    + $ git push -u origin main

### Video 002. ¿Cómo funciona el curso?
+ **Contenido:** Detalles y recomendaciones sobre el funcionamiento del curso.
1. Commit Video 002:
    + $ git add .
    + $ git commit -m "Commit 002: ¿Cómo funciona el curso?"
    + $ git push -u origin main

### Video 003. ¿Cómo hacer preguntas?
+ **Contenido:** Políticas del curso sobre como formular preguntas.
1. Commit Video 003:
    + $ git add .
    + $ git commit -m "Commit 003: ¿Cómo hacer preguntas?"
    + $ git push -u origin main

### Video 004. Instalaciones recomendadas y obligatorias
+ [Instalaciones recomendadas](https://gist.github.com/Klerith/c994a32ad825d4e87b9efbfb7174bcaa)
1. Instalaciones recomendadas:
    + [Node Js](https://nodejs.org)
    + [Visual Studio Code](https://code.visualstudio.com/download)
    + [Google Chrome](https://www.google.com/intl/es/chrome/?brand=UUXU&gclid=CjwKCAjwndCKBhAkEiwAgSDKQVlgpc0j06KtDtMn3gg-cCI_2KuhgL-PoRBJXLhg93KfoAmqVbPeLBoCkSwQAvD_BwE&gclsrc=aw.ds)
    + [Vue CLI](https://cli.vuejs.org/guide/installation.html)
    + [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
    + [Postman](https://www.postman.com/downloads)
2. Extensiones de VSCode:
    + Activitus Bar:
        + Gruntfuggly
        + Save some real estate by recreating the activity bar buttons on the status bar
    + TypeScript importer:
        + pmneo
        + Automatically searches for TypeScript definitions in workspace files and provides all known symbols as completion item to allow code completion.
3. Extensiones de Chrome
    + Vue DevTools
    + Vue DevTools Beta
    + Json Viewer Awesome
4. Instalación de **Vue CLI**:
    + Abrir terminal como administrador.
    + $ npm install -g @vue/cli
5. Instalación de Vetur en VSCode:
    + Abrir VSCode.
    + Ir a la página de [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur).
    + Presionar el botón **Install**.
    + Seguir el resto de las instrucciones de forma intuitiva.
6. Instalar Bracket Pair Colorizer 2 en VSCode:
    + Abrir VSCode.
    + Ir a la página de [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2).
    + Presionar el botón **Install**.
    + Una vez instalado, para configurar los colores de las llaves, ir a **Ver > Paleta de comandos...**.
    + Ubicar **Open Settings (JEISON)** y establecer la configuración de colores de llaves anexando en **C:\Users\bazop\AppData\Roaming\Code\User\settings.json**:
        ```json
        "bracket-pair-colorizer-2.colors": [
            "#fafafa",
            "#9F51B6",
            "#F7C244",
            "#F07850",
            "#9CDD29",
            "#0098FA"
        ],
        ```
7. Consultar las versiones de los programas:
    + Node Js:
        + $ node --version
    + Vue CLI:
        + $ vue --version
8. Commit Video 004:
    + $ git add .
    + $ git commit -m "Commit 004: Instalaciones recomendadas y obligatorias"
    + $ git push -u origin main





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
