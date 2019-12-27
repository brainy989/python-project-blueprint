# Blueprint/Boilerplate For Python Projects

## Running

### From Python
```shell
python3 -m blueprint
```

### Using Docker

Development image:
```shell
docker build -t blueprint -f dev.Dockerfile -t blueprint:dev .
docker run blueprint:dev
```

Production (Distroless) image:
```shell
docker build -t blueprint -f prod.Dockerfile -t blueprint:prod .
docker run blueprint:prod
```

### Resources
- <https://realpython.com/python-application-layouts/>
- <https://dev.to/codemouse92/dead-simple-python-project-structure-and-imports-38c6>
- <https://github.com/navdeep-G/samplemod/blob/master/setup.py>
- <https://github.com/GoogleContainerTools/distroless/blob/master/examples/python3/Dockerfile>