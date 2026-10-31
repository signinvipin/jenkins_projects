# jenkins-projects

Small Maven projects used to practice Jenkins build jobs and Nexus publishing. These are lab/learning projects.

| Folder | What it covers | Tech |
|---|---|---|
| [maven-nexus-publish](./maven-nexus-publish) | Maven project configured to publish release and snapshot artifacts to a Nexus repository | Maven, Nexus, Java |
| [sparkjava-war-job](./sparkjava-war-job) | Sample SparkJava hello-world app packaged as a WAR, for a Jenkins build job | Maven, Java, SparkJava |

For a full Jenkins pipeline (SonarQube, Docker, Kubernetes), see [jenkins-cicd-kubernetes](https://github.com/signinvipin/jenkins-cicd-kubernetes).

## Notes
- Server IP addresses are partially masked with `xx` (for example `18.116.xx.xx`). Use your own values when you run these.
- Never commit real credentials. Use Jenkins credentials or environment variables.
