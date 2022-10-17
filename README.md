# flaskapp-Nginx-Redirect
A Simple Flask App, running through Nginx Proxy Server

Target:
A simple UI that receive Email Address and Name
Use the same data to print them as Output

The Flask App Run at port 5000
uWSGI redirects it to 8080
Nginx provides a proxy server to run the app on port 80.

MACHINE-IP:80 shows this:

![image](https://user-images.githubusercontent.com/92083624/196174482-49aa94e5-1ea4-4749-ac3d-db7611258f73.png)


After entering data, "IP/process" API is also available on Port 80.

![image](https://user-images.githubusercontent.com/92083624/196175026-29c73e57-7857-42e3-a56e-f8253faac9ce.png)
