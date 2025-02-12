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
git add readme.md
`````
Para saber el estado de git 
`````shell
git status  
`````
Para confirmar el commit
`````shell
git commit -m 'nombrecommit' 
`````
