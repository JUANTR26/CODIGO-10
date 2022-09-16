# primer dia con Git/Github

Lista de comandos de Git

* Para poder ver la version de git

```bash
git --version
```

* Para configurar el correo 

```bash
git config --global user.email "email"
```

* Para poder configurar el usarname

```bash
git config --global usar.name "usarname"
```

* Sirve para poder empezar a usar el control de version (git) en nuestra carpeta.

 * Esto se usa solo una vez por carpeta

 ```bash
 git init
 ```

* Para ver el estado de nuestros cambios
 ```bash
 git status
```

* Agrega los archivos a la memoria de la pc
```bash 
git add
```

* Crear el registro de los cambios realizados 
```bash
git commit -m "comentario"
```
* Para poder ver el historial de commits 
 
 [ ] Git log retorna un `id` con este id vamos a poder ver el detalle de los cambios que se hicieron en el commit

```bash
git log
```

* Para poder ver el detalle del commit usamos 

```bash
git show id-de-commit


