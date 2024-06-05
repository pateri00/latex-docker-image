### Build using docker

Be warned that `texlive` installations can take some time.
Building the docker image may take a few minutes.

1. Build docker image
    ```bash
    $ docker build -f dockerfiles/Dockerfile.alpine . -t latex-image
    ```
2. Build document
    <!-- ```bash
    $ docker run --rm -v $PWD:$PWD -w $PWD -u `id -u`:`id -g` ba-letter make
    ``` -->

