# Simple Statistics

Simple Statistics is a Java-based implementation for computing statistics on a set of numbers.
This implementation is intended to be used in software engineering courses as
a subject software system.

Simple Statistics uses the Apache Ant build system. **Make sure that you have [Ant](https://ant.apache.org) installed.**

#### How to build Simple Statistics and run its tests from the terminal:

1. Change into the Simple Statistics root directory, which contains the *build.xml* build file.

2. Run `ant compile` to compile Basic Statistics. The compiled class files will be in the *bin* directory.

3. Run `ant document` to generate API documentation for Simple Statistics. The generated HTML files will be in the *jdoc* directory.

4. Run `ant clean` whenever you want to clean up the project (i.e., delete all generated files).

#### How to run Simple Statistics from the terminal:

1. After building the project (i.e., running `ant compile`), run: `java -cp bin SimpleStatsApp`. The application's GUI will show up.

#### Program features:
* Displays a set of entered numbers.
* Computes the mean of the set of numbers.
* Computes the median of the set of numbers.
* Computes the mode of the set of numbers.

## Troubleshooting

#### Java JDK not installed or misconfigured
If a Java JDK is not installed or properly configured on your system, you may encounter the following error: 
```
BUILD FAILED
build.xml:17 Unable to find a javac compiler;
```
Make sure that you have a JDK installed and that the JAVA_HOME environment variable is properly set.
