# loupax/pgsql-client

## Build
```shell
docker build -t loupax/pgsql-client:tagname .
docker push loupax/pgsql-client:tagname
```

## Usage
```shell
kubectl run -i --tty my-shell --image=loupax/pgsql-client:tagname postgres://$USERNAME:$PASSWORD@$HOST:5432/$DB?sslmode=disable
```
