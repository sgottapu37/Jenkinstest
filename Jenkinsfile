pipeline:
  agent:
    any:
  stages:
    - stage: "SCM Checkout"
      steps:
        - sh "ls"
    - stage: "Jenkins YAML Maven Build"
      steps:
        - sh "mvn clean compile test install"
    - stage: "Final Jenkins YAML Pipeline Stage"
      steps:
        - sh "echo 'Jenkins YAML Pipeline Complete'"
