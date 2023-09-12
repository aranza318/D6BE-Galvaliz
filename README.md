# D6BE-Galvaliz
El proyecto esta compuesto por:
1. Src:
   A. Confing contiene a un archivo configs que trabaja con dotenv (quien permite asignar variables y variables y ocultarlos para que nadie los vea).
   B. Controllers aloja a los controladores de autorizacion y de usuarios.
   C. Dao quien comprende a: una carpeta fs(donde estan los archivos relacionados a file sistem),
                             una carpeta models(que abarca a los modelos de usuario, carrito, mensaje y productos),
                             y los mangers que trabajaran con dichos modelos.
   D. Errors quien encierra a todos los errores que puede presentar la api en cuanto a los usuarios y sus registros. 
   E. MidsIngreso quien encierra a los archivos: bcrypt(quien se encarga de la encriptacion de contraseñas),
                                                 github(quien se ocupa del ingreso a la app con la cuenta de GitHub),
                                                 passport(quien trabaja con el login clasico de la pagina). 
   F. Pass icluye al archivo criptografia quien trabaja con JWT y bcrypt para encriptar las contraseñas.
   G. Public envuelve a: css (donde se aloja el archivo style, quien da los estilos a la pagina),
                         images (contiene la imagen del cliente),
                         js (inluye dento a login, quien trabaja el ingreso al sitio, y tambien a restore, quien trabaja con las implicaciones del cambio de contraseña),
                         y tambien se encuentran aqui cart(se encarga del carrito), chat(modera las partes del mismo),
                         realTimeProducts(domina el ingreso y egreso de los productos a la app), register(hospeda al registro) y user para el usuario.
   H. Routes alberga a las diversas rutas de acceso como: cart, session, views y products.
   I. Services cobija a los servicios de autenticacion y usuario.
3. Views establece las vistas mediante handlebars para: layouts(main) y tambien para cart, chat, products, profile, login, realTimeProducts, register y restore. 
4. Env: tabaja alojando las variables de dotenv.
5. App.js donde confluyen todas las partes de la app para que esta funcione y cobre vida.
7. Utils quien aloja al __dirname.
