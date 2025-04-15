# Java and Maven Installation Guide (Windows)

---

## 🔹 Install Java (JDK)

### 1. Download JDK
- Go to the official Oracle JDK download page:  
  [https://www.oracle.com/in/java/technologies/downloads/#jdk24-windows](https://www.oracle.com/in/java/technologies/downloads/#jdk24-windows)

### 2. Install JDK
- Run the downloaded `.exe` file.
- Follow the installation wizard steps to complete the setup.

### 3. Verify Java Installation
- Open Command Prompt and run:
  ```bash
  java -version
You should see Java version output (e.g., java version "24").

4. Set Environment Variables
   a. Set JAVA_HOME
   Open System Properties → Advanced → Environment Variables

Under User Variables and System Variables, click New...

Enter:

Variable name: JAVA_HOME

Variable value: C:\Program Files\Java\jdk-24 (without \bin)

b. Add Java to PATH
Under System Variables, find and edit the Path variable.

Click New and add the following:

%JAVA_HOME%\bin

C:\Program Files\Java\jdk-24\bin

🔹 Install Apache Maven
1. Download Maven
   Visit: https://maven.apache.org/download.cgi

Download the Binary zip archive (e.g., apache-maven-3.9.9-bin.zip)

2. Extract the ZIP
   Extract the archive to your preferred location, for example:
   E:\Java\apache-maven-3.9.9

3. Set MAVEN_HOME
   Open System Properties → Advanced → Environment Variables

Under User Variables and System Variables, click New...

Enter:

Variable name: MAVEN_HOME

Variable value: E:\Java\apache-maven-3.9.9

4. Add Maven to PATH
   Under System Variables, find and edit the Path variable.

Click New and add the following:

%MAVEN_HOME%\bin

E:\Java\apache-maven-3.9.9\bin

✅ Final Check
Open a new Command Prompt window

Type:

bash
Copy
Edit
mvn -v
You should see Maven version and Java version info displayed.

vbnet
Copy
Edit





