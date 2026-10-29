## Create Docker network

```sh
docker network create pangolin-proxy
```

## Edit .env
Pangolin > Site > Add Site > Type: Pangolin Site  

Get the values of: `Endpoint`, `ID`, `Secret`.   

Then fill them into the `.env` file.  

## Run
```sh
docker compose up -d
```
