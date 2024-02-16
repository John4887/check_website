This Nagios plugin is able to get the health state of a website.

Functionalities :

- Ping test ;
- HTTPS access availability (supports 301 redirections and non-default ports) ;
- SSL Certificate status (is also able to detect auto-signed certs).

Use it like this:

```shell
./check_website -H <host> -p <ping_threshold> -s <ssl_expiry_threshold> -i <check_interval> -P <ssl_port>
```
Examples of status:
![alt text](https://github.com/John4887/check_website/blob/main/check_website_OK-example.png)
![alt text](https://github.com/John4887/check_website/blob/main/check_website_CRITICAL-example.png)
