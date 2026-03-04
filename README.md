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

# Leccion 3: Ejercicio 1

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

# Leccion 4: Ejercicio 1

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch prueba.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp prueba.txt copia_prueba.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls
README.md         documentos  manual.pdf     notas.txt       prueba.txt
apellidos         edad        mi_directorio  proyecto        script.sh
archivo_grande    fotos       mi_practica    proyecto_final  videos
copia_prueba.txt  info.txt    nombres        proyectos
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

# Ejercicio 2

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir carpeta1

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch carpeta1/archivo1.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -r carpeta1 carpeta2

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -fv carpeta1/archivo1.txt carpeta2/
'carpeta1/archivo1.txt' -> 'carpeta2/archivo1.txt'

# Laboratio 1

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo1.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt copia_archivo1.txt

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

comando:  mkdir documentos
mkdir: cannot create directory ‘documentos’: File exists

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt documentos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cd documentos
@jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ 

comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ ls
archivo1.txt

¿Qué sucede si el directorio de destino no existe?
R/ Si intentas copiar un archivo a un directorio que no existe, el sistema mostrará un error y la copia no se realizará.
¿Cómo puedes copiar un archivo a un directorio fuera del directorio actual?
R/ Debes indicar la ruta del directorio destino. Puedes usar como ejemplo cp archivo.txt ../carpeta_destino/

# Laboratorio 3

comando: @jhonlenis ➜ /workspaces/practica-terminal/documentos (main) $ touch archivo2.txt archivo3.txt archivo4.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo2.txt archivo3.txt archivo4.txt documentos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documentos/
archivo1.txt  archivo2.txt  archivo3.txt  archivo4.txt

¿Qué sucede si uno de los archivos no existe?
R/ Si intentas copiar un archivo que no existe, el sistema mostrará un mensaje de error indicando que no se encontró el archivo, y la copia no se realizará.
¿Cómo puedes copiar todos los archivos .txt de un directorio?
R/ Se utiliza el comodín * para seleccionar varios archivos. Esto copia todos los archivos con extensión .txt del directorio actual al directorio destino.

# Laboratorio 4

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir proyectos
mkdir: cannot create directory ‘proyectos’: File exists

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch proyectos/archivo5.txt proyectos/archivo6.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -r proyectos proyectos_copia

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo7.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo7.txt documentos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -f archivo7.txt documentos/

¿Qué sucede si no usas la opción -f?
R/ La opción -f (force) en el comando cp se usa para forzar la copia, sobrescribiendo archivos sin pedir confirmación y sin mostrar ciertos errores.
¿Cómo puedes evitar que se sobrescriba un archivo existente?
R/ Puedes usar la opción -i (interactive), que pide confirmación antes de sobrescribir

# Laboratorio 6

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

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo8.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch -d "2022-01-01" archivo8.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp -p archivo8.txt copia_archivo8.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls -l archivo8.txt copia_archivo8.txt
-rw-rw-rw- 1 codespace codespace 0 Jan  1  2022 archivo8.txt
-rw-rw-rw- 1 codespace codespace 0 Jan  1  2022 copia_archivo8.txt

¿Qué atributos se preservan con la opción -p?
R/ La opción -p (preserve) en el comando cp permite conservar los atributos originales del archivo al copiarlo.
¿Qué sucede si no usas la opción -p?
R/ Si no usas -p:

El archivo copiado puede tener permisos diferentes, según la configuración por defecto del sistema (umask).

# Laboratorio 8

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ touch archivo_a.txt archivo_b.txt archivo_c.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo_*.txt documentos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ ls documentos/
archivo1.txt  archivo3.txt  archivo7.txt   archivo_b.txt
archivo2.txt  archivo4.txt  archivo_a.txt  archivo_c.txt

¿Qué otros patrones puedes usar para seleccionar archivos?
R/ * → Cualquier cantidad de caracteres, ? → Un solo carácter, [ ] → Rango o conjunto de caracteres y [! ] → Excluir caracteres
¿Cómo puedes copiar archivos que terminen con un patrón específico?
R/ Si quieres copiar archivos que terminen con algo específico, usas * antes del patrón.

# Laboratorio 9

comando:@jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir -p /tmp/simulacion_usb

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ echo "Este es un archivo del USB" > /tmp/simulacion_usb/archivo_externo.txt

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp /tmp/simulacion_usb/archivo_externo.txt .

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
comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo2.txt documentos/

comando: @jhonlenis ➜ /workspaces/practica-terminal (main) $ mkdir directorio_inexistente

comando: stente
@jhonlenis ➜ /workspaces/practica-terminal (main) $ cp archivo1.txt directorio_inexistente/
@jhonlenis ➜ /workspaces/practica-terminal (main) $ 

# Leccion 5

