godocs-docker
=============

Docker container to serve up godocs

Pull from the Docker registry:

```
docker pull defermat/godocs-docker
```

Or build and run from source:

```
git clone https://github.com/defermat/godocs-docker.git
cd godocs-docker
docker build -t godocs .
docker run -d -P godocs
```

To run:

```
docker run -d -p 6060:6060 defermat/godocs-docker
```

and browse to the docker host on that port.

Alternatively run as:

```
docker run -d -P defermat/godocs-docker
```

to get a dynamically assigned port.
