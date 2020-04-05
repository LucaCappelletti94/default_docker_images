default_docker_images
=================================================
Docker images for doing stuff quickly.

.. code:: bash

    nvidia-docker build --file Dockerfile -t $(basename $PWD) .
    nvidia-docker run --tty --interactive --publish 8888:8888 $(basename $PWD)
