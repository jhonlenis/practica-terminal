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

