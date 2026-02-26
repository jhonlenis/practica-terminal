# practica-terminal

# Leccion 1: Ejercicio Practico

Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyecto_final

Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd proyecto_final/

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir codigo documentacion recursos

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch codigo/main.py codigo/config.json

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch documentacion/README.md

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ tree proyecto_final
proyecto_final/
├── codigo
│   ├── main.py
│   └── config.json
├── documentacion
│   └── README.md
└── recursos

# Laboratorio 1

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch prueba.txt

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
codigo  documentacion  prueba.txt  recursos

# Laboratorio 2

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch archivo1.txt archivo2.txt archivo3.txt

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  recursos
archivo2.txt  codigo        prueba.txt

# Laboratorio 3

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch prueba.txt

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

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir documentos

Comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  prueba.txt
archivo2.txt  codigo        documentos     recursos

# Laboratoria 5

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir fotos videos música

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls
archivo1.txt  archivo3.txt  documentacion  fotos   prueba.txt  videos
archivo2.txt  codigo        documentos     música  recursos

# Laboratorio 6

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir -p proyecto/src/main

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ tree proyecto
proyecto
└── src
    └── main

3 directories, 0 files

- Laboratorio 7

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir trabajo

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch trabajo/informe.txt trabajo/notas.md

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ ls trabajo
informe.txt  notas.md

# Laboratorio 8

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir -p biblioteca/{libros,revistas,artículos}

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ touch biblioteca/libros/novela.txt biblioteca/revistas/ciencia.md

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ tree biblioteca
biblioteca
├── artículos
├── libros
│   └── novela.txt
└── revistas
    └── ciencia.md

4 directories, 2 files

# Laboratorio 9

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ mkdir mi_proyecto

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final (main) $ cd mi_proyecto

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ mkdir codigo documentacion recursos

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ touch codigo/main.py codigo/config.json

comando: @jhonlenis ➜ /workspaces/practica-terminal/proyecto_final/mi_proyecto (main) $ touch documentacion/README.md

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

Comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd /var/log

comando: @jhonlenis ➜ /var/log $ cd ..

comando: @jhonlenis ➜ /var $ cd -
/var/log

comando: @jhonlenis ➜ /var/log $ cd ~

comando: @jhonlenis ➜ ~ $ pwd
/home/codespace

# Laboratorios de Aprendizaje: Laboratorio 1

comando: @jhonlenis ➜ ~ $ pwd
/home/codespace

¿Qué significa la ruta mostrada?
R/ es tu Directorio de Trabajo Actual

Tarea: Copia la ruta mostrada y explica qué representa cada parte.
R/  home/ Es el directorio de usuario 
codespace / Nombre de usuario 

# Laboratorio 2

comando: @jhonlenis ➜ ~ $ cd /

comando: @jhonlenis ➜ / $ pwd
/

Tarea: Enumera los directorios principales que ves al ejecutar ls.
R/ tmp/ workspaces

# Laboratorio 3

comando: @jhonlenis ➜ / $ cd /home
@jhonlenis ➜ /home $ 

comando: @jhonlenis ➜ /home $ pwd
/home

Tarea: Intenta cambiar al directorio de tu usuario (por ejemplo, /home/tu_usuario).
R/ @jhonlenis ➜ /home $ cd codespace/
@jhonlenis ➜ ~ $ 

# Laboratorio 4

Tarea: Sin usar /, cambia al directorio Documentos dentro de tu directorio personal.
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd documentos

# Laboratorio 5 

Comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd /tmp
@jhonlenis ➜ /tmp $ 

comando: @jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $

Tarea: Repite este proceso varias veces y observa cómo funciona cd -.
R/ @jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd -
/tmp
@jhonlenis ➜ /tmp $ cd -
/workspaces/practica-terminal/documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ 

# Laboratorio 6

comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ cd ~
@jhonlenis ➜ ~ $ 

