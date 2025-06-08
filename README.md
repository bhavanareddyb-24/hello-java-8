@@ -1 +1,41 @@
# hello-java-8
# hello-java-8
markdown
Hello Java Maven

This is a simple Java application built using Maven to print a message.  
It is used as a basic example to integrate with Jenkins for CI/CD learning.

🧾 Project Structure


hello-java-maven/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── HelloWorld.java


🔧 Technologies Used
- Java (JDK 8 or 11)
- Maven
- Jenkins (for build automation)

🚀 How to Run

1. Compile with Maven:
   bash
   mvn clean compile
   

2. Run the program:
   bash
   java -cp target/classes HelloWorld
   

💡 Output


Hello, Jenkins + Maven!
```
```
