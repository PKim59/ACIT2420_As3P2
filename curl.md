# Example curl commands for testing your server

Replace the IP address in the examples with the IP address of your **load balancer, not your servers!**

Run these commands from your host machine, not your server.

## Testing your frontend

web1
```bash
curl.exe http://146.190.127.15
```

web2
```bash
curl.exe http://64.227.99.217
```

loadbalancer
```bash
curl.exe http://146.190.1.145
```

## Testing your backend

web1
```bash
curl.exe http://146.190.127.15/hey
```

web2
```bash
curl.exe http://64.227.99.217/hey
```

web1
```bash
curl.exe -X POST -H "Content-Type: application/json" -d '{"message":"Hello from your server"}' http://146.190.127.15/echo

```

web2
```bash
curl.exe -X POST -H "Content-Type: application/json" -d '{"message":"Hello from your server"}' http://64.227.99.217/echo
```