# Instruction : How To Build A Complete JSON API In Golang (JWT, Postgres, and Docker) by Anthony GG

Bank JSON API project in Golang with JWT authentication, Postgresql, and Docker.

https://github.com/anthdm

## Not completed


## Setup

install choco
install make 

```bash
make run
```

```bash
go mod init gobank
go get github.com/gorilla/mux
go get golang.org/x/crypto/bcrypt
go get github.com/stretchr/testify/assert

go get -u github.com/golang-jwt/jwt/v4

export JWT_SECRET=somesecretsomesecret

```

test

```shell
go test .\... -v
```

seed

```shell
make
./bin/gobank --seed
```



## References

https://pkg.go.dev/github.com/lib/pq
