# javadev-cheatsheet
Java development tools on Windows - Cheat Sheet

Development tools

| Tool  | Url  | File |
|-------|------|------|
| [Java JDK 15](#java) | https://jdk.java.net/15/ | openjdk-15_windows-x64_bin.zip 
| [Maven 3](#maven) | http://maven.apache.org/download.cgi | apache-maven-3.6.3-bin.zip
| SoapUI | https://www.soapui.org/downloads/latest-release | [SoapUI-5.6.0-windows-bin.zip](https://s3.amazonaws.com/downloads.eviware/soapuios/5.6.0/SoapUI-5.6.0-windows-bin.zip)
|  [Docker](#java)  | https://hub.docker.com/editions/community/docker-ce-desktop-windows/ |  


## <a name="java"></a> Java JDK 15
Download and unzip in a local directory, example: C:\workspace\applications\java\jdk-15

![](/assets/java-jdkunzipped.png)

Create the environment variable JAVA_HOME. One way to do this is through the control panel app: Edit environment variables for your account:

![](/assets/java-editenvvariables.png)

![](/assets/java-envhome.png)

Add the JAVA_HOME environment variable to the PATH variable:
![](/assets/java-envpath.png)

Open a windows terminal and check the installation, type:
```bash
java -version
```

The result should be like this:
![](/assets/java-verification.png)


## <a name="maven"></a> Maven 3
Download and unzip in a local directory, example: C:\workspace\applications\maven\apache-maven-3.6.3

Create the environment variable MAVEN_HOME and add it to PATH environment variable. One way to do this is through the control panel app: Edit environment variables for your account

![](/assets/java-editenvvariables.png)

![](/assets/maven-envhome.png)

![](/assets/maven-envpath.png)


## <a name="Docker"></a> Docker
Installation details: https://docs.docker.com/docker-for-windows/install/
Requirements:
* Must have administration rights in the computer
* Hyper-V and Containers Windows features must be enabled
* BIOS-level hardware virtualization support must be enabled in the BIOS settings
* Windows 10 64-bit: Pro, Enterprise, or Education (Build 16299 or later)

Enable WSL 2, offers better performance than Hyper-V
https://docs.docker.com/docker-for-windows/install/
