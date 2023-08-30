## Scenerio:

You are tasked with migrating a website, from a traditional server, into containers. Once Docker is installed, how do you start developing a solution to your assignment?

For this lab, we will be using httpd and nginx.
View the Description and Tags. Click the latest tag in the Description to see the Dockerfile.


Clone the existing website code onto the server. The website is available at 


In a browser, go to the public IP of your server on port 8080, to verify the website is displaying.

Get the latest nginx image from Docker Hub.
Run a container named "nginx" from the nginx image. Map server port 8081, to port 80 in the container.
In a browser, go to the public IP of your server on port 8081, to verify the nginx webserver is running.

Stop and delete your current running nginx container.
Create a new nginx container, mounting the website data into the container. Remember to map the port!
In a browser, go to the public IP of your server on port 8081, to verify the website is displaying



