### Instrucciones Para Jugar Mokepon

- Validar la ip de mi computador, para esto en el buscador de windows ingresar a la terminal escribiendo **cmd** y dar enter y escribir **ipconfig**
- Buscar la linea que dice la ip: IPv4 Address. . . . . . . . . . . : 192.168.1.3
- Descargar los archivos y abrir el archivo mokepon.js el cual esta en la ruta Mokepon\public\js\mokepon.js
- Verificar en las lineas de codigo: 166-207-269-282-433 que la dirección ip sea la misma obtenida por el comando ipconfig, sino es asi cambiar por la dirección ip actual del equipo.
- Asegurarse de tener instalado Node.js en el equipo que va a iniciar el servidor.
- Guardar los cambios en el archivo mokepon.js e iniciar el servidor de Node.js, para esto se debe de abrir la terminal de windows o de Visual Studio Code y situarse en la carpeta raiz del juego **Mokepon>**
- Escribir el comando **node index.js** la terminal deberia de entregar el mensaje **Servidor Funcionando**
- En un navegador abrir mi direccion ip que en este caso es:  http://192.168.1.3:8080/ (esta puede variar segun los resultados del comando ipconfig)
- En otro dispositivo conectado a la misma red ingresar a la misma dirección del punto anterior.
- Ahora en cada dispositivo se debe de escoger a la mascota Mokepon dandole clic en la mascota y despues en el boton **Seleccionar**
- Ahora cada jugador puede mover su mascota libremente con las flechas del teclado o con las flechas que estan en pantalla hasta chocar con la mascota del contrincante.
- En este momento cada jugador debe de escoger el orden de todos sus ataques y esperar a que su contrincante haga lo mismo para que salga el resultado
- Por ultimo apagar el servidor desde la terminal combinación de teclas Ctrl+C


[Para ver imagenes del juego dar clic aqui](https://i.postimg.cc/7Ppd88T0/batalla-mokepon.png)
