# 🔒 FolderLocker-JavaFX

1. What is the Project?

FolderLocker-JavaFX is a Windows-based JavaFX application that allows users to lock and unlock folders using password protection.
It provides a clean and professional GUI to secure folders and prevent unauthorized access.

2. Features

Select any folder from the system

Lock folders using a password

Unlock folders by entering the correct password

Show / Hide password option

Modern JavaFX GUI

Uses Windows ICACLS permission control

Prevents unauthorized access


3. Tech Stack

Programming Language: Java

Java Version: Java 25

GUI Framework: JavaFX 23

Additional Library: ZIP4J

OS Supported: Windows


4. JavaFX Download

Download JavaFX from the official website:

https://gluonhq.com/products/javafx/

After downloading:

Extract the JavaFX SDK

Note the lib folder path

Add all JavaFX JAR files to your classpath


5. ZIP4J Library Download

Download ZIP4J 2.11.5 from Maven Central:

https://repo1.maven.org/maven2/net/lingala/zip4j/zip4j/2.11.5/zip4j-2.11.5.jar

Add zip4j-2.11.5.jar to the project classpath along with JavaFX libraries.

6. How to Run the Project
Run from IDE (NetBeans / IntelliJ)

Add JavaFX VM options:

--module-path "path_to_javafx_lib" --add-modules javafx.controls,javafx.fxml


Add zip4j-2.11.5.jar to project libraries

Run FolderLocker.java

Run the IDE as Administrator

Run from Command Prompt (Manual)
java --module-path "path_to_javafx_lib" --add-modules javafx.controls,javafx.fxml -cp ".;zip4j-2.11.5.jar" folderlocker.FolderLocker


Replace path_to_javafx_lib with the actual JavaFX lib folder path.


7. Important Notes

This application works only on Windows

Administrator permissions are required for locking/unlocking folders

Passwords are stored in .pass files for authentication

8. Acknowledgement

Special thanks to CodeClause for providing this project during the internship.

