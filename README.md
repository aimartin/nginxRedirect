# nginxRedirect
Docker container with nginx that redirects all http requests to https

To use it, just execute the container exposing port 80, any url that nginx receives will be returned as 301 with https instead of http.

docker run -d -p 80:80 aimartin/nginxRedirects
