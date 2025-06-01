# EJERCICIOS LEVIATHAN
### level 0
contraseña: leviathan0
### level 0 → level 1
 paso 1: una vez dentro del nivel usamos el comando "ls -la"

 paso 2: usamos el comando "cd .backup/
 
 paso 3: usamos el comando "ls"
 
 paso 4: usamos el comando "cat bookmarks.html"
 
 paso 5: usamos el comando "grep password bookmarks.html"

contraseña: 3QJ3TgzHDq
### level 1 → level 2
paso 1: usamos el comando "ls"

paso 2: usamos el comando "ltrace ./check", ponemos el password (null)

paso 3: usamos el comando "./check", ponemos el password (sex)

paso 4: usamos el comando "ls"

paso 5: usamos el comando "cat /etc/leviathan_pass/leviathan2"

contraseña: NsN1HwFoyN
### level 2 → level 3
paso 1: usamos el comando "ls" y despues "mktemp -d",para poder crear un archivo temporal

paso 2: usamos el comando "cd /tmp/tmp.gzWBltYai3" que es un directorio temporal

paso 3: usamos el comando "touch 'file;bash" para crear un archivo dentro del directorio que inicie sesion

paso 4: salimos del repositorio con "cd", usamos el comando "./printfile /tmp/tmp.gzWBltYai3/file\;bash", nos dira que no tenemos acceso pero nosotros ya estaremos escalados del leviathan2 al leviathan3 chiiiii

paso 5: usamos el comando "cat /etc/leviathan_pass/leviathan3"
 
contraseña: f0n8h2iWLP
### level 3 → level 4
paso 1: usamos el comando "ls"

paso 2: usamos el comando "ltrace ./level3", y de password ponemos cualquier cosa y nos da otro password

paso 3: usamos el comando ".level3", ponemos la contraseña (snlprintf)

paso 4: usamos el comando "ls"

paso 5: usamos el comando "cat /etc/leviathan_pass/leviathan4"
 
contraseña: WG1egElCvO
### level 4 → level 5
paso 1: usamos el comando "ls -la" 

paso 2: usamos el comando "cd .trash/"

paso 3: usamos el comando "ls -la", dentro del directorio (.trash)

paso 4: usamos el comando "./bin" y nos muestra numero de codigo binario

paso 5: suponemos que es la contraseña asi que vamos a una pagina que convierta numeros binarios a texto
 
contraseña: 0dyxT7F4QD
### level 5 → level 6
paso 1: usamos el comando "ls -la"

paso 2: usamos el comando "./leviathan"

paso 3: usamos el comando "ltrace ./leviathan5"

paso 4: usamos el comando "touch /tmp/file.log"

paso 5: usamos el comando "./leviathan5"

paso 6: usamos el comando "ln -s /etc/leviathan_pass/leviathan6 /tmp/file.log"

paso 7: usamo el comando "./leviathan5"
 
contraseña: szo7HDB88w
### level 6 → level 7
paso 1: usamos el comando "ls -la"

paso 2: usamos el comando "./leviathan6", nos pide un codigo de 4 digitos 

paso 3: usamos el comando "for i in {0000..9999} ;do echo $i;./leviathan6 $i;done;", lo forzamos a que nos de el codigo, añ final nos dio un shell

paso 4: usamos el comando "whoami"

paso 5: usamos el comando "$ cat /etc/leviathan_pass/leviathan7"

contraseña: qEs5Io5yM8
