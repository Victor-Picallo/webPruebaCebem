# GIT
## Convertir tu proyecto en tu proyecto controlado por git
**git**
``` 
init
```

## Configurar git *correctamente*
```
git config --global user.mail "victor.p9646@gmail.com"
git config --global user.name "Victor-Picallo"
```

## Prepara los cambios para ser añadidos al repositorio
```
git add xxx (xxx = al archivo que te quieras) . (. = TODO)
```

## Guarda los cambios en el repositorio
```
git commit -m "creo la pagina web inicial"
```

## Conecta el repositorio local con el repositorio remoto
```
git remote add origin https://github.com/Victor-Picallo/webPrueba.git
```

## Sube los cambios que tienes en locak a el repositorio remoto
```
git push -u origin master
```