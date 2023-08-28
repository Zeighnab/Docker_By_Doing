1. Install docker daemon and CLI from docker repo.
```
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo

sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y
```

2. Start and enable docker daemon
```
sudo systemctl start docker
sudo systemctl enable docker
```

3. Configure your account to use docker without root permissions
```
sudo usermod -aG docker {user}
```

4. Exit and login to confirm addition of docker
```
groups
```

5. Run a test image
```
docker run hello-world
```