@Library('my-jenkins-shared-library') _

dockerDeployPipeline(
    repoUrl: 'https://github.com/Jackk-Doe/jenkin_test_app_two.git',
    branch: 'main',
    dockerHubRepo: 'jackkdoe/jenkin_test_app_two',
    dockerHubCredsId: 'dockerhub-creds',
    sshCredsId: 'vm-ssh-password',
    deployHost: '143.198.199.4',
    deployPath: 'jenkin_test_app_two',
    discordWebhookId: 'discord-webhook'  // optional
)
