# Hello-World
Simple Hello World app with Spring Boot and Docker.

Import the project.

Build it in command line with gradle in order to generate an executable jar.

```gradle build```

Then, for building it with docker, do this :

```docker build -t helloworld .```

We create an image called "helloworld"

Then, we run it. We specify port 8080 on the container and we map this with the port 5000 on the host OS

``docker run -p 5000:8080 helloworld```

Hence, connect you on : http://localhost:5000
