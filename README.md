# Task2
java class loading

Classloader is a subsystem of JVM that is used to load class files.

Java ClassLoader loads a java class file into java virtual machine. 

In java.lang.package, we have class called "ClassLoader" 

Java class loaders are used to load classes at runtime.

ClassLoader in Java is a class which is used to load class files in Java. Java code is compiled into class file by javac compiler and JVM executes Java program, by executing byte codes written in class file. 

Hierarchy of ClassLoaders: 

1.BootStrap ClassLoader : Bootstrap class loader loads all java core classes, which are at the part of runtime. 

2. Extension ClassLoader : Extensions class loader loads classes from this ext folder. 

3. SystemClassLoader :  Java classes that are available in the java classpath are loaded using System class loader. 



