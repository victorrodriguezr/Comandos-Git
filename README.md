# Comandos-Git
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
- **Inicializa un repositorio Git:**
```bash
 git init
```
- **Agrega un archivo al repositorio:**
```bash
git add <nombre_archivo>
```

- **Agrega todos los archivos al stagin area:**
```bash
git add .
```

- **Agrega al repositorio**
```bash
git commit -m "Su mensaje"
```

- **Subir el repositorio a un servidor remoto**
```bash
git remote add origin <url>
```

- **Enviar los datos al servidor remoto**
```bash
git push -u origin master
```







