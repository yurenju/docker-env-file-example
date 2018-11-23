# docker with env file passing

```shell
$ docker build -t env-cred .
$ docker run -e "CRED=my-secret-pw" -p 8080:8080 env-cred
```

browse http://127.0.0.1:8080 to get result from cred file
