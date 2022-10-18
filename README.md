# Docker

### Task 1
- Demonstrate minimum 15 basic Docker command with explanation and screenshot.
```git
1. docker --version
You can check your current version of docker by running the docker --version 
```
![1  docker --version](https://user-images.githubusercontent.com/94276578/196460157-9def31f1-0a93-4e21-8282-73d0ee7cb5ce.jpg)

```git
2. docker pull
Thi commond enables you to pull an image by docker digest. . 
```
![2  docker pull](https://user-images.githubusercontent.com/94276578/196460509-e0b71c9e-b49e-4347-a0fc-48c11917ad12.jpg)

```git
3. docker images
docker image ls command is used to list the docker images.
```
![3  docker images](https://user-images.githubusercontent.com/94276578/196460610-485628a5-8f58-4f3f-a7c4-a915a45ee22a.jpg)

```git
4. docker run
The docker run command first creates a writeable container layer over the specified image, and then starts it using the specified command.
```
![4  docker run](https://user-images.githubusercontent.com/94276578/196460660-6cb17952-521a-49aa-849a-9b86d0ec802f.jpg)

```git
5. docker ps
The docker ps command, which is available inside the container, is used to see the status of the process.
```
![5  docker ps](https://user-images.githubusercontent.com/94276578/196460743-a64b49a1-587a-4d72-884e-8d4baf6586c1.jpg)

```git
6. docker build
The docker build command builds Docker images from a Dockerfile and a “context”.
```
![6  docker build](https://user-images.githubusercontent.com/94276578/196460838-566f1f12-67e4-4ca6-a396-66383edf9386.jpg)

```git!

7. docker rmi
Removes (and un-tags) one or more images from the host node. 
```
![7  docker rmi](https://user-images.githubusercontent.com/94276578/196460930-233d2ecd-b25f-456d-8295-b7fc2526ccc2.jpg)

```git
8. docker run -d -p
docker run commond where -d specifies detached mode and -p specifies port number.
```
![8  docker run -d -p ](https://user-images.githubusercontent.com/94276578/196461837-7b0dfe8e-5c8a-465b-b862-3d3bb9174d31.jpg)

```git
9. docker stop
Docker stop command sends SIGTERM signal to running container process. It will stop the process however it takes a while to shutdown the container completely.
```
![9  docker stop](https://user-images.githubusercontent.com/94276578/196461903-74dd5dae-e353-49f9-b0fe-67ee6173eda1.jpg)

```git
10. docker push 
Docker Push is a command that is used to push or share a local Docker image or a repository to a central repository like docker hub.
```
![10  docker push](https://user-images.githubusercontent.com/94276578/196461967-99b51ef2-5052-4fa5-b6b4-49e86346a680.jpg)

```git
11. docker image prune
docker image prune: Remove all dangling images.
```
![11  docker image prune](https://user-images.githubusercontent.com/94276578/196462018-d1a9cfa8-eab5-48fc-829f-63d10cb2be52.jpg)

```git
12. docker image prune -a
docker image prune: Remove all dangling images. If `-a` is specified, will also remove all images not referenced by any container.
```
![12  docker image prune -a](https://user-images.githubusercontent.com/94276578/196462099-96cf08b3-8fb4-4dc8-9188-f18f2097845d.jpg)

```git
13. docker system prune
Remove all unused containers, networks, images (both dangling and unreferenced), and optionally, volumes.
```
![13  docker system prune ](https://user-images.githubusercontent.com/94276578/196462182-b89e785d-e910-4537-af89-b7aef2524720.jpg)

```git
14. docker build --help
List downs different options to build docker image.
```
![14  docker build --help](https://user-images.githubusercontent.com/94276578/196462231-df86abf9-55a1-4c8d-9c4a-3148c40a97e0.jpg)

```git
15. docker run --help
List downs different options to run docker image. 
```

![15  docker run --help](https://user-images.githubusercontent.com/94276578/196462282-ebd94140-c139-4e1b-9f97-08badf8002c2.jpg)

### Assignment 2:

[Hello World Docker Image](https://hub.docker.com/_/hello-world)
Run Hello World Docker Image Locally.
![HELLOWORLD](https://user-images.githubusercontent.com/94276578/196463535-52dddba9-5925-43de-b345-3e657442b4b8.jpg)




### Assignment 3:
Create a hello world fastapi application.
Create a Dockerfile for your fastapi hello world application.
Build Docker image using Docker file.
Run docker image build in previous step.
Push your Docker image to Docker Hub.
![FASTAPI](https://user-images.githubusercontent.com/94276578/196470602-3fb387aa-872d-41e0-a299-d1f3469bc794.jpg)



### Assignment 4:
Automate Assignment below task using github action.
1. Build Docker Image 
2. Push Docker Image to Docker hub.
![HELLOWORLD](https://user-images.githubusercontent.com/94276578/196463901-f064daba-2df8-42b0-8f21-ed5d2be31899.jpg)


