# Getting started 
## System configuration
### On windows

#### Install jdk 8

 - Go to http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
 - Select "Accept License Agreement" radio button below "Java SE Development Kit 8u102" text
 - Click on jdk-8u102-windows-x64.exe
 - When download is finished go to c:\Users\\[your usename]\Downloads\ and double click on jdk-8u102-windows-x64.exe file
 - Click Next -> Next until installation is finished
 
#### Install idea

 - Go to https://www.jetbrains.com/idea/download/#section=windows
 - Click on download button which is located below "Community" 
 - When download is finished go to c:\Users\\[your usename]\Downloads\ and double click on ideaIC-2016.2.5.exe file
 - Click Next -> Next until installation is finished

#### Install git bash
 
 - Go to https://git-scm.com/download/win
 - When download is finished go to c:\Users\\[your usename]\Downloads\ and double click on Git-2.10.1-64-bit.exe file 
 - Click Next -> Next until installation is finished 
 
### On ubuntu/debian

#### Install java

Open a terminal and execute next commands:

 - sudo apt-get install -y software-properties-common 
 - sudo add-apt-repository -y ppa:webupd8team/java
 - sudo apt-get update
 - sudo apt-get install -y oracle-java8-installer
 - sudo update-alternatives --display java
 
#### Install idea
  - Go to https://www.jetbrains.com/idea/download/#section=linux
  - Click on download button which is located below "Community" 
  - When download is finished open a terminal
  - Execute next commands: 
      - mkdir ~/ide && tar -xvf ~/Downloads/ideaIC-2016.2.5.tar.gz -C ~/ide/
      - cd  ~/ide/idea-IC-162.2228.15/bin
      - ./idea.sh
      - on the open window click in Configure -> Create Desktop Entry and Click Ok.
      - now you can close idea and you will be able to open it from OS start menu

#### Install git

Open a terminal and execute next command:

sudo apt-get install git
# Resources
## For beginners course

http://www.tutorialspoint.com/java/java_tutorial.pdf

https://www.tutorialspoint.com/java8/java8_tutorial.pdf

## For advance course

https://www.tutorialspoint.com/design_pattern/design_pattern_tutorial.pdf
