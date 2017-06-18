# docker-static-files-serve
A simple example to show how to serve static files from docker using nginx

To run this example,

Clone this repo

1. git clone https://github.com/arunkumars08/docker-static-files-serve.git
2. Navigate into the directory
3. You can see web folder that has static assets to be served from inside docker container.
4. You see Dockerfile and nginx.conf files

Run this command
```
docker build -t some-name .
```

Once the build is complete and the image is created, run the docker 

```
docker run -p 5000:90 some-name
```

Navigate to http://localhost:5000 to see the changes


For detailed reference, visit this link
https://www.linkedin.com/pulse/serve-static-files-from-docker-via-nginx-basic-example-arun-kumar