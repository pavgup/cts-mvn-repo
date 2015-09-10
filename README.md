Chemical Transformation Simulator (CTS) Third Party Maven Repository on GitHub
==============================================================================

What is this?
-------------

Binary and data dependencies required to enable CTS APIs are littering existing
repositories with little increase in value.  Instead, this can turn into a central
binary repository for all third-party jars not cleanly hosted elsewhere.

How to use this?
----------------

First make sure you understand what a [maven artifact _repository_](http://maven.apache.org/guides/introduction/introduction-to-repositories.html).
    <repository>
          <id>EPA CTS Maven Release Repository</id>
          <url>https://github.com/pavgup/cts-mvn-repo/raw/master/releases</url>
      <releases>
        <enabled>true</enabled>
      </releases>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>          
        </repository>   
    <repository>
          <id>EPA CTS Maven Snapshot Repository</id>
          <url>https://github.com/pavgup/cts-mvn-repo/raw/master/snapshots</url>
      <releases>
        <enabled>false</enabled>
      </releases>
      <snapshots>
        <enabled>true</enabled>
      </snapshots>          
        </repository> 
