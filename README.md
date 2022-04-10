# rustagram

## Installation
Docker should be installed   
`docker --version`

Run postgres image with port forwarding:
`docker run --name postgres-rustagram -p 5432:5432  -e POSTGRES_PASSWORD=admin -d postgres`

`--name` is a local name of running container   
`-p` is port mapping of container:host  
`-e` is run params for the image  
`-d` means detach  

Check connection, type `\q` to exit  
`psql -h localhost -p 5432 -U postgres`

