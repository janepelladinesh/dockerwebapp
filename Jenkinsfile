node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("dineshcherry/ddockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
