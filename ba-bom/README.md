RHBA BOM
===================================

This BOM contains all supported Maven artifacts for Red Hat Business Automation.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>com.redhat.ba</groupId>
               <artifactId>ba-bom</artifactId>
               <version>7.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
