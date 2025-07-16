# File Manager
A File Manager/Browser with the ability to list/upload/delete files and add/delete directories within a root directory that you can specify either from a <b>Native File System</b> or one of the <b>Cloud Storage</b> Providers(currently configured for Microsoft Azure Storage Account using a File Share). Additionally, the app also demonstrates the integration between <b>CKEditor</b> which is a popular <b>WYSIWYG</b> editor with this file system for browsing files using the File Manager and uploading files and images.



## Tech Stack
1. Angular for the UIX 
2. Spring Boot for the service backend 
3. Bootstrap for styling 
4. Font Awesone for Icons 
5. CKEditor 
6. Maven for buliding, packaging and running the app


## Build & Run the app
The App runs as one single java web application and can be deployed as a war in a container of your choice. The complied Angular UI code resides in <b>src/main/resources/static</b> folder. Because the backend being Spring Boot, the app can be quickly run using the following command on the project root,<br>
<b>mvn spring-boot:run</b><br>

Angular Code is built using the command <b>ng build --prod --base-href</b> . As you may have noted I am removing the base-href upon production build of Angular Code. This is necessary to make sure that the app runs correctly with it's current project structure.
