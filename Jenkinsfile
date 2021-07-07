node {

    checkout scm

    docker.withRegistry('nacchiappan23', 'believer@23') {

        def customImage = docker.build("nach/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
