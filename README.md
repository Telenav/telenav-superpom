Telenav Superpom
================

Shared configuration for a number of Telenav's open-source projects, such as KivaKit,
MesaKit and Lexakai.

## Release Process

To release a new version of the Telenav superpom:
 
1. In a shell window, run  `./release.sh` or `mvn -P sign-artifacts clean deploy`

2. Sign into [OSSRH](https://s01.oss.sonatype.org/#stagingRepositories), close the staging repository and release to Maven Central

3. Update any dependent projects, as appropriate
