node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("siri9911/nodeapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
