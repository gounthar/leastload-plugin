/*
 See the documentation for more options:
 https://github.com/jenkins-infra/pipeline-library/
*/
buildPlugin(
    useContainerAgent: true,
    configurations: [
        [platform: 'linux', jdk: 21], // use 'docker' if you have containerized tests
        [platform: 'windows', jdk: 17],
    ])
