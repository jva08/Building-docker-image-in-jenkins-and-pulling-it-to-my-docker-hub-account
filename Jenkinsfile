node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/', 'nacchiappan23') {

        def customImage = docker.build("nach/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
