# My-Repo
Hice un git clone git@github.com:DanielDP2000/My-Repo.git

Hago un commit inicial con el comando git add . y git commit -m "commit inicial"

Push inicial hago un git push origin main
Pregunta: No es necesario especificar el remoto ni la rama por que Git ya conoce el remoto y la rama del clon original que en este caso es origin main, es decir, se podria utilizar simplemente el comando "git push"

Ignorar archivos: hago un touch privado.txt para crear un fichero en el repositorio local llamado privado.txt, luego creo una carpeta llamada privada en el mismo repo local, luego hago que los dos archivos sean ignorados por git utilizando estos dos comandos, echo "privado.txt" >> .gitignore, echo "/privada" >> .gitignore y por ultimo hago un git add. y git commit -m 
Pregunta: No, el fichero .gitignore indica a Git que no tiene que rastrear ni subir esos archivos o carpetas al repositorio remoto.

Añadir un nuevo fichero: añado un nuevo fichero con touch 1.txt y hago git add . y git commit
Pregunta: el git add . añade cambios con área de preparación y el git commit guarda una instantanea permanente de esos cambios en el repo local.

Crear un tag: se crea un tag con git tag v0.1
Subir el tag: Se suben ñps cambios al repo remoto con git push --tag origin main
Pregunta: Un tag es una etiqueta que apunta a un commit espesifico, normalmente usado para marcar versiones estables o lanzamientos.

Crear una rama y cambiarse a ella: Se crea una rama con git branch v0.2 y se cambia a ella con git checkout v0.2

Añadir un nuevo fichero en la rama: se añade un fichero con touch 2.txt y hago un git add ., git commit y por ultimo git push origin v0.2
Pregunta: Las ramas permiten trabajar en desarrollos paralelos sin afectar la rama principal

