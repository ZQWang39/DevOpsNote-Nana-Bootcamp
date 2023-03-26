# Intro to Artifact repositroy manager

## What is an Artifact Repository?

* Storage of build artifacts produced by continuous integration and makes them available for automated deployment to different deployment environments
* Provides a central location
* Artifacts are applications built into a single file
* There are different artifact formats:JAR, WAR, ZIP, TAR,etc
* Artifact repository needs to support this specific format
* Repository for each file/artifact 

## What is an Artifact Repository Manager?

* Can store many different artifact types
* Which is great, because as a company you often produce different types of artifacts.

## Public vs Private Artifact Repository Managers

### Public Repository Managers
* There are public repository managers
* For example libraries/frameworks you use as adependency
* You can make own project publically available there

### Private Repository Managers
* Nexus - one of most popular repository manager- Private
* You can upload and store different built artifacts
* Retrieve (download) artifacts laterFor internal usage in your company

## Nexus - Artifact Repository Manager

* Has open source and commercial version
* Host own repositories
* Proxy repositories (intermediary to another repository):
* You can have multiple repositories for different formats or different teams in your company
* Supported formats in Nexus

