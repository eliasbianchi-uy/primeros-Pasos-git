# Primeros pasos Git

Explicando funcionamiento de Git.
Paso 1 configurar usuario de Git:

```sh
git config --global user.name <nombre>
git config --global user.email <correo>
```

Ver las configuraciones 

```sh
git config list
```

Salir del config list sin cerrar la consola es aprentando "q".

Resetear a un commit anterior
Copiando el id del commit y ejecutando
 
```sh
git reset --hard <identificador>
```

Enlazar con un repositorio en Github

```sh
git remote add origin <url>
```

para verlo

```sh
git remote -v
```

Sincronizar repositorios

```sh
git push -u origin main
```

Despúes de ejecutarlo por primera vez simplemente ejecutar

```sh
git push
```

para borrar enlace al repositorio remoto

```sh
git remote remove origin
```