RHBA Platform BOM
=====================================
This BOM contains versions for all supported Red Hat Business Automation artifacts and also all the 3rd party transitive artifacts
used by the RHBA.
The use case for this BOM is at places where one needs to depend on some 3rd party artifact and at the same time wants
to make sure it has the same version as is used by RHBA (to avoid compatibility issues).

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>com.redhat.ba</groupId>
               <artifactId>ba-platform-bom</artifactId>
               <version>7.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
