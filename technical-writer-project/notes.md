# Current error

 gradle build --scan
> Task :app:compileTestJava FAILED

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:compileTestJava'.
> Could not resolve all files for configuration ':app:testCompileClasspath'.
   > Could not find org.junit.jupiter:junit-jupiter:5.10.23.
     Searched in the following locations:
       - https://repo.maven.apache.org/maven2/org/junit/jupiter/junit-jupiter/5.10.23/junit-jupiter-5.10.23.pom
     Required by:
         project :app

* Try:
> If the artifact you are trying to retrieve can be found in the repository but without metadata in 'Maven POM' format, you need to adjust the 'metadataSources { ... }' of the repository declaration.
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Get more help at https://help.gradle.org.
