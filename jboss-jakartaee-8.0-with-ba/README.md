JBoss Java EE 8 with RHBA
===================================

This BOM builds on the Java EE full profile BOM, adding Red Hat Business Automation.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>com.redhat.ba</groupId>
               <artifactId>jboss-jakartaee-8.0-with-ba</artifactId>
               <version>7.11.0</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
