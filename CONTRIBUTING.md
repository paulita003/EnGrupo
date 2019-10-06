# Como contribuir
## Creamos y nos movemos a una nueva rama

```
git checkout -b UH3-T4
```

## Añadimos o editamos ficheros
code / eclipse ...
```
git status

git add .

git commit  //  i   esc   wq

git log --oneline
```

## Mandamos los cambios al repositorio remoto

```
git push origin UH3-T4
```

## ir al repositorio  y ver las ramas y el commit en la rama

code --> branch

Lanzar el pull request pulsando en New pull request

No le des a merge (será el adminisrador quien lo merguee)



## El administrador mergeará el pullrequest

Podrás ver en tu rama que su estado ha pasado de open a merge




## Nos traemos los cambios a nuestro repositrio master


```
git checkout master

git pull origin master

git log --oneline
```



## Borramos la rama


```
git branch

git branch -d UH3-T4

git push origin --delete UH3-T4

git log --oneline    // historial limpio
```

