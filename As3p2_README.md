# PaulK_as3p2

These files were used to set up a web server using a provided binary. The files were used to set up two DigitalOcean droplets (Debian12) using a cloud-config.yaml file, a previously provided file to serve as the binary for the newly made hello-server.service file, and include an index.html which would be served using the nginx service.

The assignment was creating 2 web servers that would serve 3 pages; the base, the /hey page, and the /echo page. It had to have a load balancer in front of the two servers as well as use reverse-proxy functionality.

The included backend server runs on port 8080, 127.0.0.1:8080.

## Included material

- backend binary, hello-server (provided by Nathan)
- frontend, index.html (provided by Nathan)
- nginx configuration file, hello.conf (initial file provided by Nathan, adjusted for the assignment)
- service file for backend, hello-server.service (initial file provided by Nathan, adjusted for the assignment)
- config for setting up servers, cloud-config.yml (initial file provided by Nathan, adjusted for the assignment)
- example curl commands for testing your server, curl.md (adjusted for use in Windows)

