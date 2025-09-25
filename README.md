# Hello Docker (Mac)

Tiny Flask app running in Docker on macOS.

## Run
docker build -t hello-flask:1 .
docker run --rm -p 8081:5000 hello-flask:1

Then open: http://localhost:8081
