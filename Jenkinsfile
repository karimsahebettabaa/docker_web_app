node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com/, 'karimsahebettaba') {

        def customImage = docker.build("karimsahebettabaa/docker_web_app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
