# 15.-RealState
link de mi pagina (https://page-real-state-j.netlify.app/) para ver el sitio

# GULP
se usó para formatear los estilos de SASS, en un archivo css, y crear un archivo .css.map, además de crear las imagenes en formato webp y avif

# como correr en local
para poder correr en local, el proyecto, tendrías que tener node instalados

node version: 20.10.0 es la que tengo yo pero podrías una menor, no habría problema, siempre y cuando las librerias instaladas funcionen correctamente
npm version: 10.2.3

para correr el proyecto: debes tener instalado gulp
gulp: npm i --global gulp-cli
luego verificar que lo tengas instalado 
gulp -dev

## posible complicaciones con gulp
tendrías que abrir la powershell como administrador y escribir el siguiente comando
Get-ExecutionPolicy -List
Set-ExecutionPolicy RemoteSigned -Scope LocalMachine
Luego darle la letra: O
y listo de esa manera vuelves a correr 
gulp -dev


Otra cosa que podría ser que no te permita instalar gulp es por el antivirus, al momento de ejecutar los scripts, trata de pausar el antivirus y dejar que instale gulp
luego ya activas nuevamente

otro dato: 
podrías tener el currenUser en RemoteSigned para que no tengas problemas pero con el LocalMachine, podría bastar
Set-ExecutionPolicy RemoteSigned -Scope LocalMachine
Luego darle la letra: O
y listo de esa manera vuelves a correr 
gulp -dev


# El Icono se hizo con Gimp
Una herramienta de diseño que he usado para generar mi propio icono 