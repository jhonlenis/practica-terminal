# practica-terminal

# Leccion 1: Ejercicio Practico

se rreó el directorio proyecto_final.  
Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyecto_final

Entraste a ese directorio.
Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd proyecto_final/

Creaste tres subdirectorios:
codigo, documentacion, recursos
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir codigo documentacion recursos

Creaste dos archivos dentro de codigo:
main.py y config.json
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch codigo/main.py codigo/config.json

Creaste el archivo README.md dentro de documentacion
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch documentacion/README.md

Mostró la estructura completa del proyecto.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ tree proyecto_final
proyecto_final/
├── codigo
│   ├── main.py
│   └── config.json
├── documentacion
│   └── README.md
└── recursos

# Laboratorio 1

Crea un archivo vacío llamado prueba.txt en el directorio actual.
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch prueba.txt

Muestra el contenido del directorio actual.
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
codigo  documentacion  prueba.txt  recursos

# Laboratorio 2

Crea tres archivos vacíos al mismo tiempo:
archivo1.txt archivo2.txt y archivo3.txt
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch archivo1.txt archivo2.txt archivo3.txt

Muestra todo el contenido del directorio actual.
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  recursos
archivo2.txt  codigo        prueba.txt

# Laboratorio 3

Crea el archivo prueba.txt
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch prueba.txt

Muestra el contenido del directorio en formato detallad
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls -l
total 12
-rw-rw-rw-  1 codespace codespace    0 Feb 25 01:26 archivo1.txt
-rw-rw-rw-  1 codespace codespace    0 Feb 25 01:26 archivo2.txt
-rw-rw-rw-  1 codespace codespace    0 Feb 25 01:26 archivo3.txt
drwxrwxrwx+ 2 codespace codespace 4096 Feb 25 01:14 codigo
drwxrwxrwx+ 2 codespace codespace 4096 Feb 25 01:15 documentacion
-rw-rw-rw-  1 codespace codespace    0 Feb 25 01:27 prueba.txt
drwxrwxrwx+ 2 codespace codespace 4096 Feb 25 01:14 recursos

# Laboratorio 4

Crea un nuevo directorio llamado documentos dentro de proyecto_final.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir documentos

Muestra el contenido del directorio actual.
Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  prueba.txt
archivo2.txt  codigo        documentos     recursos

# Laboratoria 5

Crea tres directorios al mismo tiempo:
fotos, videos y música
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir fotos videos música

Muestra el contenido del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  fotos   prueba.txt  videos
archivo2.txt  codigo        documentos     música  recursos

# Laboratorio 6

Crea una estructura de directorios completa. La opción -p permite crear carpetas anidadas aunque no existan las anteriores.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir -p proyecto/src/main

Muestra en forma de árbol la estructura del directorio proyecto.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ tree proyecto
proyecto
└── src
    └── main

3 directories, 0 files

- Laboratorio 7

Crea un nuevo directorio llamado trabajo.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir trabajo

Crea dos archivos dentro del directorio trabajo:
informe.txt y notas.md
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch trabajo/informe.txt trabajo/notas.md

Muestra el contenido del directorio trabajo.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls trabajo
informe.txt  notas.md

# Laboratorio 8

Crea la carpeta biblioteca y dentro de ella tres subcarpetas al mismo tiempo:
libros, revistas y artículos
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir -p biblioteca/{libros,revistas,artículos}

Crea dos archivos en carpetas específicas:
novela.txt dentro de libros
ciencia.md dentro de revistas
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch biblioteca/libros/novela.txt biblioteca/revistas/ciencia.md

Muestra la estructura en forma de árbol.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ tree biblioteca
biblioteca
├── artículos
├── libros
│   └── novela.txt
└── revistas
    └── ciencia.md

4 directories, 2 files

# Laboratorio 9

Crea una nueva carpeta llamada mi_proyecto.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir mi_proyecto

Entra a la carpeta mi_proyecto.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ cd mi_proyecto

Crea tres subcarpetas dentro de mi_proyecto:
codigo, documentacion y recursos
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ mkdir codigo documentacion recursos

Crea dos archivos dentro de la carpeta codigo:
main.py y config.json
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ touch codigo/main.py codigo/config.json

Crea el archivo README.md dentro de documentacion.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ touch documentacion/README.md

Muestra la estructura completa del proyecto en forma de árbol.
comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ tree
mi_proyecto/
├── codigo
│   ├── config.json
│   └── main.py
├── documentacion
│   └── README.md
└── recursos

4 directories, 3 files

# Leccion 2: Desafio final 

Cambia al directorio absoluto /var/log (carpeta de registros del sistema).
Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd /var/log

Sube un nivel en la estructura.
Estabas en /var/log, ahora pasas a /var.
comando: @jhonlenis ➜ /var/log $ cd ..

Regresa al último directorio visitado.
Vuelve de /var a /var/log.
comando: @jhonlenis ➜ /var $ cd -
/var/log

Va al directorio personal del usuario (home).
comando: @jhonlenis ➜ /var/log $ cd ~

Muestra la ruta actual.
Resultado: /home/codespace
comando: @jhonlenis ➜ ~ $ pwd
/home/codespace

# Laboratorios de Aprendizaje: Laboratorio 1

Muestra la ruta completa del directorio donde estás ubicado actualmente.
comando: @jhonlenis ➜ ~ $ pwd
/home/codespace

¿Qué significa la ruta mostrada?
R/ es tu Directorio de Trabajo Actual

Tarea: Copia la ruta mostrada y explica qué representa cada parte.
R/  home/ Es el directorio de usuario 
codespace / Nombre de usuario 

# Laboratorio 2

Cambia al directorio raíz del sistema.
comando: @jhonlenis ➜ ~ $ cd /

/ es el nivel más alto de todas las carpetas en Linux.
pwd
→ Muestra el directorio actual.
comando: @jhonlenis ➜ / $ pwd
/

Tarea: Enumera los directorios principales que ves al ejecutar ls.
R/ tmp/ workspaces

# Laboratorio 3

Cambia al directorio /home, donde se encuentran las carpetas de los usuarios.
comando: @jhonlenis ➜ / $ cd /home
@jhonlenis ➜ /home $ 

Muestra el directorio actual.
Resultado: /home
comando: @jhonlenis ➜ /home $ pwd
/home

Tarea: Intenta cambiar al directorio de tu usuario (por ejemplo, /home/tu_usuario).

Entra a la carpeta del usuario codespace dentro de /home.
Después aparece el símbolo ~, que representa tu directorio personal
R/ @jhonlenis ➜ /home $ cd codespace/
@jhonlenis ➜ ~ $ 

# Laboratorio 4

Tarea: Sin usar /, cambia al directorio Documentos dentro de tu directorio personal.

Cambia al directorio llamado documentos que está dentro del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd documentos

# Laboratorio 5 

Cambia al directorio /tmp, que es una carpeta temporal del sistema.
Es una ruta absoluta (empieza con /).
Comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd /tmp
@jhonlenis ➜ /tmp $ 

Regresa al directorio anterior en el que estabas.
comando: @jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $

Tarea: Repite este proceso varias veces y observa cómo funciona cd -.

Regresa al directorio anterior en el que estabas.
R/ @jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
Regresa al directorio anterior en el que estabas.
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd -
/tmp
Regresa al directorio anterior en el que estabas.
@jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ 

