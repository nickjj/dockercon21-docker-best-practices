Here's reference links for my live demo talk from DockerCon 21.

### Best Practices around Creating a Production Ready Web App with Docker and Docker Compose

*May 27th 2021* 

In this talk we'll go over practical Docker Compose examples of using the
override file pattern, aliases & anchors, creating a health check and making
the most of environment variables. On the Dockerfile side of things we'll go
over running containers as a non-root user, using multi-stage builds, setting
build ARGs and an ENTRYPOINT script.

#### Example open source apps

- https://github.com/nickjj/docker-flask-example
  - The above link leads to the `main` branch (most up to date), but you can check out `0.5.0` to match the talk
- https://github.com/nickjj/docker-django-example
- https://github.com/nickjj/docker-rails-example
- https://github.com/nickjj/docker-node-example
- https://github.com/nickjj/docker-phoenix-example
- https://github.com/oleksandra-holovina/docker-play-example (Thanks [Lexie](https://www.linkedin.com/in/oleksandra-holovina-287740b0)!)

#### Personal links / learning resources

- https://nickjanetakis.com
- https://diveintodocker.com
- https://runninginproduction.com
- https://nickjanetakis.com/courses/

#### Blog post references

- https://nickjanetakis.com/blog/why-i-prefer-running-nginx-on-my-docker-host-instead-of-in-a-container
- https://nickjanetakis.com/blog/the-tools-i-use (every tool I used in the talk and how they're configured)
