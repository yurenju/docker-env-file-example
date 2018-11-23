# docker with env file passing

```shell
$ docker build -t env-cred .
$ docker run -e "CRED=my-secret-pw" -p 8080:8080 env-cred
```
