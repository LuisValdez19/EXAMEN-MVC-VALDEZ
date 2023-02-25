
# DOCUMENTACIÓN DE MI CRUD MVC
### LUIS FERNANDO ESPINOZA VALDEZ 5 "A"

Este MVC se se realizo para una mejor comprensión de codigo y asi nuestro codigo esten separados por archivos y carpetas como ya lo vimos en clase, esto nos beneficia mucho ya que lo que hacemos es separar la lógica de la aplicación en tres partes que es en Modelo, en VIsta y Controlador.

## ENTORNO DE DESARROLLO 

A continuación les explicare que ocupamos para el desarrollo de Modelo Vista Controlador:

- Se realizo una carpeta llamada "BD" que contiene dos archivos, uno de ellos es la "configuracion de la BD" que como bien lo dice realiza la respectiva configuración de nuestra BD, el otro archivo es la "conexion de la BD" que como su nombre indica, nos ayudara a conectarnos a nuestra base de datos con los campos del (Servidor, nombre de la BD, el Usuario, y si tiene contraseña se la ingresamos).

- Se realizo una carpeta llamada "Controlador" que contiene un archivo llamado controlador.php que este archivo se encargará de manejar todas las interacciones entre la vista y el modelo, como por ejemplo se encarga de manejar los insert, las opciones de eliminar y modicar.

- Se realizo una carpeta llamada "Modelos" que contiene un archivo llamado modelo.php que este archivo se encargará de representar la información y los datos que se utilizan en la aplicación, como por ejemplo se encarga de las clases es decir las funciones de modificar, al igual que insertar y buscar.

- Se realizo una carpeta llamada "Vistas" que contiene un archivo llamado vistas.php que este archivo como bien en su nombre lo dice, se encargará de mostrar al usuario la interfaz que se utiliza para interactuar con el modelo y asi mostrar o presentar los datos, en pocas palabras la vista solo contiene puro codigo HTML.

- Por ultimo, se realizouna carpeta llamada "css" que contiene un archivo llamado style.css que este nos ayudara a agregarle diseño a nuestra interfaz, para que asi sea mas presentable y se pueda interactuar mucho mejor.

## ¿CÓMO FUNCIONA?

Bueno, a continuación les explicaré muy a detalle como funciona mi CRUD en un Local Host:

- Primero que nada mi crud tiene un diseño notable para que todas las personas lo vean y esté llamativo.

- Es un CRUD que nos ayudara a insertar solamente un nombre y una fecha.

- En la fecha es un tipo Dato, entonces nos permitira seleccionar en el calendario que fecha nosotros queremos insertar.

- Cuenta con un simple boton de insertar, para que al momento de llenar todos los campos, le accionemos al boton de insertar y asi se inserte.

- Cuenta con una base de datos, que al insertar nuevos datos estos se vayan a una base de datos en local.

- Cuenta con una busqueda de tipo texto, que esto nos permite escribir en el recuadro de busqueda y accionemos la opcion de busqueda y nos ayudara a buscar por el campo nombre.

- Cuando agreguemos un registro, este registro se mostrara en una tabla en nuestro index es decir menu principal.

- Cuenta con un boton eliminar, esto nos permitira eliminar registros que no deseamos que se vea en nuestra tabla.

- Al igual cuena con otro boton que es el de modificar, este boton nos permitira modificar cualquier registro ya sea el de nombre o fecha, una vez accionando el boton esto se modoficara en la tabla y en la base de datos.

## INSTALACIÓN

Para ello requerimos lo siguiente:

- Primero que nada debemos de instalar XAMPP que nos permitira configurar un servidor web en un sitio local.

- Una vez instalado, debemos de acceder a su carpeta y ingresamos a una carpeta llamada "htdocs".

- Una vez ubicados en la carpeta, comenzamos a crear la carpeta que nosotros ocupemos dentro de la carpeta htdocs.

## EJECUCIÓN

Para ello debemos de seguir los siguientes pasos:

- Para realizar la ejecución de nuestro proyecto, debemos de ir a nuestro buscador de aplicaciones y buscamos "XAMPP" una vez ubicandolo lo ejecutaremos como administrador.

- Una vez abriendo XAMPP, llenaremos las casillas de Apache y MySQL y esperemos que se marquen de verde para que asi funcione.

- Cuando se marque en verde, continuamos a abrir el administrador de MySQL que este nos permitira de crear las bases de datos y tablas que ocuparemos.

- Una vez ya creado todo y haber seguido las instrucciones, nos dirigimos a nuestro navegador y para abrir nuestro sitio web buscaremos como en el siguiente ejemplo: localhost/ejemplo/index.php el "localhoat" siempre ira de por defecto "ejemplo" es el nombre de la carpeta donde esta ubicado nuestro archivo y el "index.php" es el archivo que queremos abrir.

De esta manera nosotros podriamos ejecutar nuestro sitio web claramente acatando cada una de las intrucciones antes ya mencionadas.

