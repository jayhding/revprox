# revprox

Lightweight reverse proxy 1 port

## Installation

- Go

    ```bash
    $ go get -u github.com/acoshift/revprox
    ```

- Docker

    ```bash
    $ docker pull acoshift/revprox
    ```

## Build from source

```bash
$ git clone https://github.com/acoshift/revprox.git
$ cd revprox
$ make
```

## How to Run

```
$ revprox -addr=:8080 -target=http://localhost:9000
```

This command will start single host reverse proxy on address `:8080`.
