JBoss Java EE 7 with RHBA
===================================

This BOM builds on the Java EE full profile BOM, adding Red Hat Business Automation.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
               <groupId>com.redhat.ba</groupId>
               <artifactId>jboss-javaee-7.0-with-ba</artifactId>
               <version>7.1.0-SNAPSHOT</version>
               <type>pom</scope>
               <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
