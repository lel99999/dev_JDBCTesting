# dev_JDBCTesting
JDBC Testing Workspace and Notes

#### Testing various jdbc jars
- JDBC for Thriftserver/Hive2 Hadoop/Spark


#### Classloaders
- Bootstrap class loader
  - mainly responsible for JDK internal classes, typically rt.jar and other core libraries located in $JAVA_HOME/jre/lib

- Extension class loader
  - child of bootstrap class loader, takes care of loading the extensions of standard core Java classes ... loads from
    $JAVA_HOME/lib/ext

- System class loader
  - mainly handles loading of all the application level classes into the JVM.  It loades files found in the classpath
    environment variable, -classpath or -cp command line option. It's also a child of the extension class loader
