podTemplate(label: 'pod-golang', 
    containers: [
        containerTemplate(
            name: 'golang',
            image: 'golang',
            ttyEnabled: true,
            command: 'cat'
        )
    ]
) {
    node ('pod-golang') {

        stage 'Switch to Utility Container-test'
        container('golang') {

          sh ("go version")
          sh ("go version"
          echo ("build successful1")

        }
    }
}
