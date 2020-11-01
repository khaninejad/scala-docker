## Build Docker Image:

    docker build --tag scala-docker:1.0 .

## Run Command:

    docker run --rm -it --volume ${PWD}:/app scala-docker:1.1

  ## Or Alternatively run command:

    docker exec -it scala-docker:1.0 /bin/bash

