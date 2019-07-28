# The Classic Pack server Docker container

The idea is to have a way to create servers for [The Classic Pack](https://www.technicpack.net/modpack/tc-redux.786294) using Docker.

## Starting the server

The command to start the server:
```
docker run -dti --name theclassipack_server -p 25565:25565 theclassicpack
```

Note that the `ti` options are required to allow the admins to access the server console.

## Accessing server console

To access the server console run:

```
docker attach theclassipack_server
``` 

To exit **do not** run `CTRL+c`, instead use the key combination `CTRL+p` followed by `CTRL+q`
