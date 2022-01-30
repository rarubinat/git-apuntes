# git-apuntes
Funcionamiento de git desde consola gitbash.

## 1. Bajar programa desde git-scm.com/downloads
## 2. Configuración inicial
```
$ git version
$ git config --global user.name "nombre"
$ git config --global user.email "tuemail"
$ git config --list
````
## 3. Iniciar proyecto
```
$ git init 
```
## 4. Detalles folders
```
$ git status
```
## 5. Commit
```
$ git add "nombre archivo y extensión"
$ git commit -m "Mensaje correspondiente al commit"
```
## 6. Add all files
```
$ git status
$ git add --all
```
## 7. Git remote
```
$ git log
$ git remote add origin https://github.com/rarubinat/carpeta.git
git branch -M main
git push -u origin main
```
Github nos pedirá las credenciales de inicio se sesión, y ya tendremos connectado git local con git remote. Debes autorizar el funcionamiento del manager.
## 8. Git clone
```
Página > Repositorio > Clone > url
$git clone https://github.com/rarubinat/carpeta.git
```
## 9. Movimiento
```
$ cd
```
## 10. Delete
```
$ git push origin --delete nuevo-feature
```
