This Nagios plugin is able to get the health state of a website.

Functionalities :

- Ping test ;
- HTTPS access availabilty (supports 301 redirections and non-default ports) ;
- SSL Certificate status.

Use it like this:

```shell
./check_website -H <host> -p <ping_threshold> -s <ssl_expiry_threshold> -i <check_interval> -P <ssl_port>
```
