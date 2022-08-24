### Prepare Package and Neccessary Library
- Run and setup on local machine, machine will run on Window OS system

```
- Install docker 
https://docs.docker.com/engine/install/ 
- Setup WSL2 environemnt for running Docker on Windows 
https://docs.docker.com/desktop/windows/wsl/ 

```
- Test docker on terminal
docker ps  

```
- Install scoop
https://github.com/ScoopInstaller/Scoop
```
- Install hadolint via scoop
scoop install hadolint
- Test hadolint
make lint

- Install minikube
```
https://minikube.sigs.k8s.io/docs/start/
```

- Activate environment
```
source ~/.devops/bin/activate
```

Steps to procedure

### Prepare Package and Neccessary Library
## Step 1: Install dependencies
- Running `make setup`, create a virtual environment named `.devops`
- `make install`
- `make lint`

## Step 2: Run Docker Container
- `./run_docker.sh`

## Step 3: Update container to Docker hub
- `./upload_docker.sh`

## Step 4: Kubernetes Deploy
- `./run_kubernetes.sh`
