# Java-Vityarthi

### Java Evolution
* **1991:** James Gosling initiates the "Green Project," aiming to create a programming language for intelligent appliances.
* **1995:** Oak is renamed **Java**, and its first public version, **Java 1.0**, is released.
* **1998:** **Java 2** is released, introducing J2SE, J2ME, and J2EE editions.
* **2004:** **Java 5** (formerly J2SE 5.0) is a major release, introducing features like generics and annotations.
* **2014:** **Java 8** is released, adding lambda expressions and the Stream API, which are key for functional programming.
* **2018:** **Java 11** becomes a Long-Term Support (LTS) release, transitioning to a faster release cycle.

***

### Java Editions
| Feature | Java ME (Micro Edition) | Java SE (Standard Edition) | Java EE (Enterprise Edition) |
| :--- | :--- | :--- | :--- |
| **Purpose** | Used for mobile and embedded devices with limited resources. | Core platform for general-purpose desktop and server applications. | Develops large-scale, distributed, enterprise-level applications. |
| **Typical Use** | Feature phones, Blu-ray players, IoT devices. | Desktop GUIs, command-line applications, applets. | Web services, e-commerce, banking applications. |
| **APIs** | A subset of SE APIs, specific to resource-constrained environments. | The foundational set of APIs, including Swing, AWT, and Collections. | Extends SE with APIs for servlets, JSPs, EJB, and web services. |

***

### Java Architecture: JDK, JRE, JVM

* **JVM (Java Virtual Machine):** The core of the Java platform. The **JVM** is a runtime environment that executes Java bytecode. It acts as an interpreter, translating the compiled `.class` files into the native machine code of the underlying operating system. The **JVM** provides platform independence, allowing Java programs to "write once, run anywhere."

* **JRE (Java Runtime Environment):** A bundle that includes the **JVM**, a set of core libraries, and other supporting files. The **JRE** is what a user needs to run a Java application. It contains all the essential components for a program to execute but does not include development tools like a compiler or debugger.

* **JDK (Java Development Kit):** A complete development kit for building Java applications. The **JDK** includes the **JRE**, the **JVM**, and a suite of development tools, such as the `javac` compiler, `jdb` debugger, and other utilities. It is required for developers to compile and package Java applications.



***

### Installing and Configuring Java on Windows

1.  **Download the JDK:** Go to the official Oracle website or an OpenJDK distribution (e.g., Adoptium, Amazon Corretto) and download the latest JDK installer for Windows.
2.  **Run the installer:** Double-click the `.exe` file and follow the on-screen instructions. The installer will guide you through the process and set up the necessary files.
3.  **Set Environment Variables:**
    * Right-click "This PC" or "My Computer" and select **Properties**.
    * Click on **Advanced system settings**.
    * Click the **Environment Variables** button.
    * Under "System variables," click **New...**.
    * For the "Variable name," type `JAVA_HOME`.
    * For the "Variable value," enter the path to your JDK installation directory (e.g., `C:\Program Files\Java\jdk-17`).
    * In the "System variables" section, find the **Path** variable and click **Edit**.
    * Click **New** and add `%JAVA_HOME%\bin`.
    * Click **OK** on all windows to save the changes.
4.  **Verify the installation:** Open the Command Prompt and type `java -version`. You should see the version information, confirming a successful installation.



***

### Using Eclipse IDE

#### Creating a New Java Project

1.  **Open Eclipse IDE:** Launch Eclipse. If a workspace selection window appears, choose a directory for your projects and click **Launch**.
2.  **Create a Project:** Go to **File > New > Java Project**.
3.  **Configure the Project:** In the new window, enter a project name (e.g., `MyFirstProject`). Ensure the "Use default JRE" setting is correct, and then click **Finish**. Eclipse will create a new project with a default folder structure.
4.  **Create a Class:** Right-click on the `src` folder, then go to **New > Class**. Give your class a name (e.g., `HelloWorld`) and check the `public static void main(String[] args)` box to automatically create the main method. Click **Finish**.



#### Running a Java Configuration

1.  **Write Code:** Inside the `main` method of your new class, add a simple print statement, like `System.out.println("Hello, World!");`.
2.  **Run the Configuration:** Right-click on your class file in the Package Explorer, and select **Run As > Java Application**.
3.  **View Output:** The output of your program will appear in the **Console** view at the bottom of the Eclipse window.



The images are uploaded in assets folder.