## DockerfileProject
This project contains a simple Dockerfile that, when built and run, outputs “Hello, Captain!” to the console.
### Instructions

1. **Clone the repository** (if applicable):

    ```bash
    mkdir dockerfileproject
    cd dockerfileproject
    git clone https://github.com/AyuOrniThrONE/DockerfileProject
    ```

2. **Build the Docker image**:

    Run the following command to build the Docker image using the Dockerfile in the root directory:

    ```bash
    docker build -t dockerfileproject .
    ```

3. **Run the Docker container**:

    After building the image, you can run the container using:

    ```bash
    docker run dockerfileproject
    ```

4. **Output**:

    After running the container, you should see the following output in your terminal:

    ```bash
    Hello, Captain!
    ```
https://roadmap.sh/projects/basic-dockerfile
