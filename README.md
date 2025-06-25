# Dockerized Flask App

## Build the Docker image

```sh
docker build -t flask-app .
```

## Run the container

```sh
docker run -p 5000:5000 flask-app
```

Visit [http://localhost:5000](http://localhost:5000) in your browser. 