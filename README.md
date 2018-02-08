# nginx-phusion
Nginx docker image with phusion base image

Dockerfile Created and Maintained by : Mrunal Nachankar "<mrunal4888@gmail.com>"

---

## Express way with docker-compose

Start container with docker-compose
        
    docker-compose up -d

Check on web browser (default port is 80 for http and 443 for https. If you are using different port add your port after the url in below instructions.)

* If port is not changed.

    * http request

            http://localhost

        **Expected output is "Ngnix default web page"**

    * https request

            https://localhost 

        **Expected output is "Ngnix default web page"**

* If port is changed then check on

    * http request

            http://localhost:<port> 

        **Expected output is "Ngnix default web page"**

    * https request

            https://localhost:<port> 

        **Expected output is "Ngnix default web page"**

---

Thank you for using it. In case of any queries or suggestion feel free to write back on mrunal4888@gmail.com.

---
