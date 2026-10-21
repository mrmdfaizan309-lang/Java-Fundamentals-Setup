# Java Developer Fresher – Fundamentals and Setup Report

## 1. Introduction

This project represents the first phase of the Java Developer Fresher internship. The purpose of this phase is to understand the development environment, install the required tools, create a basic Java application, and establish a version control workflow using Git and GitHub.

## 2. Objective

The main objectives of this task are:

- Install and verify the Java Development Kit.
- Configure the development environment.
- Understand basic Java project organization.
- Create a simple Hello World application.
- Compile and execute a Java program.
- Configure Git for version control.
- Upload the project to GitHub.
- Understand the basic development workflow.

## 3. Development Environment

The following tools were used:

| Tool | Purpose |
|---|---|
| Java JDK 26.0.2 | Java development and compilation |
| Java Compiler | Compiling Java source code |
| Visual Studio Code | Writing and managing source code |
| Git | Version control |
| GitHub | Remote project repository |
| PowerShell | Running development commands |

## 4. Java Installation Verification

The Java installation was checked using:

```bash
java -version
```

The Java compiler was checked using:

```bash
javac -version
```

The installed Java version is:

```text
Java 26.0.2
```

The Java compiler is:

```text
javac 26.0.2
```

Both commands executed successfully, confirming that Java was correctly installed and configured.

## 5. Project Structure

The project follows a simple structure:

```text
Java-Fundamentals-Setup/
│
├── src/
│   └── Main.java
│
├── docs/
│   └── Fundamentals_Setup_Report.md
│
├── screenshots/
│
└── README.md
```

The `src` folder contains the Java source code.

The `docs` folder contains project documentation.

The `screenshots` folder is used to store evidence of the development and setup process.

The `README.md` file provides an overview of the project.

## 6. Hello World Application

The following Java program was created:

```java
public class Main {

    public static void main(String[] args) {

        System.out.println("Hello World!");
        System.out.println("Java Fundamentals Setup");
        System.out.println("Java Developer Fresher Project");
        System.out.println("Environment setup completed successfully.");

    }
}
```

## 7. Compilation

The Java program was compiled using:

```bash
javac src\Main.java
```

No compilation errors were encountered.

## 8. Execution

The compiled Java application was executed using:

```bash
java -cp src Main
```

The output was:

```text
Hello World!
Java Fundamentals Setup
Java Developer Fresher Project
Environment setup completed successfully.
```

This confirms that the Java development environment is working correctly.

## 9. Git Version Control

Git was used to manage the project source code and track changes.

The repository was initialized using:

```bash
git init
```

Project files were added using:

```bash
git add .
```

The initial project version was committed using:

```bash
git commit -m "Complete Java fundamentals setup"
```

## 10. GitHub

The project was uploaded to GitHub to maintain a remote copy of the source code and demonstrate version control skills.

GitHub also provides a professional portfolio location where the project can be reviewed.

## 11. Challenges Faced

During the setup process, the main challenge was understanding the correct Java project structure and verifying that both Java Runtime and Java Compiler commands were available.

This was resolved by checking:

```bash
java -version
javac -version
```

and then creating the required project structure and Java source file.

## 12. Learning Outcomes

This task provided practical experience with:

- Java development environment setup.
- Java source code creation.
- Compilation and execution.
- Basic project organization.
- VS Code.
- PowerShell.
- Git.
- GitHub.
- Documentation.

## 13. Conclusion

The Fundamentals and Setup task was completed successfully. The Java development environment was configured, a Hello World application was created and executed successfully, and the project was prepared for Git and GitHub version control.

This setup provides a strong foundation for the upcoming Java development tasks.