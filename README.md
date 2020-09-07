Helm3 Docker Image

This docker image comes with Helm3 and kubectl installed. You can specify the desired version of Helm by setting the HELM_VERSION var. It defaults to 3.3.1
Basic Usage Instructions
Default (prints Helm3 help)

    docker run --rm -it reacteev/helm3

Execute custom Helm3 command

docker run --rm -it --entrypoint "" wyzenrepo/helm3 helm version

Execute kubectl command

docker run --rm -it --entrypoint "" wyzenrepo/helm3 kubectl version


