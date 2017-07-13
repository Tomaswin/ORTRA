# ORTRA
Sistema de realidad aumentada que te guia por la escuela ORT Almagro, todavia en Development Build

Pasos a seguir para la utilizacion de Realidad Aumentada en Unity

1- Registrarse en la pagina Vuforia.com

2- Dirijirse a Developers, A License Manager

3- Creamos una nueva License Key

4- Vamos a Target Manager y creamos una nueva base de datos

5- Agregamos los targets, ya pueden ser imagenes como objetos 3D

6- Descargamos la Base de datos

7- Vamos a Downloads y buscamos Examples

8- Buscamos Advanced Topic y elegimos la descarga para unity

9- Extraemos los archivos

10- Abrimos Unity (Un proyecto nuevo)

11- Importamos como Custom Asset uno de los archivos extraidos llamado VideoPlayback

12- En Unity tambien Importamos como Custom Asset la Base de datos descargada

13- Luego Borramos la Main Camera

14- Buscamos en Unity la carpeta Vuforia, luego Prefabs y luego arrastramos el objto AR Camera a los objetos que estan visibles

15- En las propiedades de la AR Camera vamos a Vuforia Configuration y primero Copiamos nuestra License Key donde dice y luego activamos nuestra base de datos

16- Arrastramos el objeto ImageTarget al campo y en sus propiedades encontramos un lugar donde dice base de datos ahi elejimos la que creamos y descargamos y luego abajo la imagen que queremos usar.

17- Como vimos al crear un ImageTarget se nos crea un cuadro blanco arriba de ese cuadro pondremos cubos, imagenes y objetos que queramos que se muestren cuando nuestra camara detecte el objeto que elegimos

18- Para compilarlo a Android debemos ir a File, Build Settings, elegimos la opcion Android y en Profile Settings revisamos las propiedades y las cambiamos a gusto, luego le damos a Build

19- Lo instalas en tu Mobile y listo, lo unico que hay que hacer es apuntar con la camara al objeto que usamos en el ImageTarget.

tomaswinicki@gmail.com
