# Example curl commands for testing your server

Replace the IP address in the examples with the IP address of your **load balancer, not your servers!**

Run these commands from your host machine, not your server.

## Testing your frontend

loadbalancer
```bash
curl.exe http://146.190.1.145
```

## Testing your backend

loadbalancer/hey
```bash
curl.exe http://146.190.1.145/hey
```

loadbalancer/echo
```bash
curl.exe -X POST -H "Content-Type: application/json" -d '{"message":"Hello from your server"}' http://146.190.1.145/echo
```