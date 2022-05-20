## Prepare Jmeter Instance

### Pre-Request Softwares
* [Download & Install JDK](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html)
* [Download & extract Jmeter Binaries Zip](https://jmeter.apache.org/download_jmeter.cgi)
* Set environment variable(path) -  Set JAVA_HOME

### Open Jmeter GUI to create Script
* Browse to Jmeter bin folder
  - Window click on - **ApacheJMeter.jar**
  - Linux run command in Terminal - **./jmeter**
* create Simple Script
  - Add **Thread Group** Under **Test Plan**
    - Add **HTTP Request** Sampler
    - Add **View Results Tree** listener
    - Add **Summary Report** Summary Report
![img.png](images/simpleScript.png)    