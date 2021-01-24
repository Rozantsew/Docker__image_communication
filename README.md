# Docker__image_communication

1. Go to the directory docker_src and run the farther commend to build container: 
    $ docker build -t mount_point_demo .

2. Create docker container using command:
    $ docker run --rm -ti mount_point_demo

# In text version in this place will appear samba image
3. In directory docker_src create folder with name zasob_acl using command:
    mkdir zasob_acl

4. Creating kontainer with ability to share information using command(Pleace specify correct path!):

    $ docker_src michael$ docker run -it -v /Users/michael/WorkSpace/Docker__image_communication/docker_src/:/zasoby_kont:rw --name konteiner1 cabelo/opensuse-leap-15.2 /bin/bash 
 
5. At this point You can create files and they are will be wissible inside conteiner and outside the container