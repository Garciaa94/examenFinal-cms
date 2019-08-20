"# examenFinal-cms" 
"# ExamenFinalGrafAnim" 

preparacion de ambiente
1.- para la preparacion del ambiente de gost-cms primero creamos una carpeta en la ruta en la cualqueremos trabajar en nuestro
    proyecto installamos git> https://git-scm.com/download
    tambien tenemos installar node-js para poder trabajar de forma local nuestro proyecto
instalalcion de Gost-cms
2.- descargamos los archivos del cms los cuales se encuentran en GITHUB hacemos para descargar los archivos 
    directamente del repositorio a nuestra carpeta de proyecto usamos esamos el comando (git clone) espesificando la ruta 
    en donde queremos trabajar para asi tener todos los archivos para nuestro proyecto.
3..- luego de descargar los archivos hacemos el comando npm install ghost-cli -g desde nuestra terminal para comensar 
     nuestra instalacion.
	despues de instalar con componentes necesita ghost-cms ponemos el siguiente comando en nuestro terminal
	ghost install local
	asi podremos usar nuestro CMS de forma local
4.- luego de la instlacion de Ghost cms subire mi proyecto a GITHUB 
	con la consola de git que instalamos hacemos los siguientes comandos para poder subir el proyecto:
echo "# examenFinal-cms" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Garciaa94/examenFinal-cms.git
git push -u origin master

5- automatica mente se nos abrira una pestaña la cual nos mostrara el interfaz de ghost para crear una cuanta de usuario
	para poder visualizar la url es :   http://localhost:2368/ 
	el primer paso para iniciar ghost cms es crear el usuario el cual nos pedira ingresar un nombre,correo y contraseña

/*******/
6.- para cambiar el tema que viene por defecto en Ghost-csm lo podemos hacer desde la pagina oficial descargando el 
el complemento y cargandolo (importar) el plugin desde nuestro servidor.
en este caso yo me descarge un tema free desde github : https://github.com/eddiesigner/liebling/
cree una carpeta donde tendre las carpetas para luego cargarlas desde ghost-cms 
	6.1- luego de cargar el tema desde el panel de ghost damos click en activar y luego SAVE para guardar los cambios
	6.2 icono de ghost cms para poder cambiar el icono vamos desde el panel de administracion Publication icon y cargamos la imagen 
	    tiene que tener un tamaño maximo de 60X60X pixeles para que ghost cms pueda aceptar los cambios.
	
 7.- Articulos 
https://www.arsys.es/blog/programacion/ghost-cloud-blog/
https://tecnonucleous.com/2017/12/07/como-instalar-ghost-cms-y-nodejs/
https://www.miguelra.com/como-instalar-ghost/
https://www.sitepoint.com/install-ghost-windows/
https://carlosazaustre.es/como-crear-un-blog-desde-cero-con-ghost-en-digitalocean/
	

preparar ambiente 
que comandos se usas 
procedimientos de como se instala 
minimo 5 articulos temas pre definidos cambiar tema (decir como hicimos el cambio).
plugin o componentes (como usar los complementos del cms ).
cambiar los logos()
hacer commit del todos los procedimientos de instalacion
