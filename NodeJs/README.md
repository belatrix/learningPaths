# Engineer 1
- Instalación de Node y Ejecución del Server
	- Instalación de Node
	- Iniciación de un servidor HTTP
	- Manejo de paquetes con npm

- Deconstrucción de un servidor HTTP
	- Introducción al modulo HTTP
	- Creación de un Server
	- Definiendo el callback requestListener
	- Escucha por requests

- Especificaciones del modulo CommonJS
	- Entendimiento de la especificación del modulo CommonJS
	- Exportación del API de un modulo
	- Uso del scope local y global en un modulo

- Carga de Modulos
	- Diferenciación entre modulos core, locales y de terceros
	- Carga de modulos con rutas relativas y absolutas
	- Carga de directorios como modules

- Manejo de dependecia de modulos
	- Carga de versiones diferentes de un modulo dentro del mismo proyecto
	- Manejo de dependencias entre modulos

- Manejo de paquetes con npm
	- Listar paquetes instalados
	- Inspección de propiedades de paquetes
	- Vista de dependencias
	- Actualización de paquetes
	- Busqueda de paquetes

- Configuración y publicación de paquetes
	- Modulo CommonJS
	- Generación de un archivo descriptor package
	- Publicación de un package
	- Declaración de dependencias del modulo

- El Event Loop y el nextTick()
	- Entendiento el Event Loop
	- Aplazamiento the la ejecución con process.nextTick()

- Programación asincrona y nonblocking I/O
	- Invocando funciones callback en Javascript
	- Ejecución de un callback de manera sincrona
	- Ejecución de un callback de manera asincrona
	- Coparacion entre programación asincrona y multi-hilos (multi-threaded)

- Patrones Callback
	- Convenciones para los callbacks
	- Paso de errores a los callbacks
	- Dando nombres a las funciones
	- Evitar muchos callbacks anidados

- Pub/Sub con EventEmitters
	- Entendiendo el patron Messagin Pattern
	- Heredando de EventEmitter y disparando eventos
	- Agregando y removiendo event listeners

- Manejo del File System
	- Consulta y manipulación de rutas
	- Inspección a la metadata del file system
	- Manejo de archivos y directorios

- Lectura y Escritura de archivos
	- Lectura y Escritura de un archivo al tiempo
	- Lectura y Escrutura de archivos por partes
	- Depuración de errores en el I/O de archivos

- Lectura y Escritura de Streams
	- Lectura desde un Stream
	- Escritura a un Stream
	- Lectura desde el stdin y escritura al stdout

- Construcción de un Servidor HTTP
	- Enrutamiento de GET y POST requests
	- Lectura de headers desde el objeto request y Escritura de headers al objeto response
	- Manejo de archivos subidos

- Serving archivos estaticos
	- Enrutamiento de requests para contenido estatico
	- Configuración de los headeres del response con node-mime
	- Parseo de datos desde la URL

- Performance Tuning
	- Caching y compresion del response
	- Manejo de back-pressure con pipe()
	- Creando un cliente HTTP

- Usando el Middleware HTTP
	- Entendiendo el Middleware
	- Respondiendo al request con el framework Connect
	- Usando los componentes middleware logger y errorHandler

- Creando un Servidor estatico con Connect
	- Sirviendo recursos con el middleware estatico de Connect
	- Usando el componente multipart de Connect para el manejo de carga de archivos
	- Parseo del querystring y generación de paginas de error con Connect

- Tunning el servidor Connect
	- Compresión de archivos con Connect
	- Configuración del max age de recursos estaticos
	- Limitando el tamaño de los archivos a subir en el server

- Usando un framework para aplicaciónes Web
	- Instalación del framework Express
	- Creación del archivo pakage.json
	- Enrutando requests y enviando responses
	- Configuración del middleware estatico

- Almacenando datos en una sesión
	- Guardando sesiones en ambiente de desarrollo con Express
	- Configurando un sessión secret
	- Guardando sesiones en ambiente de producción con RedisStore

- Creando una aplicación TODO con Express
	- Creación de un form HTML
	- Guardando y devolviendo los datos de sesión
	- Enrutando un request POST

- Generación de logs y manejo de errores
	- Escribiendo logs de acceso
	- Logs con la herramienta Forever
	- Manejo de errores con Express
	- Logs de error con Forever

