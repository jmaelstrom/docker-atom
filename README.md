# Dockerized Atom Editor
This is the Atom editor running within a Docker container

Based upon: https://github.com/rakshazi/docker-atom - but without the PHP dependencies

# Usage

docker run -d -v /tmp/.X11-unix/:/tmp/.X11-unix/ -v /dev/shm:/dev/shm -v `pwd`:/workspace -e DISPLAY=${DISPLAY} -v ~/.atom:/root/.atom mgen/atom:1.0.0

or

add the atom script to your path.

# TODO
Masquarde the in container user as the host user

