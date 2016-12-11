# Running inside local Docker image

## Build the image

```sh
docker build -t node_docker_test .
```

## Run the image

```sh
docker run -it -p 8000:8000 --rm --name my_node_docker_test node_docker_test
```
