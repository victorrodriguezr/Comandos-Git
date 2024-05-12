# Repositorios remotos

Podemos un repositorio local con dos repositorios remotos. Para hacer simplemente se añade lo siguiente:
```bash
git remote add <NOMBRE_UNICO_IDENTIFICADOR> <URL>
```
Para hacer push simplemente lo hacemos de la siguiente manera:
```bash
git push <NOMBRE_UNICO_IDENTIFICADOR> <NOMBRE_DE_LA_RAMA>
```

Para ver los repositorios remotos con los que estan conectados:
```bash
git remote -v
```
Se enlistaran todos los repos que tenemos conectado a github. 


**Ejemplo**
Añadir un otro repositorio:
```bash
git remote add miOtraCuenta https://github.com/myOtraCuenta
```

Push al otra cuenta:
```bash
git push miOtraCuenta main
```

**Nota**: A pesar de que ese repositorio esta conectado a dos repositorios remotos una vez se haga clone en una maquina local, solo va a detectar el repostior del cual fue clonado. 

