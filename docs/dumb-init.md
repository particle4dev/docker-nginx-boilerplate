### Setup

> https://github.com/Yelp/dumb-init


> https://github.com/google/cadvisor/issues/1131
```
Connecting to www.google.com (173.194.115.49:443)
wget: can't execute 'ssl_helper': No such file or directory
wget: error getting response: Connection reset by peer

apk add --no-cache \
    wget \
    ca-certificates \
    openssl
```