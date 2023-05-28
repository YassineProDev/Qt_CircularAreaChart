<div align="center">
  
# Installation
   
</div> 

## Installation of the development environment 

Installe Qt with this link : https://www.qt.io/download-open-source

## Opening and compilation of the project

### Compile with Qt IDE
Open the file "Qt_Self-AssessmentQuiz.pro" with Qt and compile the project.

### Compile manually
 - Add the path to your QMake bin folder to the Windows PATH environment variable by using the following steps:
     - In the Windows search bar, search Edit environment.
     - Choose the Path variable in your User variables and then select Edit.
     - Select New and add the Mingw-w64 destination folder path, and type the path : C:\Qt\6.5.0\mingw_64\bin
     - Select OK to save the updated PATH. You will need to reopen any console windows for the new PATH location to be available.
     
 - Install chocolaty with this link https://chocolatey.org/install or open powershell as administrator and run this command: 
```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

 - Open your terminal and go to the current directory (Qt_Quiz-main). 
 - Type the command
```bash
qmake
```
 - Type the command
```bash
make
```
- Type the command
```bash
.\Self-AssessmentQuiz.exe
```
 - If it doesn't work type
```bash
.\release\Self-AssessmentQuiz.exe
```


<div align="center"> 
  
  
# Presentation

## Here is the interface with the question and the possible answers as well as the percentage of correct answer
  
![1](https://github.com/YassineProDev/Qt_CircularAreaChart/assets/120946916/12217039-b34e-4079-a172-c1f302835b22)

## if your answer is correct you will get the message "correct".
  
![2](https://github.com/YassineProDev/Qt_CircularAreaChart/assets/120946916/f8a872b0-af15-4111-b633-b933447feb47)


## If your answer is wrong the correct answer will be given.


![3](https://github.com/YassineProDev/Qt_CircularAreaChart/assets/120946916/5fc3303c-4838-4cc0-a43c-484c6a08dc71)

</div>

