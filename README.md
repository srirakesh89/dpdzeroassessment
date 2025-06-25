# dpdzeroassessment
**service1** Go i'm installing go by using this command yum install -y go
after i run the go run main.go  it was installed the go in our server
i write the docker file and build the docker image and created container by using portnumber 8001:8001 43.204.214.8:8001/ping and 43.204.214.8:8001/Hello
.
├── README.md
├── docker-compose.yml
├── ngnix
│   ├── Dockerfile
│   └── nginx.conf
├── service_1
│   ├── Dockerfile
│   ├── README.md
│   └── main.go
└── service_2
    ├── Dockerfile
    ├── README.md
    ├── app.py
    ├── pyproject.toml
    └── uv.lock
**service2** Python im install the uv and pip after using the command was uv run app.py
i write the docker file and build the docker image and created container by using portnumber 8002:8002  43.204.214.8:8002/ping and 43.204.214.8:8002/Hello
Im created ngnix directory and inside created the nginx.conf and build a docker image 
i write the docker-compose.yml file and by using this command docker-compose up --build
