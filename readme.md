#Biblioteca virftual

Crear una biblioteca de libros que permita agregar, eliminar y mostrar los libros que tengas, con su titulo, autor e ISBN correspondiente.

Estos datos se deben almacenar en localStorage.



#lite-server

en la consola, me posiciono en la carpeta del proyecto.

Desde la pagina de npm busco lite server
https://www.npmjs.com/package/lite-server

copio este codigo en la consola:
npm install lite-server --save-dev

se crea el package.json

desntro del package.json, en scripto pego el codigo:
"dev": "lite-server"

deberia quedar algo asi:
 "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "lite-server"
  }

en la consola ejecuto el codigo:
npm run dev

#Maquetear

ingresamos a https://bootswatch.com/
busco el tema que quiera
y en download, abro en una  nueva pestaña bootstrap.min.css

copio el link de la pagina y lo pego en el index.html
