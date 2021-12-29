node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockr_id') {

        def customImage = docker.build("jva16/firstimage")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
