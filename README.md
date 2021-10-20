# unidad-4-ejercicio-1

1. Clona en tu máquina, con el comando `git clone`, el repositorio que hay 
aquí en **GitHub** 
[https://github.com/trainingIT-GIT/unidad-4-ejercicio-1](https://github.com/trainingIT-GIT/unidad-4-ejercicio-1)
o si lo prefieres en **BitBucket**
[https://bitbucket.org/curso-git-avanzado/unidad-4-ejercicio-1/src/master/](https://bitbucket.org/curso-git-avanzado/unidad-4-ejercicio-1/src/master/)

>Ambos servidores te permiten clonar y acceder a la URL real de _git_:
>- En bitBucket es recomendable copiar la URL asegurándote antes de que estás logueado con tu cuenta. Puedes comprobarlo viendo si en la URL del repositorio aparece tu nombre de usuario.
>- El comando `git clone` te creará una subcarpeta, a menos que añadas un punto; recuerda entrar en ella para empezar a trabajar.

2. De cara a empezar tú un repositorio desde cero, borra la carpeta `.git` para desvincular de este repositorio al proyecto.
3. Inicializa un repositorio local. 
4. Añade al _stage_ los archivos de los directorios 1 y 2.
5. Comprueba con `git status` que el stage tiene lo que quieres.
6. Crea un _commit_ con esos dos archivos.
7. Realiza una modificación en el texto del archivo `1/1.txt` y otra en el texto del archivo `2/2.txt`.
8. Añade al _stage_ únicamente las modificaciones del archivo `2/2.txt`.
9. Haz `git status` e interpreta la información que te da.
10. Crea un _commit_ con las modificaciones que has hecho en el archivo `2/2.txt` y con el archivo `3/3.txt`.
11. Haz `git status` y comprueba que el stage está vacío y que en el working directory está el cambio del archivo `1/1.txt`.
12. Desversiona el archivo `1/1.txt` (es decir, dile a _Git_ que deje de trackearlo), pero sin eliminarlo. 
13. Elimina el archivo `2/2.txt`.
14. Haz `git status` y comprueba que la eliminación de los dos archivos está en el _stage_.
15. Crea un _commit_ que almacene la eliminación de esos dos últimos archivos.
16. Haz `git status` y comprueba que todo está como esperas (el archivo `1/1.txt` está sin versionar y el _stage_ está sin cambios).
17. Configura el repositorio para que ignore la carpeta `1`.
18. Haz `git status` y comprueba la diferencia
