# clase1
clase1
 
# level 0:

puse en la terminal de linux el comando "ssh -p 2220 bandit0@bandit.labs.overthewire.org", seguidamente colocamos la (contraseña)que la pagina de OverTheWire nos dio que era "bandit0"

# level 0 → level 1:

para poder hallar la contraseña una vez logueado use el comando "ls", nos muestra que hay un solo archivo que es (readme),usamos el comando "cat readme" para que me muestre el contenido del archivo.
Al final la

contraseña es: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

# level 1 → level 2:

para poder hallar la contraseña una vez logueado use el comando "ls", nos muestra que hay un solo archivo que es (-),usamos el comando "cat ./-" para que ver el contenido del archivo,el comando ayuda a entrar al directorio actual
y no un parametro especial.Al final la 

contraseña es: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

# level 2 → level 3:

para poder hallar la contraseña una vez logueado use el comando "ls", nos muestra que hay un solo archivo que es (spaces in this filename),usamos el comando "cat "spaces in this filename" para que ver el contenido del archivo,el comando ayuda a entrar al directorio actual.Al final la 

contraseña es: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

# level 3 → level 4:

para poder hallar la contraseña una vez logueado use el comando "ls", nos muestra que hay un solo archivo que es (inhere),usamos el comando "ls -la" para que ver el contenido del archivo,el comando "-la" ayuda a ver los archivos ocultos, en este caso existia el archivo (...Hiding-From-You), lo abrimos con el comando "cat ...Hiding-From-You" .Al final la

contraseña es: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
 
# level 4 → level 5:

para poder hallar la contraseña una vez logueado use el comando "ls", nos muestra que hay un solo archivo que es (inhere),usamos el comando "ls" para que ver el contenido del archivo,nos sale varios archivos que tienen de nombre -file00,01,02,03,...,09 en vez de ver que tiene uno por uno, usaremos el comando "file ./-file0*" este comando mostrara que contenido tienen todos los archivos, vemos que la mayoria de los archivos contienen data exepto el archivo -file07 que dice que contiene ASCII text, lo abrimos con el comando "cat ./-file 07 y al final la

contraseña es: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

# level 5 → level 6:

una vez logueados usamos el comando "ls" y entramos al directorio que aparece con el comando "cd inhere", usamos el comando "ls -l", y nos muestra varios archivos y cada archivo contiene mas de 5 ficheros, para no leer un por uno, usamos el comando "find ./ -type f -size 1033c" para que busque el tipo de archivo con un tamaño de 1033 bytes y nos muestras un fichero, que es (./maybehere07/.file2), usamos el comando "cat ./maybehere07/.file2" y al final la 
 
contraseña es: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
 
# level 6 → level 7:

una vez logueados usamos el comando "find" con las especificaciones que nos dio el nivel, usamos el comando "find / -user bandit7 -group bandit6 -size 33c 2>/dev/null" al comando le estamos dando las especificaciones de su nombre de usuario (bandit7), el nombre de su grupo (bandit6) y el tamaño de (33 bytes) al final la 

contraseña es: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

# level 7 → level 8:

una vez logueados en bandit usamos el comando "ls" nos muestra el archivo(data.txt),usamos el comando "cat data.txt" y nos muestra lo que parece ser muchas contraseñas junto con diferentes palabras.Lo que hacemos es poner el comando junto con la palabra que nos el nivel "grep millionth data.txt" y al final la 

contraseña es: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
 
# level 8 → level 9:

una vez logueados usamos el comando "ls" nos muestra el archivo(data.txt),usamos el comando "cat data.txt" y nos muestra lo que parece ser muchas contraseñas repetidas, usamos el comando "sort data.txt | uniq -u" este comando lo que hace es buscar una linea unica diferente que no se este repitiendo, esa info la sacamos usando el comando "man uniq" que nos dice que al usar "uniq -u" se estaria buscando lineas unicas. Al final la 

contraseña es: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
 
# level 9 → level 10:

para poder hallar la contraseña usamos el comando "ls" nos muestra que existe un archivo (data.txt), vemos que contiene el archivo con el comando "cat data.txt", nos salio un monton de codigo binario con signos de interrogacion y algunas letras que si se pueden leer, usamos el comando "strings data.txt" y vemos que nos trata de mostrar lo que se entiende como mensajes (the password is), lo que quiere decir, la 

contraseña es: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
 
# level 10 → level 11:

para poder hallar la contraseña usamos el comando "ls" nos muestra que existe un archivo (data.txt), vemos que contiene el archivo con el comando "cat data.txt", nos sale lo que parece ser la contraseña, por lo tanto usamos el comando con la informacion que nos dio el nivel que contiene datos codificados de lo que contiene el archivo "cat data.txt | base64 -d". Al final la 

contraseña es: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
 
# level 11 → level 12:

para hallar la contraseña use el comando "ls", nos mostro el archivo (data.txt), vemos lo que contiene con el comando "cat data.txt", nos mostro lo que parece ser la contraseña, seguidamente usamos un comando que hace que rote 13 veces "echo "Gur cnffjbeq vf 7k16JArUVv5LxVuJfsSVdbbtaHGlw9D4" | tr 'A-Za-z' 'N-ZA-Mn-za-m'" lo que hara que la nos muestre la contraseña. Al final la 

contraseña es: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
 
# level 12 → level 13:


contraseña es: 
 
# level 13 → level 14:


contraseña es: 
 
# level 14 → level 15:


contraseña es: 
 
# level 15 → level 16:


contraseña es: 
 
# level 16 → level 17:


contraseña es: 
 
# level 17 → level 18:


contraseña es: 
 
# level 18 → level 19:


contraseña es: 
 
# level 19 → level 20:


contraseña es: 
 
# level 20 → level 21:


contraseña es: 
 
# level 21 → level 22:


contraseña es: 
 
# level 22 → level 23:


contraseña es: 
 
# level 23 → level 24:


contraseña es: 
 
# level 24 → level 25:


contraseña es: 
 
# level 25 → level 26:


contraseña es: 
 
# level 26 → level 27:


contraseña es: 
 
# level 27 → level 28:


contraseña es: 
 
# level 28 → level 29:


contraseña es: 
 
# level 29 → level 30:


contraseña es: 
 
# level 30 → level 31:


contraseña es: 
 
# level 31 → level 32:


contraseña es: 
 
# level 32 → level 33:


contraseña es: 
 
# level 33 → level 34:


contraseña es: 
 