- Escogiendo un motor de plantillas
	- Separando la capa de de modelo de la vista
	- Usando sintaxis HTML
	- Comparación de caracteristicas de motores de plantillas

- Haciendo rendering con las plantillas de la vista
	- Populando la plantilla con datos
	- Definiendo custom delimiters
	- Ejecutando codigo dentro de una plantilla

- Caracteristicas avanzadas de las plantillas
	- Rendering vistas con un layout
	- Incluyendo archivos externos en las vistas
	- Manipulación de los datos en la vista

- Instalando MongoDB y Mongoose
	- Instalando MongoDB
	- Usando la autenticación
	- Introduciendo Mongoose

- Creando una interface de DB
	- Cargando la configuración de la DB
	- Creando una interface de conexión a la DB
	- Conectandose a la DB

- Definición de un Modelo
	- Definiendo un Schema en Mongoose
	- Validación de datos
	- Describiendo el API REST

- Ejecución de operaciones CRUD
	- Creación y actualización de un evento
	- Listado y detalles de los eventos 
	- Borrado de un evento

- Usando Subdocuments
	- Definiendo un schema subdocument
	- Validando subdocumentos
	- Agregando un subdocumento al array del documento padre
	- Borrando subdocumentos

- Comunicación Real-Time con Socker.IO
	- Instalando Socker.IO
	- Escuchando por conexiones de socket en el server
	- Estableciendo conexiones de socket en el cliente

- Pushing Notifations
	- Refactorizando la API REST para emitir eventos
	- Retransmitiendo eventos a conexiones por socket
	- Mostrando los mensajes de notificación

- Publicando actualizaciones de contenido
	- Creación de plantilla al lado del cliente
	- Aumentando los datos del objeto message
	- Renderizando fragmentos de la vista en el navegador
	- Usando sockets con namespaces

- Instalación de un Framework para pruebas
	- Instalando Mocha, Should y Supertest
	- Configurando Mocha y ejecución de tests
	- Conectandose a una DB de pruebas

- Escribiendo pruebas de integración
	- Simulación de server requests con Supertest
	- Populando datos de prueba con fixtures
	- Usando assertions para verificar el comportamiento de la aplicación 

# Engineer 2
- Nodejs
	- Fundamentos de Nodejs
	- Casos de usos comunes
	- Pros y contras de Nodejs

- Blocking vs Non-blocking code
	- Introducción
	- El Call Stack
	- Soporte CLI

- Configuración del ambiente 
	- Instalando Node.js
	- Alternativas de instalación
	- Instalando nodemon

- Hola Mundo
	- Creando una aplicación CLI
	- Usando ESLint
	- Depurando una aplicación

- CommonJS
	- Intro y Repaso 
	- npm
	- El Event Loop
	- Trabajando con Streams
	- Trabajando con archivos

- NPM
	- Que es NPM repaso
	- Instalanción de npm repaso
	- Arreglando los permisos
	- Administrando los paquetes

- El Event Loop
	- Estructura de datos LIFO (Last-In First-Out)
	- Util para depurar
	- Crash de programas en Stack overflow
	- Compuesto de stack frames
	- Stack frame: argumentos, retordo de dirección y variables locales
	- Evita muchas llamadas a funciones

- Trabajando con Streams
	- Abstract interface
	- Forma alternativa para acceder a los datos
	- Requerimiento de poca memoria
	- Instancias de EventEmitter
	- Readable / Writeable / Duplex

- Trabajando con archivos
	- El module del File System
	- Leyendo / Escribiendo archivos
	- Observando archivos
	- Manipulación de directorios

- Express.js Basico
	- Lo basico
	- Patron MVC
	- Enrutamiento
	- Estructurando un app
	- Plantillas con Handlebars

- Patron MVC
	- Que es MVC
	- Interación de componentes MVC
	- MVC en Express.js

- Enrutamiento
	- Metodos y rutas
	- Manejo de enrutamiento
	- express.Router

- Estructurando la aplicación
	- Generador Express
	- Middleware
	- Autenticación de usuario

- Plantillas con Handlebars
	- Motor de plantilla
	- El output depende de los datos
	- HTML normal con expresiones

- MongoDB Basico
	- Lo basico de MongoDB
	- NoSQL DB
	- Shema y tipos de datos
	- Operaciones CRUD
	- Integración con Node.js
	- Mongoose

