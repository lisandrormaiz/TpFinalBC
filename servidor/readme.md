Proyecto Final - Programación Backend - Servidor 
Es una API RESTful construida sobre Node.js utilizando Express.js como framework. Tiene sistema de AUTH con Passport y JWT, en donde podés registrarte e iniciar sesión. En la API podés agregar, obtener, modificar, borrar productos. Además, tiene un carrito en donde podés agregar y borrar productos. Tiene sistema de órdenes en donde podés crear una orden del carrito del usuario. Por último, tiene un canal de chat para consultas del cliente por websockets.

Inicializar el proyecto 
Instalar las dependencias del proyecto.
npm install
Crea y configura development.env además de production.env para que funcione correctamente, podes ver el ejemplo en example.env.
Correr el proyecto en tu computadora en modo desarrollo.
npm run dev
Correr en modo producción.
npm start
Ingresar a la ruta "/api-docs" para visualizar la documentación.
En la ruta "/" ingresas a la página, un pequeño Front End en React JS.
Visita la página en donde está corriendo el proyecto con Front End
Click Acá para ir a la página.

Paquetes utilizados 
dotenv
express
express-validator
cors
compression
jsonwebtoken
mongoose
passport
passport-local
passport-jwt
bcrypt
swagger-ui-express
winston
yargs
