Installing CUDA-TSNE with no hussle
=========================================================
To install CUDA-TSNE on an NVIDIA-DOCKER enabled machine run the following:

.. code:: bash

    git clone https://github.com/LucaCappelletti94/default_docker_images
    cd cuda-tsne-docker
    nvidia-docker build --file Dockerfile -t cuda_tsne_docker .
    nvidia-docker run --tty --interactive --publish 13000:13000 cuda_tsne_docker
