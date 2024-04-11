## GUÍA CONCEPTOS BÁSICOS DE JAVASCRIPT


A continuación estaremos desarrollando el paso a paso para conectar mi repositorio local, es decir, el código del computador, con mi repositorio remoto (Mi biblioteca en Github)


1. Crear el repositorio en GitHub (remoto)
    * buscamos el botón verde con icono de libro que dice nuevo
    * llenamos el nombre del repositorio descripción (si quieren) y lo ponemos público

2. Crear nuestro repositorio local


    * abrimos la consola de gitbash desde visual:
        1. Ctrl + ñ
        2. ... -> Terminal -> nuevo terminal

    * Vamos a escribir los comandos para inicializar nuestro repositorio local y conectarlo con el remoto
        - COMANDOS: (Deben ir en orden)
        1. git init -> Inicializar mi repositorio local
        1.1 git status -> me muestra el estado de mis archivos
        2. git add  -> Se usa para agregar cambios al entorno de preparación
        3. git add . -> Se usa para agregar todos los archivos (html, java y README)
        4. git commit -m -> nos permite poner un mensaje, pero además significa que sus archivos estan listos para enviarse al repositorio remoto
        5. (Se usa solo la primera vez los tres)
            git branch -M main -> Establecer la rama del main
           git remote add origin https://github.com/yeisonaguzman/actividadClase.git -> conecta al repositorio en internet, al remoto
           git push -u origin main -> Sube todo a internet

## QUE PONER EN EL README PARA MI PROYECTO FINAL

1. Titulo del proyecto -> página web
2. Descripción general -> parrafo que le hable de todo el proyecto
3. Autor -> quién lo hizo - Mi nombre


En la carpeta script van todos los archivos de JS pero destinados a darle dinamismo al sitio web
NODE JS se utiliza para poder implementar el JS en nuestro backend
no se relacionan con la funcionalidad del sitio