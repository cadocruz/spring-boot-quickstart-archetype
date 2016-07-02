Spring Boot 1.3.5.RELEASE Quickstart Maven Archetype
=========================================

Summary
-------
The project is a Maven archetype for Spring Boot application.

* Java 8
* Spring Boot 1.3.5.RELEASE
* Brixton.SR1


Installation
------------

To install the archetype in your local repository execute following commands:

```bash
    git clone https://github.com/cadocruz/spring-boot-quickstart-archetype.git
    cd spring-boot-quickstart-archetype
    mvn clean install
```

Create a project
----------------

Create a new empty directory for your project and navigate into it.

```bash
    mvn archetype:generate \
        -DarchetypeGroupId=br.com.cadocruz.spring-boot-archetypes \
        -DarchetypeArtifactId=spring-boot-quickstart \
        -DarchetypeVersion=1.0.3-RELEASE \
        -DgroupId=my.groupid \
        -DartifactId=my-artifactId \
        -Dversion=my-version
```