# Introduction docker

Install docker with script and test it 

### Installation instruction
1. `curl -fsSL https://get.docker.com -o get-docker.sh`
2. `sh get-docker.sh`
### Post installation instructions
1. Add the user in the group docker to not use docker with root rights: `sudo usermod -aG docker username`
2. Start docker: `sudo systemctl start docker`
3. Enable docker to automatically start docker at boot time: `sudo systemctl enable docker`
### Test
1. `docker --version`
2. `docker run helloworld`
3. `docker run -d  --name`nginx -p 80:80 nginx`
4. `docker ps`
5.  copy the ip address of the machine in the browser with port 80: `@ip:80`
