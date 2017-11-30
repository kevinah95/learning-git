# FAQ

## ¿Qué pasa si quiero trabajar en la misma funcionalidad de mi compañero de trabajo?

### Sugerencia

Se debe de trabajar sobre el mismo branch creado inicialmente, donde la rama remota es la que debe de actualizarse.

### Recreación

```bash
kevin(master)> git checkout -b lc-auth
Switched to a new branch 'lc-auth'
kevin(lc-auth)> # kevin is working on this feature locally
```
```bash
leo(master)> git pull origin master
leo(master)> 
```


Notas:

- Si se hace un pull request y a través de la consola se realizó una fusión de las ramas, el pull request se cierra o mejor dicho cambia de estado a 'MERGED'
