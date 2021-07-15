properties([
    parameters([
        // Container parameters
        string(defaultValue: '192.168.48.2:5002/jenkins/jnlp-image-with-tools:latest', description: '', name: 'TASK_IMAGE', trim: false),
        string(defaultValue: 'pvc-ws', description: '', name: 'TASK_PVC', trim: false),
        string(defaultValue: '8Gi', description: '', name: 'TSK_MEM_LIMIT', trim: false),
        string(defaultValue: '4000m', description: '', name: 'TSK_CPU_LIMIT', trim: false),
        // Genenric parameters
        string(defaultValue: '30', description: '', name: 'TASK_TIMEOUT', trim: false),
        string(defaultValue: 'regcred', description: '', name: 'IMAGE_PULL_SECRETS', trim: false),
        // Task parameters
        string(defaultValue: '', description: 'Pipeline ID', name: 'PIPELINE_ID', trim: false),
        string(defaultValue: '', description: 'Pipeline Build ID', name: 'PL_BUILD_ID', trim: false),
        string(defaultValue: '.', description: '', name: 'SROUCE', trim: false),
        string(defaultValue: 'bHMgLWFsCg==', description: 'shell script encoded by base64', name: 'SCRIPT',trim: false)
        ])
])


pipeline{
  agent any
    stages{
      stage('build'){
        steps{
          echo 'Hello World'
        }
      }
    }
}
