# Overview
This is the POM parent for OSS projects distributed via Sonatype's OSS Nexus repository.

# Usage
```
<parent>
	<groupId>eu.ralph-schuster</groupId>
	<artifactId>pom-oss</artifactId>
	<version>2.2.0</version>
</parent>
```

# Features
* Java 17 is default source format
* Java 17 is default target format
* Attaching Java sources
* Attaching Javadoc
* Signing artifacts
* Publishing to OSS Staging repository
* Generating Maven Site:
    * Surefire JUnit test report
    * Javadoc pages
    * Test Javadoc pages
    * Project information
    * Issue tracking report (from JIRA)
    * NCSS report
    * Tag list report
* Publishing Maven Site to [downloads.ralph-schuster.eu]

# License
Licensed under [GNU LGPL](LICENSE.md).

# Help and Contribution
Please use the Issue Tracker at [GitHub](https://github.com/technicalguru/pom-parent).