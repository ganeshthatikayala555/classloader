# classloader

simple pgm to tell how bootstrap classloader loads the core classes(java.lang.Object--java.lang.Class--java.lang.String)
java.lang.Class: Represents classes and interfaces in the Java Virtual Machine.
java.lang.String: Provides methods for working with strings.
###application classloader loads classes dynamically ..if an object of another class is created in a class containing main method ,
the .class with main method loaded first then the aanother .class loaded dynamically during runtime..this enables efficient memory usage(classes
are loaded by application loader when they are needed)
