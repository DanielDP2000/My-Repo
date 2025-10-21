# My-Repo
Hice un git clone git@github.com:DanielDP2000/My-Repo.git
hago un commit inicial con el comando git add . y git commit -m "commit inicial"
push inicial hago un git push origin main
Pregunta: No es necesario especificar el remoto ni la rama por que Git ya conoce el remoto y la rama del clon original que en este caso es origin main, es decir, se podria utilizar simplemente el comando "git push"
Ignorar archivos: hago un touch privado.txt para crear un fichero en el repositorio local llamado privado.txt, luego creo una carpeta llamada privada en el mismo repo local, luego hago que los dos archivos sean ignorados por git utilizando estos dos comandos, echo "privado.txt" >> .gitignore, echo "/privada" >> .gitignore y por ultimo hago un git add. y git commit -m 
Pregunta: No, el fichero .gitignore indica a Git que no tiene que rastrear ni subir esos archivos o carpetas al repositorio remoto.

