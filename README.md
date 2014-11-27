godocs-docker
=============

Docker container to server up godocs

Pull from the Docker registry:

```
docker pull defermat/godocs-docker
```

Or build from source:

```
git clone https://github.com/defermat/godocs-docker.git
cd godocs-docker
docker build -t godocs .
```

To run:

```
docker run -d -p 6060:6060 godocs
```

and browse to the docker host on that port.

Alternatively run as:

```
docker run -d -P godocs
```

to get a dynamically assigned port.
