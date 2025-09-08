# What is a docker container and how to setup and create new docker containers?

A Docker container is a lightweight, standalone, and executable software package that includes everything needed to run an application: application code, runtime, system tools, libraries, and settings. Docker containers share the host's OS kernel but are isolated from each other, making them fast, portable, and efficient compared to traditional virtual machines. They ensure applications run consistently across different environments by packaging the app with all its dependencies together in a container.[^1_1][^1_3][^1_5][^1_7]

To set up and create new Docker containers, the general steps are:

1. Install Docker on your machine (Docker runs on Windows, macOS, and Linux).
2. Create a Docker image, usually starting by writing a Dockerfile that contains the instructions to build the image (including the application and dependencies).
3. Build the Docker image from the Dockerfile using the `docker build` command.
4. Create a Docker container from an existing image using the `docker container create` or `docker run` command. The `docker create` command sets up the container without starting it, while `docker run` creates and starts the container.
5. Use `docker start` to start a created container or interact with it using other Docker commands.

Example commands:

- Create container (without start):

```bash
docker container create --name mycontainer myimage
```

- Start container:

```bash
docker start mycontainer
```

- Alternatively, create and run container immediately:

```bash
docker run --name mycontainer myimage
```


Options are available to attach standard input/output, set environment variables, allocate memory limits, and more during container creation.[^1_2][^1_4][^1_6][^1_10]

This process allows developers to isolate applications and their dependencies rapidly and consistently across development, testing, and production environments.
<span style="display:none">[^1_8][^1_9]</span>

<div style="text-align: center">⁂</div>

[^1_1]: https://www.geeksforgeeks.org/devops/introduction-to-docker/

[^1_2]: https://docs.docker.com/reference/cli/docker/container/create/

[^1_3]: https://www.freecodecamp.org/news/how-docker-containers-work/

[^1_4]: https://www.geeksforgeeks.org/devops/create-a-docker-container-from-an-existing-image/

[^1_5]: https://circleci.com/blog/docker-image-vs-container/

[^1_6]: https://learn.microsoft.com/en-us/dotnet/core/docker/build-container

[^1_7]: https://www.docker.com/resources/what-container/

[^1_8]: https://chtc.cs.wisc.edu/uw-research-computing/docker-build

[^1_9]: https://www.reddit.com/r/docker/comments/keq9el/please_someone_explain_docker_to_me_like_i_am_an/

[^1_10]: https://www.hostinger.com/in/tutorials/docker-start-a-container

