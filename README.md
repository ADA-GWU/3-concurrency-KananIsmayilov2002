# Concurrency
## Overview
This task includes image processing and usage of multiple threads in order to pixelize the provided image. The application has 2 modes 'S' and 'M', single and multi-threading. The pixelization process is done in 2 modes according to the running mode:

- **Single-threaded**: Processing is done left to right, top to bottom.
- **Multi-threaded**: The image is divided into *n* horizontal strips (where *n* is the number of available threads), and each strip is processed from left to right.

## Prerequisites
Codes in this repository was written in Java language. For using application, Java should be installed in the system. Following  steps is necessary for running the codes.

Installing Java
For running codes written in Java, Java Development Kit should be installed.

https://www.oracle.com/java/technologies/downloads/#jdk21-windows

After installation, open the terminal and run the command "javac -version", If you can see the Java version, everything is ok.
## Instructions

**Clone Repository**:
```
git clone https://github.com/ADA-GWU/3-concurrency-KananIsmayilov2002.git
```

**Run the Application** 

Open the corresponding folder path in your terminal and compile Java files using:
```
javac Main.java
```
Input format should be: java Main.java "filename" "square size" "processing mode". For example
```
java Main images\nature.png 20 M
```
## Result

![image](https://github.com/user-attachments/assets/0e592199-fe03-40b6-aa2c-f8c1cc789556)   ![result](https://github.com/user-attachments/assets/ad0f6f9c-c8ba-4985-bde5-56b8a704955a)









