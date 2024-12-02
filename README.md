1. Crear un repositorio en local.

En este proyecto, empiezo creando un repositorio llamado "repositorio-modulo-0", 
utilizando el comando "mkdir repositorio-modulo-0" en la consola de comandos. 
A continuación, navego al interior de la carpeta del repositorio utilizando 
"cd repositorio-modulo-0". Una vez dentro de la carpeta, inicializamos el 
repositorio de Git utilizando el comando "git init".

2. Subir el repositorio a GitHub.

Para subir el repositorio a GitHub, lo primero que he hecho ha sido acceder a la
web de GitHub con mi cuenta, y hacer click en el botón con un símbolo "+" para 
crear un nuevo repositoriom al cual le he asignado el mismo nombre que el que
he creado en local: "repositorio-modulo-0". Una vez creado el repositorio,
he copiado la URL del mismo y utilizado el comando "git remote add origin", 
seguido de la URL copiada previamente. Investigando un poco por mi cuenta,
descubrí que para comprobar la conexión entre los repositorios puedo utilizar el
comando "git remote -v", el cual me indica la URL del repositorio linkeado a mi 
repositorio local.

3. Hacer un commit y un push.

He creado una carpeta llamada "Carpeta de prueba". A continuación, ejecuto el 
comando "git add ." para añadir los ficheros a fase stage, para poder hacer un 
commit con el comando "git commit -m "commit de prueba"". Después, he hecho un push
utilizando el comando "git push -u origin master", con lo cual ya puedo ver mis 
archivos del repositorio dentro de GitHub.
