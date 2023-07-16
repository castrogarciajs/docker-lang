# Docker
Develop faster. Run anywhere. The most-used Tool in Stack Overflow’s 2023 Developer Survey


## commando Docker images

1. **Docker images** mostrará todas las imagenes que tengo en mi maquina
```sh
docker images
```

2. **Docker pull** Descarga una imagen

````sh
docker pull <images>
````

3. **Docker image rm <image:version>** Elimina una imagen

```sh
docker image rm node:18
```


## commando Docker contenedores

1. **Docker create <image-container>** Crea un contenedor basado en una imagen existente

   ```sh
   docker create mongo
   exit: id-container
   ```
   
2. **Docker start: id-container** Para ejecutar el contenedor ya existente
   ````sh
   docker start id
   ````
3. **Docker ps** Me devuelve los contenedores que tengo ejecutando
   ```sh
   docker ps
   ```

4. **Docker stop id-container** Detiene el contenedor
   ```sh
   docker stop id-container
   ```
5. **Docker rm name-container** Elimina el contenedor mediante su imagen
   ```sh
   docker rm name-container
   ```
6. **Docker create --name name-container base-image** cambiar nombre del contenedor
   ```sh
   docker create --name name-container base-image
   ```
   ### Port mapping
7. **Docker create -p27017:27017** 