# Laboratorio 6

Te lleva al directorio personal (home) del usuario.
~ representa /home/codespace.
comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd ~
@jhonlenis ➜ ~ $ 

Tarea: Crea un archivo llamado prueba.txt en tu directorio personal.

Muestra la ruta actual. Resultado: /home/codespace
R/ @jhonlenis ➜ ~ $ pwd
/home/codespace
Crea un archivo vacío llamado prueba.txt en tu carpeta personal.
@jhonlenis ➜ ~ $ touch prueba.txt
Muestra el contenido del directorio actual.
@jhonlenis ➜ ~ $ ls
java  nvm  prueba.txt

# Laboratorio 7 

Sube un nivel en la estructura de carpetas.
Pasaste de /workspaces/practica-terminal a /workspaces.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd ..
@jhonlenis ➜ /workspaces $ 

Tarea: Sube dos niveles consecutivos y verifica tu ubicación con pwd.

ube dos niveles desde donde estabas.
Desde /workspaces:
R/@jhonlenis ➜ /workspaces $ cd ../..

Muestra el directorio actual.
Resultado: /
@jhonlenis ➜ / $ pwd
/
@jhonlenis ➜ / $ 

# Laboratorio 8

Cambia al directorio /home, donde están las carpetas de los usuarios.
comando: @jhonlenis ➜ / $ cd /home
@jhonlenis ➜ /home $ 

Entra a la carpeta del usuario codespace.
El símbolo ~ aparece porque representa /home/codespace.
comando: @jhonlenis ➜ /home $ cd codespace
@jhonlenis ➜ ~ $ 

Crea una nueva carpeta llamada Descargas dentro de tu directorio personal.
comando: @jhonlenis ➜ ~ $ mkdir Descargas
@jhonlenis ➜ ~ $ 

Entra a la carpeta Descargas.
Ahora estás en: ~/Descargas (es decir, /home/codespace/Descargas).
comando: @jhonlenis ➜ /home $ cd codespace/Descargas
@jhonlenis ➜ ~/Descargas $ 

Tarea: Explica la diferencia entre rutas relativas y absolutas.
R/ Las rutas absolutas son direcciones completas que parten desde la raíz del sistema (/), funcionando de forma independiente a tu ubicación actual. Por el contrario, las rutas relativas definen un camino basado exclusivamente en el directorio donde te encuentras en ese momento, sin usar la barra inicial. Mientras la absoluta es como una coordenada GPS invariable, la relativa es una instrucción de dirección que cambia según tu punto de partida.

# Laboratorio 9

Crea una carpeta llamada pruebas dentro de tu directorio personal.
~ representa /home/codespace.
comando: r directory
@jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir ~/pruebas

Entra directamente a la carpeta pruebas usando la ruta del home.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd ~/pruebas
@jhonlenis ➜ ~/pruebas $ 

Crea una subcarpeta llamada nivel1 dentro de pruebas.
comando: @jhonlenis ➜ ~/pruebas $ mkdir nivel1

Entras a la carpeta nivel1
comando: @jhonlenis ➜ ~/pruebas $ cd nivel1
@jhonlenis ➜ ~/pruebas/nivel1 $ 

# Laboratorio 10

Te lleva directamente a tu directorio personal (home).
comando: @jhonlenis ➜ ~ $ cd /home/codespace

Muestra todos los archivos, incluidos los ocultos.
Los que empiezan con .
@jhonlenis ➜ ~ $ ls -a
.             .jupyter    .rvmrc
..            .local      .vscode-remote
.bash_logout  .maven      .zprofile
.bashrc       .minikube   .zshrc
.cache        .nvs        Descargas
.conda        .oh-my-zsh  java
.config       .php        nvm
.docker       .profile    prueba.txt
.dotnet       .python     pruebas
.gitconfig    .rbenv
.hugo         .ruby
@jhonlenis ➜ ~ $ 

Entra a la carpeta oculta .config.
comando: @jhonlenis ➜ ~ $ cd .config
@jhonlenis ➜ ~/.config $ 

Muestra la ruta actual.
comando: @jhonlenis ➜ ~/.config $ pwd
/home/codespace/.config
@jhonlenis ➜ ~/.config $ 

# Leccion 3: Ejercicio 1

Muestra el contenido del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  proyecto_final

# Ejercicio 2

