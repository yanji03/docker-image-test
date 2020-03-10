node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("my-hello-world:${env.BUILD_ID}")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}