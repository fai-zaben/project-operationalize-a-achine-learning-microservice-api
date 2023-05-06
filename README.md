CircleCI status badge
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/fai-zaben/project-operationalize-a-achine-learning-microservice-api/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/fai-zaben/project-operationalize-a-achine-learning-microservice-api/tree/main)

## Project Overview

### summary of the project

Containerizing a Python flask app which is pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on.

### Pre-reguest: Python 3.7

### Instructions
1. clone repo locally
2. create a virtual environment and activate it using the following command:

```
make setup
```

3. install dependencies using the folowng command:

```
make install
```

4. run Docker container by running the following script:

```
./run_docker.sh
```

5. upload to Docker Hub by running the following script:

```
./upload_docker.sh
```

> Note: change the dockerpath variable to contain your Docker Hub username

6. kubernetes deployment by running the following script:

```
./run_kubernetes.sh
```

