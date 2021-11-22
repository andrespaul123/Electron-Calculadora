# Electron-Calculadora
Es una calculadora hecha con electron, html , css, javaScript

no se subieron los archivos node-modules debido a un gran tamaño de archivos.
se recomienda remplazar los dos archivos package.json y package-lock.json ya que en algunos casos se puede tener diferentes versiones de electron.

para instalar el package.json  introducir   npm init -y   ese comando genera el paquete por defecto.

asi deberia aparecer
{
  "name": "my-electron-app",
  "version": "1.0.0",
  "description": "Hello World!",
  "main": "main.js",
  "author": "Jane Doe",
  "license": "MIT"
}


para instalar electron y los archvos node-modules   introducir: npm install --save-dev electron
una vez instalado cambiar en el package.json el start ya que es el comando que ejecutara nuestra ventana de una aplicacion.
{
  "scripts": {
    "start": "electron ."
  }
}



comando para inicializar el proyecto de la calculadora:   npm start
