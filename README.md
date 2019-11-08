# oracle-docker11g
Trasteo con Docker y oracle

Es nececesario bajar el fichero que se indica en el Dockerfile


Para lenvatar el servicio llega con

```sh

  docker-compose [-p oracle] up''
  
```  
- [-p oracle] por si queremos utilizar un nombre distinto a la carpeta **

Para copiar scripts con powerShell al directorio temporal de la imagen:

```powershell
  foreach ($file in  Get-ChildItem -name ) { docker cp  $file oracle11g:/tmp//}
  
```