- NoSQL DB
	- Lo basico
	- Bases de datos de key-value
	- Bases de datos de documentos
	- Bases de datos de columnas
	- Bases de datos de grafos

- Schema y tipos de datos
	- Schema en MongoDB
	- Tipos de datos disponibles
	- Datos normalizados vs datos desnormalizados

- CRUD
	- El shell de MongoDB
	- Operadores
	- Buscando documentos
	- Insertando / Actualizando / Removiendo documentos

- Integración con Node.js
	- Conexión a MongoDB
	- Encontrando documentos con Node.js
	- Insertando / Actualizando / Removiendo con Node.js

- Mongoose
	- Que es Mongoose
	- Instalando Mongoose
	- Creando modelos
	- Protegiendo aplicaciones

- APIs RESTful
	- APIs RESTful
	- Sirviendo APIs
	- Consumiendo desde el lado del server
	- Consumiendo desde el lado del cliente
	- CRUD a traves de REST

- Sirviendo APIs
	- Express.js para APIs RESTful
	- Planea tu API
	- Autenticación

- Consumiendo desde el lado del server
	- Modulo API
	- Modulo nativo HTTP
	- Modulo cliente API REST

- Consumiendo desde el lado del cliente
	- Documentando
	- Retrieving
	- Manipulación

- CRUD a traves de REST
	- Retrieving
	- Aggregate
	- Manupulación

- Pruebas unitarias y TDD
	- Introducción
	- Mocha y Chai
	- Spying y Stubbing
	- Mocking con Sinon.JS
	- Ejecución con Karma

- Mocha y Chai
	- Mocha
	- Chai
	- Escribiendo pruebas

- Spying y Stubbing
	- Spies
	- Stubs
	- Fake timers

- Mocking con Sinon.js
	- Sinon.js
	- Mocks
	- Probando aplicaciones

- Ejecución con Karma
	- Karma
	- Configurando Karma
	- Probando aplicaciones

- Dependencias y SemVer
	- Introducción
	- El package.json
	- Publicando a npm
	- Lo basico de Heroku
	- Desplegando a Heroku

- El package.json
	- Que es el archivo package.json
	- Como crear el archivo package.json
	- Que hay dentro del archivo package.json

- Publicando a npm
	- Intro a npm
	- Preparando el package
	- Publicando a npm

- Lo basico de Heroku
	- Platform as a Service (SaaS)
	- Que es Heroku
	- Como funciona Heroku

- Desplegando a Heroku
	- Heroku toolbelt
	- Despliegue
	- Configuración

- Optimización del Page Performance
	- Introducción
	- Javascript Isomorfico
	- Bundling con webpack
	- Terminando la app

- Javascript Isomorfico
	- Aplicación isomorfica
	- Beneficios
	- Un ejemplo

- Bundling con Webpack
	- Que es Webpack
	- Como instalar Webpack
	- Como configurar Webpack

- Terminando la App
	- Redis
	- Job queue
	- Workers

- Clusters
	- Por qué usar un cluster
	- Creando un Node.js cluster
	- Mejorando una aplicación o el flujo de trabajo de desarollo

# Engineer 3
- Instalando Express.js y herramientas CLI
  - Instalando Node.js y sus dependencias para comenzar un proyecto

- Bootstrapping una App
  - Creando una app Express.js basica usando el CLI

- Estructura de una app Express.js
  - Introducción y explicación

- Introduciendo el motor de plantillas Jade
  - Como funciona el motor Jade

- Introduciendo Stylus
  - Que es y como funciona

- Bootstrap con Jade y Stylus
  - Como Bootstrap puede ayudar a crear buenas web apps

- Archivos publicos y estaticos
  - Donde almacenar archivos publicos y estaticos, como imagenes, archivos de fuetes y codigo Javascript

- Otras opciones de las plantillas
  - Todas las plantillas que hay disponibles para crear una app

- Planeando la estructura de una aplicación
  - Construyendo una aplicación básica para mostrar los aspectos importantes de una aplicación común de Node.js

- Instalación de modulos necesarios
  - Modulos para ayudar a construir una aplicación

- Creación de endpoints
  - Creando y probando las rutas

- Creación de una aplicación con interface de usuario
  - Configurando paginas HTML planas - sin datos dinamicos
  - La apariencia basica de la aplicación

