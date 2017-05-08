## /Pipeline template/

Plantilla para /pipelines/ usando **Luigi** + **Docker**

### Prerequisitos

- `pyenv, 3.5.2`
- `ag`
- `hub`
- `git flow`
- `docker`
- `docker-compose`
- `docker-machine`

### Instalando

1. Instala y ejecuta el pipeline mediante el comando

``` sh
./iniciar_pipeline.sh
```

Este archivo ejecutará las siguientes tareas:
  1. Crea maquinas con docker localmente
  2. Crea un swarm utilizando esas maquinas 
  3. Instala las imagenes necesarias
  4. Por último ejecuta el pipeline. 

>"Es necesario colocar iris.csv en la carpeta data (para este ejemplo ya debe estar ahí)."

Basado en el proyecto [pipeline-template](https://github.com/nanounanue/pipeline-template)
