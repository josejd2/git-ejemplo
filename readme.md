# Explicación de git
La primera vez que utilizamos git en una máquina debemos configurar el user y el email y comprobarlo.
````shell
git config --global user.name 'nombreusuario' => (si hay espacios hay que poner comillas).
git config --global user.email 'direccion de correo'
````
Para comprobar configuración.
`````shell
git config --list  
`````
Para iniciar el repositorio por primera vez
`````shell
git init  
`````
Para hacer que git controle solo un archivo
`````shell
git add .
git <nombrearchivo>
`````
Para saber el estado de git 
`````shell
git status  
`````
Para confirmar el commit
`````shell
git commit -m 'nombrecommit' 
`````
Para ver los commits que tenemos
`````shell
git log
git log --graph 
`````
Para listar las ramas
`````shell
git branch 
`````
Para crear una rama
`````shell
git branch <nombredelarama>
`````
Para cambiar de rama
`````shell
git checkout <nombredelarama>
`````
Para fusionar lo que tengas a rama master
`````shell
git merge <nombredelarama>
`````