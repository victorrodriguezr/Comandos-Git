# Guardar archivos temporales en una rama especifica

1. Guardar el estado de sus archivos temporales en la rama actual.
```bash
git stash save "Su mensajes"
```
Ejemplo:
```bash
git stash save "Guardar cambios rama develop"
```

2. Listar la cantidad stah guardados
```bash
git stash list
```

Output:
```bash
stash@{0}: On develop: Guardar cambios rama develop
```
3. Recuperar cambios
    3.1. Recuperar el estado de los archivos temporales y deja una copia en el `stash`
    ```bash
    git stash app <NOMBRE_DEL_STASH>
    ```

    Ejemplo:
    ```bash
    git stash apply stash@{0}
    ```

    3.2. Recupera los estados de los archivos temporales y elimina el estado del `stash`
    ```bash
    git stash pop <NOMBRE_DEl_STAH>
    ```

    Ejemplo:
    ```bash
    git stash pop stash@{0}
    ```

