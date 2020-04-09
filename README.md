# flask_https_example


# installation

```
# apt install python2.7 python-pip gunicorn nginx
$ openssl req -x509 -newkey rsa:4096 -nodes -out cert.pem -keyout key.pem -days 365
$ pip install flask
# cp hello.nginx /etc/nginx/sites-available/hello
# ln -s /etc/nginx/sites-available/hello /etc/nginx/sites-enabled
# cp hello.service /etc/systemd/system/hello.service
# systemctl restart hello
# systemctl restart nginx
```