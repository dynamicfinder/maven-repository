maven-repository
================

Snapshot Repository for dynamicfinder projects.

To deploy to local directory, use:
mvn -DaltDeploymentRepository=release-repo::default::file:../maven-repository/releases clean deploy

or
mvn -DaltDeploymentRepository=snapshot-repo::default::file:../maven-repository/snapshots clean deploy