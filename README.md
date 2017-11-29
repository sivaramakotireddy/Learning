# Learning
Self Learning 

We will write our code in java and now we need to compile the code. For this we need JVM means java virtual machine. In JVM javacode is compiled into bytecode.
First for any java project we need to create class.JVM only knows class.
For compiling on command prompt we will use javac filename.java. But what happens when we do this is, there is JRE(JAVA RUNTIME ENVIRONMENT)-it provides environment for JVM.
javac+JVM(JRE) = JDK(java development kit)
JDK has all these.
"java class loader is a part of JRE that loads java classes into the JVM"
In a JVM, each and every class is loaded by some java.lang.ClassLoader. The ClassLoader class is located in the java.lang package 
When JVM is started 3 class loaders are used. They are:
1.Bootstrap class loader: It is for loading key Java classes like java.lang.Object 
2.Extensions class loader: It can store extension libraries, which provide features that go beyond the core Java runtime code. It is for loading all .jar files.
3.System class loader: It loads code found on java.class.path.
