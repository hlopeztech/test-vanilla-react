npm create vite@latest

seleccionar vanilla y JS

entrar a la carpeta del proyecto

instalar el plugin de de vite para react
npm install @vitejs/plugin-react -E

instalar react y react dom
npm install react react-dom -E

crear configuracion de vite (vite.config.js)

configurar el punto de entrada de la aplicacion (main.js)

modificar la extensión del archivo main.js a main.jsx ya que vite no es capaz de transpilar el codigo de archivos .js

instalar el linter
npm install standard -D
añadir el linter al package.json
"eslintConfig": {
    "extends": "./node_modules/standard/eslintrc.json"
}

crear la carpeta src con el componente inicial "App"

y finalmente cargar el componente en el main.jsx