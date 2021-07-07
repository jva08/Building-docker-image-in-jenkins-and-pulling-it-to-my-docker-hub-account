node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dock') {

        def customImage = docker.build("nach/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
