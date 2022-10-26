Telenav Superpom
================

This project contains a Maven superpom defining how to build 
Telenav Open Source projects, including:

- kivakit
- mesakit
- lexakai
- cactus

### Releasing to Maven Central

To release a new version of this project to Maven Central:
 
1. In a shell window, run  `./release` or `mvn -P sign-artifacts clean deploy`
2. Sign into [OSSRH](https://s01.oss.sonatype.org/#stagingRepositories), close the staging repository and release to Maven Central
3. Update any dependent projects, as appropriate