- Entendiendo plantillas con menos logica en ellas
  - Un problema con el que los desarrolladores se encuentran frecuentemente en el desarrollo de una app
  - Algunos conceptos acerca de menos logica en las plantillas

- Mostrando datos dinamicos con Jade
  - Como cruzar el umbral de datos harcodeados a una app dinamica

- Por qué automatizar las pruebas
  - Creación de un plan de pruebas que ejecuta todos los aspectos de una app

- Micro Testing/Unit Testing vs Full Stack Testing
  - Opciones diferentes para hacer pruebas a la app

- Configuración de herramientas para pruebas
  - Como organizar las herramientas para hacer pruebas

- Pruebas JS al lado del server vs Pruebas JS al lado del cliente
  - Explicación

- Instalación y configuración de MongoDB
  - Instalando MongoDB y sus dependencias antes de almacenar los dato

- Configurando Mongoose
  - Configuración de la app para conectarse a MongoDB
  - Usando la libreria Mongoose para Node.js

- Creación de los modelos
  - Almacenamiento de los datos en MongoDB

- Diferencias entre MongoDB y DB relacionales
  - Por qué MongoDB is diferente

- Colleccionando los datos
  - Uso de los datos con MongoDB

- Agregando autenticación con Passport.js
  - Restricción de accesos a usuario que se han logueado a la app

- Entendiendo sesiones
  - Por qué HTTP stateless es bueno y malo
  - Como usar las sesiones para hacer que el server almacene algunos datos

- Usando Facebook y Twitter como autenticación
  - Como permitir que los usuarios accedan a la app con Twitter y Facebook

- Despliegue de la aplicación
  - Consideraciones a tener en cuenta

- Despliegue de la app en el Cloud con Heroku
  - Usar una PaaS para el despligue de la app

- Consideraciones a tener en cuenta al desplegar la app en un server tradicional
  - Desplegando la app a un server dedicado o a un Virtual Machine

- Modulos personalizados
  - Algunos temas avanzados en Express.js, comenzando con los modulos personalizados

- Framework MVC dogmatico Sails.js
  - Que tanto Sails.js se parece a Rails
  - Conceptos que se comparten con Rails como los modelos, los controladores y las plantillas

- Herramienta popular para blogs - Ghost
  - La herramienta Ghost

- Herramientas a lado del cliente con el patron MVC
  - Herramientas como:
    - Backbone.js
    - Ember.js
    - Angular
  - El stack de herramientas MEAN (MongoDB, Express.js, Angular y Node.js)

- Socket.IO para conexiones WebSocket
	- Como Socket.IO permite facilmente soportar WebSockets en una app con Express.js

# Senior
- Necesitades para escalar una app
	- Factores externos
		- Incremento en el trafico
		- Incremento en el poder de procesamiento requerido
	- Factores internos
		- Alta disponibilidad
		- Tolerancia a fallos

- Patrones de arquitectura
	- Los patrones
		- Arquitectura por capas
		- MVC no es por capas
		- Client-Server
		- Master-Slave
		- Event-Bus o Event-Driven Architectures
		- Arquitectura por Microservicios
		- El patron Broker
	- Arquitecturas Lambda

- Formas de escalar
  - Tecnicas de escalamiento
    - Esalamiento vertical u horizontal?​
    - Tomando ventajas del Cloud
	- Clustering la aplicación
		- Clustering con PM2
		- Conclusiones
	- Microservicios al rescate
		- Conclusiones

- Retos al escalar
	- Lidiar con tus archivos de log
		- Haciendo loggin en el stdout y stderr
		- Haciendo loggin en un solo archivo
	- Compartiendo memoria entre procesos
		- Puntos unicos de fallas?​
	- Stateful Apps y escenarios Multi-Server

- Cuando escalar?​
	- Monitoreo
		- Alerting
		- Monitoreo de tus Apps
		- Agregando metricas AWS en tu Dashboard
		- Reaccionando a las Metricas

- Probando la Aplicación
	- Pruebas 101
		- La definición
		- Las herramientas
		- Mejores practicas
	- Pruebas con Node.​js
		- Pruebas sin modulos externos
		- Mocha
		- Pruebas a codigo asincrono
	- Pruebas de integración
		- Enfoques de pruebas

- Casos de exito
	- PayPal
	- Uber
	- LinkedIn
  	- Mas grandes retos
	- Netflix
