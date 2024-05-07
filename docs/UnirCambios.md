# Unir cambio en git
1. Hacer checkout de la rama a la que vamos a traer los cambios
```bash
git checkout <nombre_de_la_rama>
```
**Ejemplo**:
```bash
git checkout master
```

2. Hacer merge de la rama a la que vamos a traer los cambios
```bash
git merge <nombre_de_la_rama_de_la_que_vamos_a_traer_los_cambios>
```
**Ejemplo**:
```bash
git merge develop
```

**Nota**: usted puede hacer `git checkout <SU-RAMA>` y crear un archivo, pero mientras usted no lo agregue al `stage` y despúes le haga `commit` esos cambios no van a quedar en esa rama. Eso significa que si no hacemos lo anterior usted posterior a eso puede hacer `git checkout <OTRA-RAMA>` y en esta si los agrega  `stage` y despúes hace `commit` a pesar de que los cambios se hayan hecho en la otra rama, esto van a quedar en la rama actual (`<OTRA-RAMA>`).