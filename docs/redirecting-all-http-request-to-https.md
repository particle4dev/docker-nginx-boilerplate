### Setup

/etc/nginx/sites-available/default:

```
server {
       listen         80 default_server; # Sets the address and port for IP
       listen    [::]:80  default_server ipv6only=on; # Sets names of a virtual server
       server_name    example.com;
       return         301 https://$host$request_uri;
}
```