# layers-Recetas


Entrar a la carpeta commonModelDB y en node  abrir una consola y en esa seccion poner:


```bash
npm install
```


volver a la carpeta raiz y hacer el 

```bash
sls deploy -V
```


ver el arn y meterlo en el serverles yml del proyecto

del proyecto principal 

Ejemplo :

  layers:
    - arn:aws:lambda:us-east-1:675296751371:layer:CommonModelsDb:4
