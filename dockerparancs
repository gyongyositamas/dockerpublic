c14@u136:~$ ssh ubuntu@192.168.2.157
ubuntu@192.168.2.157's password: 
Welcome to Ubuntu 16.04.6 LTS (GNU/Linux 4.4.0-142-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

21 csomag frissíthető.
13 frissítés biztonsági frissítés.

New release '18.04.2 LTS' available.
Run 'do-release-upgrade' to upgrade to it.



ubuntu@ubuntu:~$ sudo apt-get update


ubuntu@ubuntu:~$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
OK
ubuntu@ubuntu:~$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
ubuntu@ubuntu:~$ sudo apt-get update
ubuntu@ubuntu:~$ apt-cache policy docker-ce
ubuntu@ubuntu:~$ sudo apt-get install -y docker-ce

ubuntu@ubuntu:~$ sudo systemctl status docker
ubuntu@ubuntu:~$ sudo apt install mc
ubuntu@ubuntu:~$ sudo touch Dockerfile
ubuntu@ubuntu:~$ sudo mc
ubuntu@ubuntu:~$ sudo docker build -t webserver-image:v1 . 
ubuntu@ubuntu:~$ sudo docker images 
ubuntu@ubuntu:~$ sudo mc
ubuntu@ubuntu:~$ sudo docker run -d -p 80:80 webserver-image:v1 
3d1e5bdb3e7f6c30bdcacbfc19a779639049bd901d94e050940c17abef1b9a9a
docker: Error response from daemon: driver failed programming external connectivity on endpoint thirsty_vaughan (f295bb8cd2c5127194cf4c36235764f2b6a2d090e872a5202fcfc04c0f65a2a2): Bind for 0.0.0.0:80 failed: port is already allocated.
ubuntu@ubuntu:~$ sudo docker stop  -d -p 80:80 webserver-image:v1 
unknown shorthand flag: 'd' in -d
See 'docker stop --help'.
ubuntu@ubuntu:~$ sudo docker run  -d -p 80:80 webserver-image:v1 
db9b63c6f2269738516fec93e02569fda77c1daabbe8b7ac400d3ff9978d14c4
ubuntu@ubuntu:~$ sudo mc
ubuntu@ubuntu:~$ touch index.html
ubuntu@ubuntu:~$ sudo mc
ubuntu@ubuntu:~$ sudo docker container  ls -a
ubuntu@ubuntu:~$ sudo mc
ubuntu@ubuntu:~$ cd kozos
ubuntu@ubuntu:~/kozos$ ls
ubuntu@ubuntu:~/kozos$ docker ps 
ubuntu@ubuntu:~/kozos$ sudo -s 
root@ubuntu:~/kozos# docker ps
root@ubuntu:~/kozos# docker container 
root@ubuntu:~/kozos# docker container kill recursing_cori 
root@ubuntu:~/kozos# docker ps -a
root@ubuntu:~/kozos# docker container prune 
root@ubuntu:~/kozos# docker images
root@ubuntu:~/kozos# docker images 
root@ubuntu:~/kozos# docker images webserver-image
root@ubuntu:~/kozos# docker images webserver-image 
root@ubuntu:~/kozos# docker images webserver-image:v1 
root@ubuntu:~/kozos# docker build -t ng .
root@ubuntu:~/kozos# docker run -d -p 80:80 --name tomi ng
root@ubuntu:~/kozos# nmap 127.0.0.1
root@ubuntu:~/kozos# ifconfig
