Create an image from the Dockerfile using the command:

```shell
docker build -t imagename .
```
Then, use the compose command which uses the configuration from the .yml file. The configuration for container names and ports can be done there. The command is as follows:

```shell
docker compose up
```
after finish be sure to shutdown docker compose with

```shell
docker compose down
```
