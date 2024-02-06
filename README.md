# flask_web
Creating a simple web app in Flask, and deploying it with Docker.
<br>
<br>
In order to dockerize our Flask application, we need the following files:

`app.py`: Python file that creates a basic web application using Flask

`requirements.txt`: Specify the Flask version we use as `0.10.1`

`Dockerfile`: Our Flask Dockerfile, used to create a Docker image for `app.py`
<br>
<br>
After creating these files, we build the image with `docker build`, and then run the container with `docker run`. After enabling local port forwarding in our terminal session, we are able to view the application in a browser. Check it out!

<img src=flask_web_example_image.png width=800px>
