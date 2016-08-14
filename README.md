# android-gradle-samples

## [uploadArtifactsSample](./uploadArtifactsSample.gradle)
This script publishes your android library to a maven repository using the [gradle maven plugin](https://docs.gradle.org/current/userguide/maven_plugin.html). It creates the .aar, javadoc.jar, sources.jar and .pom and updates the maven-metadata.xml after uploading the files to the maven repository.

## [uploadArtifactsWithTFSRelease](./uploadArtifactsWithTFSRelease.gradle)
This script is like the [uploadArtifactsSample](./uploadArtifactsSample.gradle). But it's purpose is to publish your android library with the [Release Management of the Team Foundation Server](https://www.visualstudio.com/en-us/features/release-management-vs.aspx) in combination with [Team Foundation Server Builds](https://www.visualstudio.com/en-us/docs/build/overview)
