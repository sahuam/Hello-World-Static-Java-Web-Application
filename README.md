# Hello-World-Static-Java-Web-Application

This project is for the newbies who is seeking for an simple example to build a static java web application.

----------------------------------
# Requirements - 
1) Textpad/Notepad++/atom/notepad - Any text editor (recommend Atom)
2) Apache Tomcat - 7/8/9
----------------------------------
# Summary - 
We are trying to build a static web application using simple HTML and CSS code to build our web pages and Apache Tomcat to deploy the web project in local. We are trying to make a clear way to understand the basic process to build a static web project, which could help you to make your own project.


# Steps to follow -
Before starting i hope you have the basic about HTML, CSS and Apache Web server/Apache tomcat. If not, the very first step is <b>GO AND LEARN...!!</b>  

<b>Step 1 - Creating Static Web Project.</b></br>
We have to create a base folder/directory for our project. In this we have create a folder named HelloWorld. So basically HelloWorld is my projet name.</br></br>
You can follow the below structure for creating your full project directory. </br>

          HelloWorld/
          |
          |--->css/
          |     |
          |     |--->style.css
          |
          |--->WEB-INF/
          |     |
          |     |--->web.xml (optional) 
          |
          |--->home.html
          |
          |--->welcome.html
          |
          |--->index.html 

<b>Step 2 - Deploying HelloWorld Project in Apache Tomcat.</b></br>
<i>Note : If tomcat is not install in your system. Click here to visit the website to download --> <a href="https://tomcat.apache.org/download-90.cgi">Apache Tomcat 9</a>.</i></br>

After installation check the install direcorty path. For example I am taking the install directory path as "C:\Program Files\Apache Software Foundation\Tomcat 9.0"</br>

Copy the project folder HelloWorld in "<tomcat-install-dir>/webapps/" directory. </br>
Open cmd(command prompt) on your system and follow the below steps - </br>
          - to go to the bin folder of tomcat type : <b>cd "C:\Program Files\Apache Software Foundation\Tomcat 9.0\bin"</b></br>
          - For starting tomcat type : <b>startup.bat</b> 

<i>Note : To stop apache tomact type on cmd "shutdown.bat"</i></br>

<b>Step 3 - Check your website on your local</b></br>
Open a browser and use this url <b>"http://localhost:8080/HelloWorld/"</b>.</br>
<i>Note : The above URL will direct to the <b>index.html</b> that we have created in our HelloWorld Project and this is a thing that tomcat has set bydefault in a file called web.xml.</i></br>
If you want to see <b>home.html</b> then you have to use <b>"http://localhost:8080/HelloWorld/home.html"</b>.</br>
If you want your home page should come up automatically just like index page then we need to make some changes in web.xml of our project.</br>
