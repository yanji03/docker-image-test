node ('slave1') {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("my-hello-world-jing-homework")

        /* Push the container to the custom Registry */
        /*customImage.push()*/
    }
}
