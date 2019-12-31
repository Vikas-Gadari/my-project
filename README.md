# my-project

Login github
Create new repositories-name-myproject
Click initialize with a readme
Public
Copy repository address

Eclipse
New workspace
Windows-show views-others-git repository-clone a git repository 
-paste -user - password - next - finish

New - other - maven project - next 
Click create simple maven project
Group I'd - com. Vikas
Article I'd - app1
Packaging- war
Name- app1
Description- sample app
Finish

Pom. Xml
<properties>
<maven.compiler.source>1.8<>
<maven.compiler.target>1.8<>
</properties>
App1-right click-maven-update maven-ok

App1-java ee tools -generate deployment descriptor stub

Create served
Project-app1
Source folder- \app\src\main\java
Java package- com. Vikas
Class name - MyServlet
Next- url mapping - /MyServlet
Edit - /index.html-ok
Next- right ✔ doget ❌ dopost
Ok

Mvnrepository. Com
Serlet api
3.0
Maven copy
Pom. Xml
</properties>
<dependencies>
Paste
</dependencies>
Ctrl save

Delete src main java app1 package

App1- right click - team - share project - repository - click bottom path - finish
App1- right click - team - commit - Instage to staged
Commit messege - starter project- commit and push
Close eclipse

Change pom. Xml path
Cmd- cd downloads
java -jar jenkins. war
Localhost:8080

Create
New item - item name -app1
Description - app1
Source code management - git
Repository url - my project link copy and paste
Add Jenkins - username
Pass
I'd - GitCredentials
Add
Credentials- select bottom

Build triggers - poll scm - H/2 ****

Build - invoke top level maven targets
Maven version - H3
Goals- advanced
Goals - package
Pom - app1/pom.xml
Save
Build now
