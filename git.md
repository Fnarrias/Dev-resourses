## Git

#Comandos Básicos
- [ Iniciar carpeta del repo]
```
git init 
```
- [ Añadir archivos con cambios]
```
git add . 

```
- [ Añadir archivos con cambios]
```
git commit -m "<texto descripción del commit>" 
```
- [ Añadir la url del repo a origin]
``` 
git remote add <URL de tu proyecto> 
```
- [ Cambiar la url de origin]
``` 
git remote set-url origin new.git.url/here 
```
- [ Setear la rama a main]
```
git branch -M main 
```
- [Realizar el push ]
```
git push -u origin main
```
#Casos especiales -Comandos Básicos
- [Push a una rama específica (remote sería origin en este caso)]
```
git push <remote> <branch>
```
- [En caso del primer push, si tiene conflictos puedes forzar el comando]
```
git push --force <remote> <branch>
```

- [Pull una rama específica (remote sería origin en este caso)]
```
git pull <remote> <branch>
```
- [si el pull no actualiza los archivos]
```
 git fetch --all
 git reset --hard origin/master
```

