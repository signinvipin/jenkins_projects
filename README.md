# jenkins_projects

Small Maven projects used to practice Jenkins build jobs and Nexus publishing. These are lab/learning projects.

| Folder | What it covers | Tech |
|---|---|---|
| [maven_nexus_publish](./maven_nexus_publish) | Maven project configured to publish release and snapshot artifacts to a Nexus repository | Maven, Nexus, Java |
| [sparkjava_war_job](./sparkjava_war_job) | Sample SparkJava hello-world app packaged as a WAR, for a Jenkins build job | Maven, Java, SparkJava |

For a full Jenkins pipeline (SonarQube, Docker, Kubernetes), see [jenkins_cicd_kubernetes](https://github.com/signinvipin/jenkins_cicd_kubernetes).

## Notes
- Server IP addresses are partially masked with `xx` (for example `18.116.xx.xx`). Use your own values when you run these.
- Never commit real credentials. Use Jenkins credentials or environment variables.
