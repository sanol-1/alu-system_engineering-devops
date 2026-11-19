# load_balancer

Improving the web stack with redundancy: two Nginx web servers behind an
HAProxy load balancer.

## Files

| File | Description |
|------|-------------|
| `0-custom_http_response_header` | Installs Nginx and adds an `X-Served-By` header containing the server hostname. |
| `1-install_load_balancer` | Installs HAProxy and distributes requests to web-01 and web-02 using roundrobin. |

## Author

sanol-1
