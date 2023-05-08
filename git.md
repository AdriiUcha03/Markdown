# COMANDO BÁSICOS DE GIT

### GIT INIT

> git init

```Crea el area de guardado de los archivos temporales, y el repositorio local.```

### GIT STATUS

```Nos muestra en qué estado se encuentras los ficheros que vamos modificando, hay cuatro estados.```

>1. Untracked: archivo sin rastrear(aún no vive en git).
>2. Unstaged: archivo ha sido modificado pero no agregado a git.
>3. Staged: El archivo aún no es guardado solo añadido (git add).
>4. Tracked Se ha realizado el commit y ya esta en el repositorio con los cambios definitivos.

### RESET HEAD

> reset head

```Nos resetea la cabecera del branch que estamos modificando o el ultimo modificado, por si hemos cometido un error, poder volver atrás(siempre que esten en staged).```

### GIT BRANCH

> git branch nueva_rama

```Con branch podemos crear ramas: si añadimos -M cambiar el nombre de la rama o si usamos git branch vemos las ramas y en las que nos encontramos.```

### GIT CHECKOUT

> git checkout rama

```Con el checkout podemos cambiar entre ramas para poder ir haciendo diferente modificaciones en versiones y ramas diferentes para realizar pruebas y hacer cambios.```

### GIT RESET

> git reset

```Podemos vover a versiones anteriores borrando todos los cambios que hicimos despues del commit.```

# GIT CON REPOSITORIOS REMOTOS

### GIT ADD REMOTE URL

> git add remote URL

```Con el siguiente comando agregamos un repositorio remoto al local.```

### ACCEDER A PROYECTO REMOTO PARA ACTULIZAR EL LOCAL

> git clone URL

### GIT PUSH

> git push [donde hacemos el push] [lo que pusheamos]

```Subimos las modificaciones al repositorio remoto.```

### GIT FETCH

> git fetch [repositorio del que leemos] [donde actualizamos]

```Con fetch actualizamos el repositorio sin aplicar ni machacar cambios.```

### GIT PULL

> git pull [sitio remoto] [branch local a subir]

```Actualizamos y sobreescribimos los cambios de forma directa en el repositorio local(es como hacer fetch y merge).```

### GIT CLEAN 

> git clean

```Sirve para limpiear archivos basura```