Tarea: Crea un archivo llamado prueba.txt en tu directorio personal.
R/ @jhonlenis ➜ ~ $ pwd
/home/codespace
@jhonlenis ➜ ~ $ touch prueba.txt
@jhonlenis ➜ ~ $ ls
java  nvm  prueba.txt

# Laboratorio 7 

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd ..
@jhonlenis ➜ /workspaces $ 

Tarea: Sube dos niveles consecutivos y verifica tu ubicación con pwd.
R/@jhonlenis ➜ /workspaces $ cd ../..
@jhonlenis ➜ / $ pwd
/
@jhonlenis ➜ / $ 

# Laboratorio 8

comando: @jhonlenis ➜ / $ cd /home
@jhonlenis ➜ /home $ 

comando: @jhonlenis ➜ /home $ cd codespace
@jhonlenis ➜ ~ $ 

comando: @jhonlenis ➜ ~ $ mkdir Descargas
@jhonlenis ➜ ~ $ 

comando: @jhonlenis ➜ /home $ cd codespace/Descargas
@jhonlenis ➜ ~/Descargas $ 

Tarea: Explica la diferencia entre rutas relativas y absolutas.
R/ Las rutas absolutas son direcciones completas que parten desde la raíz del sistema (/), funcionando de forma independiente a tu ubicación actual. Por el contrario, las rutas relativas definen un camino basado exclusivamente en el directorio donde te encuentras en ese momento, sin usar la barra inicial. Mientras la absoluta es como una coordenada GPS invariable, la relativa es una instrucción de dirección que cambia según tu punto de partida.

# Laboratorio 9

comando: r directory
@jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir ~/pruebas

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd ~/pruebas
@jhonlenis ➜ ~/pruebas $ 

comando: @jhonlenis ➜ ~/pruebas $ mkdir nivel1

comando: @jhonlenis ➜ ~/pruebas $ cd nivel1
@jhonlenis ➜ ~/pruebas/nivel1 $ 

# Laboratorio 10

comando: @jhonlenis ➜ ~ $ cd /home/codespace
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

comando: @jhonlenis ➜ ~ $ cd .config
@jhonlenis ➜ ~/.config $ 

comando: @jhonlenis ➜ ~/.config $ pwd
/home/codespace/.config
@jhonlenis ➜ ~/.config $ 

# Leccion 4: Ejercicio 1

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  proyecto_final

# Ejercicio 2

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.   .git       documentos
..  README.md  proyecto_final
@jhonlenis ➜ /workspaces/practica-t

# Ejercicio 3

comando:  $ ls -l
total 20
-rw-rw-rw-   1 codespace root      9190 Feb 26 02:22 README.md
drwxrwxrwx+  2 codespace codespace 4096 Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace 4096 Feb 25 01:33 proyecto_final

Responde: ¿Qué significa el primer carácter d en algunos elementos?
R/ El primer carácter d significa Directory (Directorio).

Indica que ese elemento no es un archivo de datos (como un texto o una imagen), sino una carpeta que contiene otros archivos o subdirectorios. En tu lista, documentos y proyecto_final son carpetas porque empiezan con d.

# Ejercicio 4

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lah
total 32K
drwxrwxrwx+  5 codespace root      4.0K Feb 25 02:09 .
drwxr-xrwx+  5 codespace root      4.0K Feb 25 01:05 ..
drwxrwxrwx+  8 codespace root      4.0K Feb 25 17:22 .git
-rw-rw-rw-   1 codespace root      9.6K Feb 26 02:24 README.md
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final

# Ejercicio 5

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir mi_practica

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd mi_practica
@jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ 

comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ touch archivo1.txt archivo2.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ mkdir carpeta1 carpeta2

comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ ls -lah
total 16K
drwxrwxrwx+ 4 codespace codespace 4.0K Feb 26 02:26 .
drwxrwxrwx+ 6 codespace root      4.0K Feb 26 02:25 ..
-rw-rw-rw-  1 codespace codespace    0 Feb 26 02:25 archivo1.txt
-rw-rw-rw-  1 codespace codespace    0 Feb 26 02:25 archivo2.txt
drwxrwxrwx+ 2 codespace codespace 4.0K Feb 26 02:26 carpeta1
drwxrwxrwx+ 2 codespace codespace 4.0K Feb 26 02:26 carpeta2

comando: @jhonlenis ➜ /workspaces/practica-terminal/mi_practica (main) $ ls -R
.:
archivo1.txt  archivo2.txt  carpeta1  carpeta2

./carpeta1:

./carpeta2:

# Laboratios de Aprendizajes: Laboratorio 1

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  mi_practica  proyecto_final

¿Qué sucede si ejecutas ls en un directorio vacío?
R/No va a salir nada porque si estas en una carpeta en la linea de comandos cuando ejecutas ls te va a salir vacio

# Laboratorio 2

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.  ..  .git  README.md  documentos  mi_practica  proyecto_final

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch .mi_archivo_secreto

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -a
.   .git                 README.md   mi_practica
..  .mi_archivo_secreto  documentos  proyecto_final

¿Por qué crees que algunos archivos están ocultos por defecto?
R/ Los archivos se ocultan principalmente para evitar el desorden visual, manteniendo la carpeta personal limpia de archivos de configuración técnica.

# Laboratorio 3

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l
total 24
-rw-rw-rw-   1 codespace root      12272 Feb 26 02:34 README.md
drwxrwxrwx+  2 codespace codespace  4096 Feb 25 02:09 documentos
drwxrwxrwx+  4 codespace codespace  4096 Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace  4096 Feb 25 01:33 proyecto_final

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md  documentos  mi_practica  proyecto_final  prueba.txt

¿Qué permisos tiene el archivo?
R/ el archivo tendrá permisos rw-rw-rw- (lectura y escritura para todos) o rw-r--r-- (lectura/escritura para ti y solo lectura para el resto).
¿Quién es el propietario?
R/ El propietario es codespace.

# Laboratorio 4

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -lh
total 28K
-rw-rw-rw-   1 codespace root       13K Feb 26 02:38 README.md
drwxrwxrwx+  2 codespace codespace 4.0K Feb 25 02:09 documentos
drwxrwxrwx+  4 codespace codespace 4.0K Feb 26 02:26 mi_practica
drwxrwxrwx+ 13 codespace codespace 4.0K Feb 25 01:33 proyecto_final
-rw-rw-rw-   1 codespace codespace    0 Feb 26 02:35 prueba.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ dd if=/dev/zero of=archivo_grande bs=1M count=10
10+0 records in
10+0 records out
10485760 bytes (10 MB, 10 MiB) copied, 0.0100094 s, 1.0 GB/s

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p mi_directorio/subdirectorio1/subdirectorio2

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch mi_directorio/archivo1.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch mi_directorio/subdirectorio1/archivo2.txt

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyectos .secretos
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch notas.txt manual.pdf
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch .config_personal .password_backup
@jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Hola Mundo" > info.txt

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -d */
documentos/  mi_directorio/  mi_practica/  proyecto_final/  proyectos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir nombres apellidos edad
@jhonlenis ➜ /workspaces/practica-terminal (main) $ touch notas.txt manual.pdf script.sh

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -d */
apellidos/   edad/   mi_directorio/  nombres/         proyectos/
documentos/  fotos/  mi_practica/    proyecto_final/  videos/

# Laboratorio 9

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p proyecto/{documentos,imagenes,temp}

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/documentos/reporte.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/imagenes/foto.jpg

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/temp/archivo_temporal

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyecto/.configuracion

¿Qué opción usarías para encontrar rápidamente un archivo oculto importante?
R/ La opción ideal sería ls -la (o ls -lah para ver el tamaño).

# Leccion 4
