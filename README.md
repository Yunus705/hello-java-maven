# ☕ DevOps Internship Task 8 - Java + Maven Build with Jenkins (EC2)

This task demonstrates how to compile and package a simple Java application using **Apache Maven** via **Jenkins Freestyle Job** running on an EC2 instance.

---

## 📌 Objective

- Build a basic Java HelloWorld project using Maven.
- Use Jenkins (installed on AWS EC2) to automate the build.
- Observe a successful `BUILD SUCCESS` message in Jenkins console.

---

## 🧰 Tools & Technologies

- Jenkins (on AWS EC2)
- Java 
- Apache Maven
- Git & GitHub
- EC2 (Ubuntu)

---

## 📁 Project Structure

hello-java-maven/
├── pom.xml
└── src/
    └── main/
        └── java/
            └── HelloWorld.java

---

⚙️ Jenkins Job Configuration

Jenkins Installed on EC2

Global Tool Configuration:

JDK added

Maven added

Freestyle Job Created:

Source Code Management → GitHub repo

Build Step → Invoke top-level Maven targets

Goals: clean package

Build triggered manually.

✅ Expected Output

In Jenkins → Console Output:

[INFO] BUILD SUCCESS