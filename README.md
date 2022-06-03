# Comandos básicos git

**Nota**: los simbolos mayor que **(>)** y menor que **(<)** son para colocar nuestro comando en la terminal.
## **Configurar git**
- **Configurar el nombre de usuario y correo, ejemplo:**
```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

- **Ver las lista de configuraciones, ejemplo:**

```bash
git config --list
```

##  Comandos básicos para proyectos
- **Inicializa un repositorio Git**:
**Nota**: se debe inicializar el repositorio en la carpeta donde se encuentra los archivos del respoitoio.
```bash
 git init
```
- **Agrega un archivo al stagin area**:
```bash
git add <nombre_archivo>
```

- **Agrega todos los archivos al stagin area:**
```bash
git add .
```

- **Confirmar cambios al repositorio**
```bash
git commit -m "Su mensaje"
```

- **Asignar el repositorio a un servidor remoto**
```bash
git remote add origin <url_repository_git>
```

- **Enviar los datos al servidor remoto**
```bash
git push -u origin <nombre_de_su_rama>
```

Ejemplo:
```bash
git push -u origin master
```

## Clonar un repositorio
- **Clonar un repositorio**
```bash
git clone <url_repository_git>
```
## Verificiar el estado del repositorio
- **Verificar el estado del repositorio:**
```bash
git status
```

## **GIT ADD**
- **Agregar todos los archivos**
```bash
git add .
```

- **Agregar un archivo especifico**
```bash
git add <nombre_archivo>
```
Ejemplo: 
```bash
git add README.md
```

- **Agregar un folder**
```bash
git add <nombre_folder>
```
Ejemplo:
```bash
git add MyFolder/
```

## **GIT LOG**
Descripción: sirve para ver el historial de los cambios que se han realizado en el repositorio.
- **Comando git log**
```bash
git log
```

- **Log una línea por commit**
```bash	
git log --oneline
```

- **Ver número limitado de commit por línea**
```bash
git log -3
```

- **Ver diagram para el log con diagrama de rama**
```bash
git log --graph --oneline
```
## **GIT BRANCH**
- **Crear una rama**
```bash
git branch <nombre_de_la_rama>
```
- **Listar las ramas del repositorio**
```bash
git branch
```

- **Cambiar de rama**
```bash
git checkout <nombre_de_la_rama>
```

-**Eliminar una rama especificada**
**Nota**: Elimina la rama especificada. Esta operación es segura, ya que git evita que elimines la rama si tiene aún cambios que no se han fusionado.
```bash
git branch -d <nombre_de_la_rama>
```

- **Eliminar una rama especificada y forzar la eliminación**
**Nota**: fuerza la eliminación de la rama especificada, incluso si tiene cambios que no se han fusionado.
```bash
git branch -D <nombre_de_la_rama>
```

- **Cambiar el nombre de la rama**
```bash
git branch -m <nombre_de_la_rama> <nombre_nuevo_de_la_rama>
```

- **Enumerar las ramas**
```bash
git branch -a
```

## GIT AMMEND
- **Para modificar el mensaje del ultimo commit**
```bash
git commit --amend -m "Su mensaje"
```

## Tabla de contenido
-  [Unir ramas o unir cambios](./docs/UnirCanbios.md)







