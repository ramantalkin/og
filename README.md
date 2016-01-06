## Quickstart
docker run -d -ti -p 8080:8080 --name og1 raman/og

## Check docker logs to see status of container
docker logs og1

Wait for the server to start up (should a minute or so), then point your browser to `http://localhost:8080`
