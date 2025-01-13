# sit-service-bom

Parent for packages that should not be deployed to maven central.

The following plugins will be removed for inherting projects:
- org.sonatype.central - central-publishing-maven-plugin
- org.apache.maven.plugins - maven-gpg-plugin

The following dependencies will be included:
- dev.sitconsulting - sit-metrics-autoconfiguration
- org.springframework.boot - spring-boot-starter-web
