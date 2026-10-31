# maven-nexus-publish

A small Maven project (`NumberGenerator`) configured to publish artifacts to a Nexus repository. Used to practice Jenkins and Nexus integration.

## What's inside
- `pom.xml`: `distributionManagement` points to the Nexus `Releases` and `Snapshots` repositories (host masked as `18.116.xx.xx`)
- `src/`: sample Java classes and a JUnit test

## Usage
1. The Nexus address in `pom.xml` is masked (`18.116.xx.xx`). Replace it with your own Nexus host.
2. Add credentials for the `Releases` and `Snapshots` server ids in `~/.m2/settings.xml` (never in `pom.xml`).
3. Build and publish:

```bash
mvn clean deploy
```

Versions ending in `-SNAPSHOT` go to the Snapshots repository, and other versions go to Releases.