Muestra todos los archivos y carpetas, incluidos los ocultos (los que empiezan con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.   .git       documentos
..  README.md  proyecto_final
@jhonlenis ➜ /workspaces/practica-t

# Ejercicio 3

Muestra el contenido del directorio en formato detallado
comando:  $ ls -l
total 20
-rw-rw-rw-   1 codespace root      9190 Feb 26 02:22 README.md
drwxrwxrwx+  2 codespace codespace 4096 Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace 4096 Feb 25 01:33 proyecto_final

Responde: ¿Qué significa el primer carácter d en algunos elementos?
R/ El primer carácter d significa Directory (Directorio).

Indica que ese elemento no es un archivo de datos (como un texto o una imagen), sino una carpeta que contiene otros archivos o subdirectorios. En tu lista, documentos y proyecto_final son carpetas porque empiezan con d.

# Ejercicio 4

Muestra el contenido del directorio con detalle, incluyendo archivos ocultos y tamaños en formato legible.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lah
total 32K
drwxrwxrwx+  5 codespace root      4.0K Feb 25 02:09 .
drwxr-xrwx+  5 codespace root      4.0K Feb 25 01:05 ..
drwxrwxrwx+  8 codespace root      4.0K Feb 25 17:22 .git
-rw-rw-rw-   1 codespace root      9.6K Feb 26 02:24 README.md
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final

# Ejercicio 5

Crea una carpeta llamada mi_practica.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir mi_practica

Entra a la carpeta mi_practica.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd mi_practica
@jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ 

Crea dos archivos vacíos: archivo1.txt y archivo2.txt
comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ touch archivo1.txt archivo2.txt

Crea dos subcarpetas: carpeta1 y carpeta2
comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ mkdir carpeta1 carpeta2

Muestra todo con detalle, incluidos ocultos y tamaños en formato legible.
comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ ls -lah
total 16K
drwxrwxrwx+ 4 codespace codespace 4.0K Feb 26 02:26 .
drwxrwxrwx+ 6 codespace root      4.0K Feb 26 02:25 ..
-rw-rw-rw-  1 codespace codespace    0 Feb 26 02:25 archivo1.txt
-rw-rw-rw-  1 codespace codespace    0 Feb 26 02:25 archivo2.txt
drwxrwxrwx+ 2 codespace codespace 4.0K Feb 26 02:26 carpeta1
drwxrwxrwx+ 2 codespace codespace 4.0K Feb 26 02:26 carpeta2

Muestra el contenido de forma recursiva (incluye subdirectorios).
Indica que carpeta1 y carpeta2 están vacías.
comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ ls -R
.:
archivo1.txt  archivo2.txt  carpeta1  carpeta2

./carpeta1:

./carpeta2:

# Laboratios de Aprendizajes: Laboratorio 1

Muestra el contenido del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  mi_practica  proyecto_final

¿Qué sucede si ejecutas ls en un directorio vacío?
R/No va a salir nada porque si estas en una carpeta en la linea de comandos cuando ejecutas ls te va a salir vacio

# Laboratorio 2

Muestra todos los archivos, incluidos los ocultos (los que empiezan con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.  ..  .git  README.md  documentos  mi_practica  proyecto_final

Crea un archivo oculto llamado .mi_archivo_secreto.
Es oculto porque empieza con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch .mi_archivo_secreto

Vuelve a mostrar todo, y ahora aparece: .mi_archivo_secreto → Nuevo archivo oculto creado.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.   .git                 README.md   mi_practica
..  .mi_archivo_secreto  documentos  proyecto_final

¿Por qué crees que algunos archivos están ocultos por defecto?
R/ Los archivos se ocultan principalmente para evitar el desorden visual, manteniendo la carpeta personal limpia de archivos de configuración técnica.

# Laboratorio 3

Muestra el contenido del directorio en formato detallado.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l
total 24
-rw-rw-rw-   1 codespace root      12272 Feb 26 02:34 README.md
drwxrwxrwx+  2 codespace codespace  4096 Feb 25 02:09 documentos
drwxrwxrwx+  4 codespace codespace  4096 Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace  4096 Feb 25 01:33 proyecto_final

Crea un archivo vacío llamado prueba.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

Muestra el contenido del directorio.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  mi_practica  proyecto_final  prueba.txt

¿Qué permisos tiene el archivo?
R/ el archivo tendrá permisos rw-rw-rw- (lectura y escritura para todos) o rw-r--r-- (lectura/escritura para ti y solo lectura para el resto).
¿Quién es el propietario?
R/ El propietario es codespace.

# Laboratorio 4

Lista los archivos con detalles y tamaños en formato legible (K, M).
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lh
total 28K
-rw-rw-rw-   1 codespace root       13K Feb 26 02:38 README.md
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+  4 codespace codespace 4.0K Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:35 prueba.txt

Crea un archivo grande de prueba.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ dd if=/dev/zero of=archivo_grande bs=1M count=10
10+0 records in
10+0 records out
10485760 bytes (10 MB, 10 MiB) copied, 0.0100094 s, 1.0 GB/s

Confirma que ahora existe: archivo_grande con tamaño 10M.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lh
total 11M
-rw-rw-rw-   1 codespace root       14K Feb 26 02:39 README.md
-rw-rw-rw-   1 codespace codespace  10M Feb 26 02:39 archivo_grande
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+  4 codespace codespace 4.0K Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:35 prueba.txt

¿Por qué es útil mostrar el tamaño en formato legible?
R/ Es útil principalmente por claridad y rapidez en la toma de decisiones.

# Laboratorio 5

comando: total 10268
-rw-rw-rw-   1 codespace root         14320 Feb 26 02:41 README.md
-rw-rw-rw-   1 codespace codespace 10485760 Feb 26 02:39 archivo_grande
-rw-rw-rw-   1 codespace codespace        0 Feb 26 02:35 prueba.txt
drwxrwxrwx+  4 codespace codespace     4096 Feb 26 02:26 mi_practica
drwxrwxrwx+  2 codespace codespace     4096 Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace     4096 Feb 25 01:33 proyecto_final

sirve para ver qué archivo fue modificado más recientemente, mostrando primero el más nuevo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lt
total 10272
-rw-rw-rw-   1 codespace codespace        4 Feb 26 02:43 prueba.txt
-rw-rw-rw-   1 codespace root         14749 Feb 26 02:41 README.md
-rw-rw-rw-   1 codespace codespace 10485760 Feb 26 02:39 archivo_grande
drwxrwxrwx+  4 codespace codespace     4096 Feb 26 02:26 mi_practica
drwxrwxrwx+  2 codespace codespace     4096 Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace     4096 Feb 25 01:33 proyecto_final

¿Dónde aparece ese archivo en la lista?
R/ Este archivo aparece de primeras y se ve el cambio a la hora de modificarlo 

# Laboratorio 6

Crea una estructura de carpetas anidadas. -p permite crear todos los niveles aunque no existan.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p mi_directorio/subdirectorio1/subdirectorio2

Crea el archivo archivo1.txt dentro de mi_directorio.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch mi_directorio/archivo1.txt

Crea el archivo archivo2.txt dentro de subdirectorio1.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch mi_directorio/subdirectorio1/archivo2.txt

Lista todo el contenido de forma recursiva (muestra carpetas y subcarpetas).
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -R
.:
README.md       documentos     mi_practica     prueba.txt
archivo_grande  mi_directorio  proyecto_final

./documentos:

./mi_directorio:
archivo1.txt  subdirectorio1

./mi_directorio/subdirectorio1:
archivo2.txt  subdirectorio2

./mi_directorio/subdirectorio1/subdirectorio2:

./mi_practica:
archivo1.txt  archivo2.txt  carpeta1  carpeta2

./mi_practica/carpeta1:

./mi_practica/carpeta2:

./proyecto_final:
archivo1.txt  biblioteca     documentos   música      recursos
archivo2.txt  codigo         fotos        proyecto    trabajo
archivo3.txt  documentacion  mi_proyecto  prueba.txt  videos

./proyecto_final/biblioteca:
artículos  libros  revistas

./proyecto_final/biblioteca/artículos:

./proyecto_final/biblioteca/libros:
novela.txt

./proyecto_final/biblioteca/revistas:
ciencia.md

./proyecto_final/codigo:
config.json  main.py

./proyecto_final/documentacion:
README.md

./proyecto_final/documentos:

./proyecto_final/fotos:

./proyecto_final/mi_proyecto:
codigo  documentacion  recursos

./proyecto_final/mi_proyecto/codigo:
config.json  main.py

./proyecto_final/mi_proyecto/documentacion:
README.md

./proyecto_final/mi_proyecto/recursos:

./proyecto_final/música:

./proyecto_final/proyecto:
src

./proyecto_final/proyecto/src:
main

./proyecto_final/proyecto/src/main:

./proyecto_final/recursos:

./proyecto_final/trabajo:
informe.txt  notas.md

./proyecto_final/videos:

¿Cómo ayuda la opción R a explorar directorios grandes?
R/ Es ideal para auditar jerarquías complejas en un solo comando, ya que despliega el contenido de cada "rama" del árbol de archivos. Esto ahorra tiempo al buscar elementos específicos que están enterrados en niveles profundos del sistema.

# Laboratorio 7

Lista todo con detalle: permisos, tamaño en formato legible (K, M) y archivos ocultos (los que empiezan con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lah
total 11M
drwxrwxrwx+  7 codespace root      4.0K Feb 26 02:45 .
drwxr-xrwx+  5 codespace root      4.0K Feb 25 01:05 ..
drwxrwxrwx+  8 codespace root      4.0K Feb 25 17:22 .git
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:33 .mi_archivo_secreto
-rw-rw-rw-   1 codespace root       18K Feb 26 02:48 README.md
-rw-rw-rw-   1 codespace codespace  10M Feb 26 02:39 archivo_grande
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+  3 codespace codespace 4.0K Feb 26 02:46 mi_directorio
drwxrwxrwx+  4 codespace codespace 4.0K Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final
-rw-rw-rw-   1 codespace codespace    4 Feb 26 02:43 prueba.txt

Crea dos carpetas:
proyectos (normal)
.secretos (oculta, porque empieza con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyectos .secretos
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch notas.txt manual.pdf
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch .config_personal .password_backup
@jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Hola Mundo" > info.txt

ista todo con detalle: permisos, tamaño en formato legible (K, M) y archivos ocultos (los que empiezan con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lah
total 11M
drwxrwxrwx+  9 codespace root      4.0K Feb 26 02:50 .
drwxr-xrwx+  5 codespace root      4.0K Feb 25 01:05 ..
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:50 .config_personal
drwxrwxrwx+  8 codespace root      4.0K Feb 25 17:22 .git
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:33 .mi_archivo_secreto
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:50 .password_backup
drwxrwxrwx+  2 codespace codespace 4.0K Feb 26 02:49 .secretos
-rw-rw-rw-   1 codespace root       19K Feb 26 02:50 README.md
-rw-rw-rw-   1 codespace codespace  10M Feb 26 02:39 archivo_grande
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
-rw-rw-rw-   1 codespace codespace   11 Feb 26 02:50 info.txt
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:49 manual.pdf
drwxrwxrwx+  3 codespace codespace 4.0K Feb 26 02:46 mi_directorio
drwxrwxrwx+  4 codespace codespace 4.0K Feb 26 02:26 mi_practica
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:49 notas.txt
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final
drwxrwxrwx+  2 codespace codespace 4.0K Feb 26 02:49 proyectos
-rw-rw-rw-   1 codespace codespace    4 Feb 26 02:43 prueba.txt

# Laboratorio 8

Muestra solo los directorios del lugar actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -d */
documentos/  mi_directorio/  mi_practica/  proyecto_final/  proyectos/

Crea tres nuevas carpetas: nombres, apellidos y edad
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir nombres apellidos edad
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch notas.txt manual.pdf script.sh

Muestra solo los directorios del lugar actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -d */
apellidos/   edad/   mi_directorio/  nombres/         proyectos/
documentos/  fotos/  mi_practica/    proyecto_final/  videos/

# Laboratorio 9

Muestra la lista detallada del directorio
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l
total 10308
-rw-rw-rw-   1 codespace root         20411 Feb 26 02:54 README.md
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:53 apellidos
-rw-rw-rw-   1 codespace codespace 10485760 Feb 26 02:39 archivo_grande
drwxrwxrwx+  2 codespace codespace     4096 Feb 25 02:09 documentos
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:53 edad
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:52 fotos
-rw-rw-rw-   1 codespace codespace       11 Feb 26 02:50 info.txt
-rw-rw-rw-   1 codespace codespace        0 Feb 26 02:53 manual.pdf
drwxrwxrwx+  3 codespace codespace     4096 Feb 26 02:46 mi_directorio
drwxrwxrwx+  4 codespace codespace     4096 Feb 26 02:26 mi_practica
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:53 nombres
-rw-rw-rw-   1 codespace codespace        0 Feb 26 02:53 notas.txt
drwxrwxrwx+ 13 codespace codespace     4096 Feb 25 01:33 proyecto_final
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:49 proyectos
-rw-rw-rw-   1 codespace codespace        4 Feb 26 02:43 prueba.txt
-rw-rw-rw-   1 codespace codespace        0 Feb 26 02:53 script.sh
drwxrwxrwx+  2 codespace codespace     4096 Feb 26 02:52 videos

Crea un archivo vacío llamado secreto.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch secreto.txt
@jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l secreto.txt
-rw-rw-rw- 1 codespace codespace 0 Feb 26 02:55 secreto.txt
@jhonlenis ➜ /workspaces/practica-terminal (main) $ chmod 000 secreto.txt
@jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l secreto.txt
---------- 1 codespace codespace 0 Feb 26 02:55 secreto.txt

¿Que Cambió?
Antes: Tenías algo como -rw-r--r-- (indicando que podías leer y escribir).
Después: Verás ----------. Los guiones significan que el permiso ha sido revocado.

# Laboratorio 10

Crea la carpeta proyecto y dentro de ella tres subcarpetas: documentos, imagenes, temp y Las {} permiten crear varias carpetas en una sola línea
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p proyecto/{documentos,imagenes,temp}

Crea el archivo reporte.txt dentro de documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/documentos/reporte.txt

Crea el archivo foto.jpg dentro de imagenes.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/imagenes/foto.jpg

Crea el archivo archivo_temporal dentro de temp.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/temp/archivo_temporal

Crea un archivo oculto llamado .configuracion dentro de proyecto (es oculto porque empieza con .
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/.configuracion

¿Qué opción usarías para encontrar rápidamente un archivo oculto importante?
R/ La opción ideal sería ls -la (o ls -lah para ver el tamaño).

# Leccion 4: Ejercicio 1

Crea un archivo vacío llamado prueba.txt
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

Copia el archivo prueba.txt y crea una copia llamada copia_prueba.txt.
cp significa copy
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp prueba.txt copia_prueba.txt

Muestra el contenido del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md         documentos  manual.pdf     notas.txt       prueba.txt
apellidos         edad        mi_directorio  proyecto        script.sh
archivo_grande    fotos       mi_practica    proyecto_final  videos
copia_prueba.txt  info.txt    nombres        proyectos
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

# Ejercicio 2

Crea un directorio llamado carpeta1.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir carpeta1

Crea un archivo llamado archivo1.txt dentro de carpeta1.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch carpeta1/archivo1.txt

Copia la carpeta carpeta1 completa y crea una nueva llamada carpeta2.
-r significa recursivo (copia carpetas y su contenido).
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -r carpeta1 carpeta2

Muestra todos los archivos y carpetas de forma recursiva, es decir, enseña también lo que hay dentro de cada subcarpeta.
comando: ls -R
.:
README.md       copia_prueba.txt  manual.pdf     proyecto        videos
apellidos       documentos        mi_directorio  proyecto_final
archivo_grande  edad              mi_practica    proyectos
carpeta1        fotos             nombres        prueba.txt
carpeta2        info.txt          notas.txt      script.sh

./apellidos:

./carpeta1:
archivo1.txt

./carpeta2:
archivo1.txt

./documentos:

./edad:

./fotos:

./mi_directorio:
archivo1.txt  subdirectorio1

./mi_directorio/subdirectorio1:
archivo2.txt  subdirectorio2

./mi_directorio/subdirectorio1/subdirectorio2:

./mi_practica:
archivo1.txt  archivo2.txt  carpeta1  carpeta2

./mi_practica/carpeta1:

./mi_practica/carpeta2:

./nombres:

./proyecto:
documentos  imagenes  temp

./proyecto/documentos:
reporte.txt

./proyecto/imagenes:
foto.jpg

./proyecto/temp:
archivo_temporal

./proyecto_final:
archivo1.txt  biblioteca     documentos   música      recursos
archivo2.txt  codigo         fotos        proyecto    trabajo
archivo3.txt  documentacion  mi_proyecto  prueba.txt  videos

./proyecto_final/biblioteca:
artículos  libros  revistas

./proyecto_final/biblioteca/artículos:

./proyecto_final/biblioteca/libros:
novela.txt

./proyecto_final/biblioteca/revistas:
ciencia.md

./proyecto_final/codigo:
config.json  main.py

./proyecto_final/documentacion:
README.md

./proyecto_final/documentos:

./proyecto_final/fotos:

./proyecto_final/mi_proyecto:
codigo  documentacion  recursos

./proyecto_final/mi_proyecto/codigo:
config.json  main.py

./proyecto_final/mi_proyecto/documentacion:
README.md

./proyecto_final/mi_proyecto/recursos:

./proyecto_final/música:

./proyecto_final/proyecto:
src

./proyecto_final/proyecto/src:
main

./proyecto_final/proyecto/src/main:

./proyecto_final/recursos:

./proyecto_final/trabajo:
informe.txt  notas.md

./proyecto_final/videos:

./proyectos:

./videos:
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

# Ejercicio 3

Copia archivo1.txt desde carpeta1 hacia carpeta2.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -fv carpeta1/archivo1.txt carpeta2/
'carpeta1/archivo1.txt' -> 'carpeta2/archivo1.txt'

# Laboratio 1

Crea un nuevo archivo vacío llamado archivo1.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo1.txt

Hace una copia de archivo1.txt con el nombre copia_archivo1.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt copia_archivo1.txt

Muestra los archivos y carpetas del directorio actual.
Aquí se ve que ahora existen: archivo1.txt y copia_archivo1.txt
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md       copia_archivo1.txt  manual.pdf     proyecto_final
apellidos       copia_prueba.txt    mi_directorio  proyectos
archivo1.txt    documentos          mi_practica    prueba.txt
archivo_grande  edad                nombres        script.sh
carpeta1        fotos               notas.txt      videos
carpeta2        info.txt            proyecto
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

¿Qué sucede si intentas copiar un archivo que no existe?
R/ Si intentas copiar un archivo que no está ahí la terminal te dará un mensaje de error 
¿Qué pasa si el archivo de destino ya existe?
R/ El comando cp sobrescribirá el archivo de destino silenciosamente. Perderás el contenido anterior del archivo de destino y será reemplazado por el nuevo.

# Laboratorio 2

Intenta crear una carpeta llamada documentos.
❌ Error: File exists Significa que esa carpeta ya existe.
comando:  mkdir documentos
mkdir: cannot create directory ‘documentos’: File exists

Copia el archivo archivo1.txt dentro de la carpeta documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt documentos/

Entra a la carpeta documentos.
cd significa change directory (cambiar de directorio).
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ 

Muestra el contenido de la carpeta actual.
Aquí aparece:
archivo1.txt ✅ (porque fue copiado allí).
comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ ls
archivo1.txt

¿Qué sucede si el directorio de destino no existe?
R/ Si intentas copiar un archivo a un directorio que no existe, el sistema mostrará un error y la copia no se realizará.
¿Cómo puedes copiar un archivo a un directorio fuera del directorio actual?
R/ Debes indicar la ruta del directorio destino. Puedes usar como ejemplo cp archivo.txt ../carpeta_destino/

# Laboratorio 3

Crea tres archivos vacíos llamados archivo2.txt, archivo3.txt y archivo4.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ touch archivo2.txt archivo3.txt archivo4.txt

Copia los tres archivos a la carpeta documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo2.txt archivo3.txt archivo4.txt documentos/

Muestra el contenido de la carpeta documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documentos/
archivo1.txt  archivo2.txt  archivo3.txt  archivo4.txt

¿Qué sucede si uno de los archivos no existe?
R/ Si intentas copiar un archivo que no existe, el sistema mostrará un mensaje de error indicando que no se encontró el archivo, y la copia no se realizará.
¿Cómo puedes copiar todos los archivos .txt de un directorio?
R/ Se utiliza el comodín * para seleccionar varios archivos. Esto copia todos los archivos con extensión .txt del directorio actual al directorio destino.

# Laboratorio 4

Intenta crear una carpeta llamada proyectos, pero aparece el error "File exists" porque esa carpeta ya existe.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyectos
mkdir: cannot create directory ‘proyectos’: File exists

Crea dos archivos vacíos (archivo5.txt y archivo6.txt) dentro de la carpeta proyectos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyectos/archivo5.txt proyectos/archivo6.txt

opia toda la carpeta proyectos y su contenido a una nueva carpeta llamada proyectos_copia.
-r significa copiar de forma recursiva (carpetas y archivos).
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -r proyectos proyectos_copia

Muestra los archivos dentro de proyectos_copia.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls proyectos_copia/
archivo5.txt  archivo6.txt

¿Qué sucede si omites la opción -r al copiar un directorio?
R/ En sistemas Linux o macOS, si intentas copiar un directorio sin usar la opción -r (recursiva), el comando cp mostrará un error y no copiará nada.
¿Cómo puedes copiar solo ciertos archivos dentro de un directorio?
R/ Puedes hacerlo usando comodines o especificando archivos concretos.
Usando comodines (*)
Especificando archivos manualmente
Usando patrones más específicos (ejemplo)
Copiar solo archivos .txt que tengan números:
cp carpeta/*[0-9].txt destino/

# Laboratorio 5

Crea un archivo vacío llamado archivo7.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo7.txt

Copia el archivo archivo7.txt dentro de la carpeta documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo7.txt documentos/

Copia el archivo nuevamente, pero la opción -f (force) sobrescribe el archivo si ya existe en la carpeta destino sin pedir confirmación.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -f archivo7.txt documentos/

¿Qué sucede si no usas la opción -f?
R/ La opción -f (force) en el comando cp se usa para forzar la copia, sobrescribiendo archivos sin pedir confirmación y sin mostrar ciertos errores.
¿Cómo puedes evitar que se sobrescriba un archivo existente?
R/ Puedes usar la opción -i (interactive), que pide confirmación antes de sobrescribir

# Laboratorio 6

Copia el archivo archivo7.txt a la carpeta documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -v archivo7.txt documentos/
'archivo7.txt' -> 'documentos/archivo7.txt'

¿Qué información adicional muestra la opción -v?
R/ La opción -v significa verbose (modo detallado).

Cuando la usas con cp, el comando muestra en pantalla qué archivos se están copiando y hacia dónde.
¿Cómo puedes combinar -v con otras opciones como -f?
R/ Puedes combinar varias opciones juntas en el mismo comando.
Ejemplo combinando -v (detallado) y -f (forzar):
cp -vf archivo.txt destino/

# Laboratorio 7

Crea un archivo vacío llamado archivo8.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo8.txt

Cambia la fecha de modificación del archivo archivo8.txt al 1 de enero de 2022.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch -d "2022-01-01" archivo8.txt

Copia el archivo archivo8.txt a copia_archivo8.txt manteniendo los permisos, propietario y fecha original.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -p archivo8.txt copia_archivo8.txt

Muestra la información detallada de ambos archivos (permisos, propietario, tamaño y fecha
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l archivo8.txt copia_archivo8.txt
-rw-rw-rw- 1 codespace codespace 0 Jan  1  2022 archivo8.txt
-rw-rw-rw- 1 codespace codespace 0 Jan  1  2022 copia_archivo8.txt

¿Qué atributos se preservan con la opción -p?
R/ La opción -p (preserve) en el comando cp permite conservar los atributos originales del archivo al copiarlo.
¿Qué sucede si no usas la opción -p?
R/ Si no usas -p:
El archivo copiado puede tener permisos diferentes, según la configuración por defecto del sistema (umask).

# Laboratorio 8

Crea tres archivos vacíos: archivo_a.txt, archivo_b.txt y archivo_c.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_a.txt archivo_b.txt archivo_c.txt

opia todos los archivos que empiezan con archivo_ y terminan en .txt al directorio documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo_*.txt documentos/

Muestra el contenido de la carpeta documentos, donde aparecen los archivos copiados.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documentos/
archivo1.txt  archivo3.txt  archivo7.txt   archivo_b.txt
archivo2.txt  archivo4.txt  archivo_a.txt  archivo_c.txt

¿Qué otros patrones puedes usar para seleccionar archivos?
R/ * → Cualquier cantidad de caracteres, ? → Un solo carácter, [ ] → Rango o conjunto de caracteres y [! ] → Excluir caracteres
¿Cómo puedes copiar archivos que terminen con un patrón específico?
R/ Si quieres copiar archivos que terminen con algo específico, usas * antes del patrón.

# Laboratorio 9

Crea la carpeta simulacion_usb dentro de /tmp.
La opción -p crea la ruta completa si no existe.
comando:@jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p /tmp/simulacion_usb

Crea el archivo archivo_externo.txt y escribe el texto “Este es un archivo del USB” dentro.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Este es un archivo del USB" > /tmp/simulacion_usb/archivo_externo.txt

Copia el archivo desde /tmp/simulacion_usb al directorio actual (.)
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp /tmp/simulacion_usb/archivo_externo.txt .

Muestra todos los archivos y carpetas del directorio actual, incluyendo archivo_externo.txt que se copió.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md      archivo_b.txt        documentos     proyecto
apellidos      archivo_c.txt        edad           proyecto_final
archivo1.txt   archivo_externo.txt  fotos          proyectos
archivo2.txt   archivo_grande       info.txt       proyectos_copia
archivo3.txt   carpeta1             manual.pdf     prueba.txt
archivo4.txt   carpeta2             mi_directorio  script.sh
archivo7.txt   copia_archivo1.txt   mi_practica    videos
archivo8.txt   copia_archivo8.txt   nombres
archivo_a.txt  copia_prueba.txt     notas.txt

¿Qué sucede si el dispositivo USB no está montado?
R/ Si el USB no está montado, el sistema no podrá acceder a su contenido Si intentas copiar archivos hacia él, aparecerá un error como:“No existe el archivo o directorio”
¿Cómo puedes verificar las ubicaciones de los dispositivos conectados?
R/ lsblk, fdisk -l, mount, /media/usuario/
/mnt/, df -h

# Laboratorio 10

¿Qué mensaje de error recibes cuando el archivo de origen no existe?
R/  @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo_inexistente.txt documentos/
cp: cannot stat 'archivo_inexistente.txt': No such file or directory

¿Qué mensaje de error recibes cuando el directorio de destino no existe?
R/ @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt directorio_inexistente/
cp: cannot create regular file 'directorio_inexistente/': Not a directory

Correcion: 

Copia el archivo archivo2.txt al directorio documentos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo2.txt documentos/

Crea un nuevo directorio llamado directorio_inexistente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir directorio_inexistente


comando: Copia el archivo archivo1.txt dentro del directorio directorio_inexistente.
@jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt directorio_inexistente/
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

# Leccion 5: Ejercicio 1

Crea un archivo vacío llamado archivo.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo.txt

enombra el archivo archivo.txt a nuevo_nombre.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv archivo.txt nuevo_nombre.txt

Muestra la lista de archivos y carpetas del directorio actual, donde aparece nuevo_nombre.txt después de renombrarlo.
comando: nombre.txt
@jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            archivo_grande          mi_directorio
apellidos            carpeta1                mi_practica
archivo1.txt         carpeta2                nombres
archivo2.txt         copia_archivo1.txt      notas.txt
archivo3.txt         copia_archivo8.txt      nuevo_nombre.txt
archivo4.txt         copia_prueba.txt        proyecto
archivo7.txt         directorio_inexistente  proyecto_final
archivo8.txt         documentos              proyectos
archivo_a.txt        edad                    proyectos_copia
archivo_b.txt        fotos                   prueba.txt
archivo_c.txt        info.txt                script.sh
archivo_externo.txt  manual.pdf              videos

# Ejercicio 2

Crea un directorio llamado carpeta_vieja en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir carpeta_vieja

Renombra el directorio carpeta_vieja a carpeta_nueva.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv carpeta_vieja carpeta_nueva

ista todos los archivos y carpetas del directorio actual, mostrando que carpeta_nueva reemplaza a carpeta_vieja.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md      archivo_c.txt           documentos        proyecto
apellidos      archivo_externo.txt     edad              proyecto_final
archivo1.txt   archivo_grande          fotos             proyectos
archivo2.txt   carpeta1                info.txt          proyectos_copia
archivo3.txt   carpeta2                manual.pdf        prueba.txt
archivo4.txt   carpeta_nueva           mi_directorio     script.sh
archivo7.txt   copia_archivo1.txt      mi_practica       videos
archivo8.txt   copia_archivo8.txt      nombres
archivo_a.txt  copia_prueba.txt        notas.txt
archivo_b.txt  directorio_inexistente  nuevo_nombre.txt

# Ejercicio 3

Crea un directorio llamado documento en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir documento

Crea un archivo vacío llamado informe.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch informe.txt

Mueve el archivo informe.txt al directorio documento.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv informe.txt documento/

Lista el contenido del directorio documento, mostrando que ahora contiene informe.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documento/
informe.txt

# Ejercicio 4

Crea tres archivos vacíos: archivo1.txt, archivo2.txt y archivo3.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo1.txt archivo2.txt archivo3.txt

Mueve todos los archivos que terminan en .txt del directorio actual al directorio documento/ usando el comodín *
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv *.txt documento/

ista el contenido del directorio documento, mostrando todos los archivos .txt que fueron movidos, incluidos los recién creados.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documento/
archivo1.txt  archivo8.txt         copia_archivo1.txt  notas.txt
archivo2.txt  archivo_a.txt        copia_archivo8.txt  nuevo_nombre.txt
archivo3.txt  archivo_b.txt        copia_prueba.txt    prueba.txt
archivo4.txt  archivo_c.txt        info.txt
archivo7.txt  archivo_externo.txt  informe.txt

# Ejercicio 5

Crea un archivo vacío llamado datos.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch datos.txt

Mueve el archivo datos.txt al directorio documento/ y lo renombra como backup_datos.txt al mismo tiempo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv datos.txt documento/backup_datos.txt

Lista los archivos dentro del directorio documento, mostrando que backup_datos.txt ahora está allí junto con los demás archivos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documento/
archivo1.txt  archivo8.txt         backup_datos.txt    informe.txt
archivo2.txt  archivo_a.txt        copia_archivo1.txt  notas.txt
archivo3.txt  archivo_b.txt        copia_archivo8.txt  nuevo_nombre.txt
archivo4.txt  archivo_c.txt        copia_prueba.txt    prueba.txt
archivo7.txt  archivo_externo.txt  info.txt

# Ejercicio 6

Crea un archivo vacío llamado archivo_existente.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_existente.txt

Crea un archivo vacío con el mismo nombre archivo_existente.txt dentro del directorio documento/.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch documento/archiv
o_existente.txt

Intenta mover archivo_existente.txt al directorio documento/.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv -i archivo_existente.txt documento/
mv: overwrite 'documento/archivo_existente.txt'? 

# Ejercicio 7

Crea un archivo vacío llamado archivo_viejo.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_viejo.txt

Escribe el texto "Contenido viejo" dentro de archivo_viejo.txt, reemplazando cualquier contenido anterior.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Contenido viejo" > archivo_viejo.txt

Copia archivo_viejo.txt al directorio documento/.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo_viejo.txt documento/

Sobrescribe archivo_viejo.txt en el directorio actual con el texto "Contenido nuevo".
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Contenido nuevo" > archivo_viejo.txt

Mueve archivo_viejo.txt a documento/ pero solo si el archivo de destino es más antiguo que el archivo que se mueve (-u = update). Esto actualiza el archivo en documento/ con la versión más reciente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv -u archivo_viejo.txt documento/

Muestra el contenido del archivo archivo_viejo.txt en pantalla
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cat documento/archivo_
viejo.txt
Contenido nuevo

# Desafio Final

Crea dos carpetas llamadas proyectos y documento. La opción -p permite crear directorios padres si no existen y evita errores si ya existen.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p proyectos documento

Crea tres archivos vacíos dentro de la carpeta proyecto: tarea1.txt, tarea2.txt y tarea3.txt.
comando: jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/tarea1.
txt proyecto/tarea2.txt proyecto/tarea3.txt

Muestra en pantalla el mensaje indicando que los archivos fueron creados.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Archivos creados en la carpeta 'proyectos'."
Archivos creados en la carpeta 'proyectos'.

Mueve el archivo tarea1.txt desde la carpeta proyecto a la carpeta documento.
Al mismo tiempo, renombra el archivo como proyecto1.txt.
comandos: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv proyecto/tarea1.txt
 documento/proyecto1.txt
Mueve tarea2.txt de proyecto a documento.
Lo renombra como proyecto2.txt.
@jhonlenis ➜ /workspaces/practica-terminal (main) $ mv proyecto/tarea2.txt
 documento/proyecto2.txt
Mueve tarea3.txt de proyecto a documento.
Lo renombra como proyecto3.txt.
@jhonlenis ➜ /workspaces/practica-terminal (main) $ mv proyecto/tarea3.txt
 documento/proyecto3.txt


Muestra un mensaje de confirmación.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Archivos movidos y renombrados con éxito."

Lista los archivos dentro de documento y filtra solo los que contienen la palabra proyecto, verificando que los archivos se movieron correctamente:
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "--- Verificación de la carpeta 'documento' ---"
ls documento | grep "proyecto"
--- Verificación de la carpeta 'documento' ---
proyecto1.txt
proyecto2.txt
proyecto3.txt

Verifica el contenido de la carpeta proyecto. Después del movimiento, la carpeta está vacía de esos archivos, aunque puede mostrar otras subcarpetas como documentos, imagenes, temp.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "--- Verificación de la carpeta 'proyecto' (debería estar vacía) ---"
ls proyecto
--- Verificación de la carpeta 'proyecto' (debería estar vacía) ---
documentos  imagenes  temp

# Laboratorio 1

Crea un archivo vacío llamado prueba.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

Renombra el archivo prueba.txt a archivo_renombrado.txt. El archivo sigue en el mismo directorio, solo cambia de nombre.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv prueba.txt archivo_renombrado.txt

Lista todos los archivos y carpetas del directorio actual para verificar que el archivo fue renombrado correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md               directorio_inexistente  nombres
apellidos               documento               proyecto
archivo_existente.txt   documentos              proyecto_final
archivo_grande          edad                    proyectos
archivo_renombrado.txt  fotos                   proyectos_copia
carpeta1                manual.pdf              script.sh
carpeta2                mi_directorio           videos
carpeta_nueva           mi_practica

# Laboratorio 2

Crea un nuevo directorio llamado temporal en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir temporal

Renombra el directorio temporal a archivos_temporales. mv puede mover archivos o carpetas, y si es en el mismo directorio, solo cambia el nombre.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv temporal archivos_temporales

Lista todos los archivos y carpetas del directorio actual, permitiendo verificar que el directorio fue renombrado correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md               carpeta_nueva           mi_practica
apellidos               directorio_inexistente  nombres
archivo_existente.txt   documento               proyecto
archivo_grande          documentos              proyecto_final
archivo_renombrado.txt  edad                    proyectos
archivos_temporales     fotos                   proyectos_copia
carpeta1                manual.pdf              script.sh
carpeta2                mi_directorio           videos

# Laboratorio 3

Crea un nuevo directorio llamado documentos2.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir documentos2

Crea un archivo vacío llamado informe.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch informe.txt

Mueve el archivo informe.txt dentro del directorio documentos2.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv informe.txt documentos2/

Lista los archivos dentro de la carpeta documentos2, confirmando que informe.txt fue movido correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documentos2/
informe.txt

# Laboratorio 4

Crea tres archivos vacíos llamados archivo1.txt, archivo2.txt y archivo3.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo1.txt archivo2.txt archivo3.txt

Crea un directorio llamado respaldos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir respaldos

Mueve todos los archivos que terminan en .txt al directorio respaldos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv *.txt respaldos/

Lista los archivos dentro de respaldos para confirmar que los .txt se movieron correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls respaldos/
archivo1.txt  archivo3.txt           archivo_renombrado.txt
archivo2.txt  archivo_existente.txt

# Laboratorio 5

Crea un archivo vacío llamado datos_originales.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch datos_originales.txt

Crea un directorio llamado backup para almacenar archivos de respaldo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir backup

Mueve el archivo datos_originales.txt al directorio backup y, al mismo tiempo, lo renombra como datos_backup.txt.
comando: jhonlenis ➜ /workspaces/practica-terminal (main) $ mv datos_originales.txt backup/datos_backup.txt

Lista los archivos dentro del directorio backup para confirmar que el archivo se movió y renombró correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls backup/
datos_backup.txt

# Laboratorio 6

Crea un archivo vacío llamado archivo_existente.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_existente.txt

Crea un directorio llamado documento3 para organizar archivos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir documento3

Crea un archivo vacío dentro del directorio documento3 con el mismo nombre archivo_existente.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch documento3/archi
vo_existente.txt

Mueve el archivo archivo_existente.txt al directorio documento3.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv -i archivo_existente.txt documento3/
mv: overwrite 'documento3/archivo_existente.txt'? y

Lista el contenido del directorio documento3 para verificar que archivo_existente.txt ahora está allí.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documento3/
archivo_existente.txt

# Laboratorio 7

Crea un archivo vacío llamado archivo_viejo.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_viejo.txt

Escribe el texto "Contenido viejo" dentro de archivo_viejo.txt, sobrescribiendo cualquier contenido previo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Contenido viejo" > archivo_viejo.txt

Crea un directorio llamado respaldo para almacenar copias de seguridad.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir respaldo

Copia el archivo archivo_viejo.txt al directorio respaldo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo_viejo.txt respaldo/

Sobrescribe el contenido de archivo_viejo.txt con "Contenido nuevo".
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Contenido nuevo" > archivo_viejo.txt

Mueve archivo_viejo.txt al directorio respaldo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv -u archivo_viejo.txt respaldo/

Muestra el contenido del archivo en respaldo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cat respaldo/archivo_viejo.txt
Contenido nuevo

# Laboratorio 8

Crea un archivo vacío llamado archivo_absoluto.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_absoluto.txt

Mueve el archivo archivo_absoluto.txt desde el directorio actual a la ruta absoluta /tmp/.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv archivo_absoluto.txt /tmp/

Lista todos los archivos y carpetas dentro del directorio /tmp/. Se confirma que archivo_absoluto.txt ahora está en /tmp/.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls /tmp/
archivo_absoluto.txt
codespaces_logs
dockerd.log
sshd.log
storage_version.txt
vscode-git-a2d2ddeea1.sock
vscode-ipc-878f001e-4c6c-4c3c-98f8-e8c69104ffc5.sock
vscode-ipc-dc51cefb-5fdb-447f-992f-11f2c3b8bf28.sock

# Laboratorio 9

Crea un archivo vacío llamado mi archivo.txt. Las comillas permiten que el nombre del archivo tenga espacios.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch "mi archivo.txt"

Crea un directorio llamado destino en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir destino

Mueve el archivo mi archivo.txt al directorio destino. Se usan comillas porque el nombre del archivo contiene un espacio.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mv "mi archivo.txt" destino/

Lista los archivos dentro del directorio destino. Se confirma que mi archivo.txt fue movido correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls destino/
'mi archivo.txt'

# Leccion 6: Ejercicio 1

Crea un archivo vacío llamado prueba.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

Lista el archivo prueba.txt en el directorio actual, confirmando que existe.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls prueba.txt
prueba.txt

Elimina (borra) el archivo prueba.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm prueba.txt

# Ejercicio 2

Crea un directorio llamado temporal.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir temporal

Elimina el directorio temporal solo si está vacío.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rmdir temporal

# Ejercicio 3

Crea un directorio llamado proyecto1.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyecto1

Crea dos archivos vacíos dentro del directorio proyecto1: archivo1 y archivo2.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto1/archiv
o1 proyecto1/archivo2

Lista de manera recursiva el contenido de proyecto1. Resultado: muestra que proyecto1 contiene archivo1 y archivo2.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -R proyecto1
proyecto1:
archivo1  archivo2

Elimina el directorio proyecto1 junto con todos sus archivos internos
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r proyecto1

# Desafio Final

Crea un directorio proyecto con tres subdirectorios src, docs y tests.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p proyecto/{src,docs,tests}

Crea archivos vacíos dentro de cada subdirectorio:
main.c en src
manual.txt en docs
test1.py en tests
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/src/main.c proyecto/docs/manual.txt proyecto/tests/test1.py

Elimina el directorio proyecto
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r proyecto

# Laboratorio 1

Crea un archivo vacío llamado archivo1.txt en el directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo1.txt

Lista los archivos y carpetas del directorio actual. Permite verificar que archivo1.txt se creó correctamente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  nombres
apellidos            documento               proyecto_final
archivo1.txt         documento3              proyectos
archivo_grande       documentos              proyectos_copia
archivos_temporales  documentos2             respaldo
backup               edad                    respaldos
carpeta1             fotos                   script.sh
carpeta2             manual.pdf              videos
carpeta_nueva        mi_directorio
destino              mi_practica

Elimina el archivo archivo1.txt permanentemente del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm archivo1.txt

Lista nuevamente los archivos y carpetas para confirmar que archivo1.txt ya no está.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 2

Crea tres archivos vacíos: archivoA.txt, archivoB.txt y archivoC.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivoA.txt archivoB.txt archivoC.txt

Elimina los tres archivos creados anteriormente de forma permanente.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm archivoA.txt archivoB.txt archivoC.txt

Lista los archivos y carpetas del directorio actual. Permite confirmar que archivoA.txt, archivoB.txt y archivoC.txt ya no están.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 3

Crea un archivo vacío llamado importante.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch importante.txt

ntenta eliminar importante.txt, pero con la opción -i pide confirmación antes de borrarlo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -i importante.txt
rm: remove regular empty file 'importante.txt'? y

# Laboratorio 4

Crea un directorio llamado vacío.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir vacío

Elimina el directorio vacío.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rmdir vacío

Lista el contenido del directorio actual.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 5

Crea un directorio llamado lleno. Similar a vacío, pero aquí luego se le añadirán archivos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir lleno

Crea dos archivos vacíos dentro del directorio lleno. Esto hace que el directorio ya no esté vacío.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch lleno/archivo1.txt lleno/archivo2.txt

Intenta eliminar el directorio lleno. Error: Directory not empty → no se puede eliminar porque contiene archivos.
comando:@jhonlenis ➜ /workspaces/practica-terminal (main) $ rmdir lleno
rmdir: failed to remove 'lleno': Directory not empty

# Laboratorio 6

Crea un directorio llamado proyecto.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyecto

Crea dos archivos vacíos dentro del directorio proyecto:
main.py → normalmente código principal de Python.
config.json → archivo de configuración.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/main.py proyecto/config.json

Elimina el directorio proyecto y todo su contenido.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r proyecto

Muestra el contenido actual del directorio. Observa que proyecto ya no aparece porque fue eliminado.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 7

Crea un directorio llamado datos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir datos

Crea dos archivos vacíos dentro del directorio datos:
registro.txt → normalmente para almacenar registros.
backup.log → archivo de log de respaldo.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch datos/registro.txt datos/backup.log

Elimina el directorio datos y todo su contenido de forma interactiva.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -ri datos
rm: descend into directory 'datos'? y
rm: remove regular empty file 'datos/registro.txt'? y
rm: remove regular empty file 'datos/backup.log'? y
rm: remove directory 'datos'? y

# Laboratorio 8

Crea un directorio llamado temp.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir temp

Crea dos archivos vacíos dentro de temp: file1.txt y file2.txt.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch temp/file1.txt temp/file2.txt

Borra el directorio temp y todo su contenido de manera forzada y recursiva.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -rf temp

Muestra el listado de archivos y carpetas en el directorio actual, confirmando que temp ya no existe.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 9

Crea un directorio llamado proyecto con subdirectorios src, docs y tests al mismo tiempo.
comando: jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p proyecto/{src,docs,tests}

Crea archivos vacíos en los subdirectorios correspondientes
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/src/main.c proyecto/docs/manual.txt proyecto/tests/test1.py

Elimina el directorio proyecto y todo su contenido de manera recursiva.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r proyecto

Lista los archivos y carpetas del directorio actual, confirmando que proyecto ya no existe.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            directorio_inexistente  mi_practica
apellidos            documento               nombres
archivo_grande       documento3              proyecto_final
archivos_temporales  documentos              proyectos
backup               documentos2             proyectos_copia
carpeta1             edad                    respaldo
carpeta2             fotos                   respaldos
carpeta_nueva        manual.pdf              script.sh
destino              mi_directorio           videos

# Laboratorio 10

Crea un directorio llamado trabajo con tres subcarpetas: informes, temporal y archivos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p trabajo/{informes,temporal,archivos}

Crea archivos vacíos en cada subdirectorio:
reporte1.doc en informes
notas.txt en temporal
datos.csv en archivos
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch trabajo/informes/reporte1.doc trabajo/temporal/notas.txt trabajo/archivos/datos.csv

Elimina recursivamente el directorio temporal y su contenido.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r trabajo/temporal

Elimina todo el directorio trabajo incluyendo los subdirectorios informes y archivos y sus archivos.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ rm -r trabajo 

Lista los archivos y directorios del directorio actual para confirmar que trabajo ya no existe.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md            carpeta_nueva           edad            proyectos
apellidos            destino                 fotos           proyectos_copia
archivo_grande       directorio_inexistente  manual.pdf      respaldo
archivos_temporales  documento               mi_directorio   respaldos
backup               documento3              mi_practica     script.sh
carpeta1             documentos              nombres         videos
carpeta2             documentos2             proyecto_final
