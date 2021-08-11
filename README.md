# JerseyDemo

```
9:30 AM 8/11/2021

https://github.com/ashburndev?tab=repositories

https://github.com/ashburndev/simple-service
https://github.com/ashburndev/simple-service-webapp
https://github.com/ashburndev/simple-heroku-webapp

https://www.jetbrains.com/help/idea/creating-and-running-your-first-restful-web-service.html

https://github.com/ashburndev/RestGlassfishHelloWorld

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

C:\LocalApps\eclipse-jee-2021-06-R-win32-x86_64>
C:\LocalApps\eclipse-jee-2021-06-R-win32-x86_64>eclipse.exe

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

https://howtodoinjava.com/jersey/jersey-quickstart-archetype-hello-world-application-example/

C:\Users\David Holberton\eclipse-workspace-2021-06>dir /o:d
 Volume in drive C has no label.
 Volume Serial Number is 4603-A8D3

 Directory of C:\Users\David Holberton\eclipse-workspace-2021-06

08/11/2021  09:39 AM    <DIR>          .metadata
08/11/2021  09:47 AM    <DIR>          ..
08/11/2021  09:47 AM    <DIR>          .
08/11/2021  09:47 AM    <DIR>          JerseyDemo
               0 File(s)              0 bytes
               4 Dir(s)  35,726,983,168 bytes free

C:\Users\David Holberton\eclipse-workspace-2021-06>cd JerseyDemo

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>dir /o:gd
 Volume in drive C has no label.
 Volume Serial Number is 4603-A8D3

 Directory of C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo

08/11/2021  09:47 AM    <DIR>          target
08/11/2021  09:47 AM    <DIR>          ..
08/11/2021  09:47 AM    <DIR>          .
08/11/2021  09:47 AM    <DIR>          src
08/11/2021  09:47 AM    <DIR>          .settings
08/11/2021  09:47 AM             2,300 pom.xml
08/11/2021  09:47 AM             1,350 .classpath
08/11/2021  09:47 AM             1,086 .project
               3 File(s)          4,736 bytes
               5 Dir(s)  35,727,048,704 bytes free

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>tree /a
Folder PATH listing
Volume serial number is 4603-A8D3
C:.
+---.settings
+---src
|   \---main
|       +---java
|       |   \---com
|       |       \---howtodoinjava
|       |           \---demo
|       +---resources
|       \---webapp
|           \---WEB-INF
\---target
    +---classes
    |   \---com
    |       \---howtodoinjava
    |           \---demo
    +---m2e-wtp
    |   \---web-resources
    |       \---META-INF
    |           \---maven
    |               \---com.howtodoinjava
    |                   \---JerseyDemo
    \---test-classes

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>tree /a /f
Folder PATH listing
Volume serial number is 4603-A8D3
C:.
|   .classpath
|   .project
|   pom.xml
|
+---.settings
|       .jsdtscope
|       org.eclipse.core.resources.prefs
|       org.eclipse.jdt.core.prefs
|       org.eclipse.m2e.core.prefs
|       org.eclipse.wst.common.component
|       org.eclipse.wst.common.project.facet.core.xml
|       org.eclipse.wst.jsdt.ui.superType.container
|       org.eclipse.wst.jsdt.ui.superType.name
|       org.eclipse.wst.validation.prefs
|
+---src
|   \---main
|       +---java
|       |   \---com
|       |       \---howtodoinjava
|       |           \---demo
|       |                   MyResource.java
|       |
|       +---resources
|       \---webapp
|           |   index.jsp
|           |
|           \---WEB-INF
|                   web.xml
|
\---target
    +---classes
    |   \---com
    |       \---howtodoinjava
    |           \---demo
    |                   MyResource.class
    |
    +---m2e-wtp
    |   \---web-resources
    |       \---META-INF
    |           \---maven
    |               \---com.howtodoinjava
    |                   \---JerseyDemo
    |                           pom.properties
    |                           pom.xml
    |
    \---test-classes

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git init
Initialized empty Git repository in C:/Users/David Holberton/eclipse-workspace-2021-06/JerseyDemo/.git/

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        pom.xml
        src/

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git add .

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .gitignore
        new file:   pom.xml
        new file:   src/main/java/com/howtodoinjava/demo/MyResource.java
        new file:   src/main/webapp/WEB-INF/web.xml
        new file:   src/main/webapp/index.jsp


C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git commit -a -m "first commit"
[main (root-commit) 60e0e85] first commit
 5 files changed, 149 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 pom.xml
 create mode 100644 src/main/java/com/howtodoinjava/demo/MyResource.java
 create mode 100644 src/main/webapp/WEB-INF/web.xml
 create mode 100644 src/main/webapp/index.jsp

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

https://github.com/ashburndev/JerseyDemo

…or push an existing repository from the command line

git remote add origin git@github.com:ashburndev/JerseyDemo.git
git branch -M main
git push -u origin main

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git remote add origin git@github.com:ashburndev/JerseyDemo.git

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>git push -u origin main
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 8 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (15/15), 2.57 KiB | 527.00 KiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:ashburndev/JerseyDemo.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>mvn dependency:tree
[INFO] Scanning for projects...
[INFO]
[INFO] --------------------< com.howtodoinjava:JerseyDemo >--------------------
[INFO] Building JerseyDemo 0.0.1-SNAPSHOT
[INFO] --------------------------------[ war ]---------------------------------
[INFO]
[INFO] --- maven-dependency-plugin:2.8:tree (default-cli) @ JerseyDemo ---
[INFO] com.howtodoinjava:JerseyDemo:war:0.0.1-SNAPSHOT
[INFO] +- org.glassfish.jersey.containers:jersey-container-servlet-core:jar:2.29.1:compile
[INFO] |  +- org.glassfish.hk2.external:jakarta.inject:jar:2.6.1:compile
[INFO] |  +- org.glassfish.jersey.core:jersey-common:jar:2.29.1:compile
[INFO] |  |  +- jakarta.annotation:jakarta.annotation-api:jar:1.3.5:compile
[INFO] |  |  \- org.glassfish.hk2:osgi-resource-locator:jar:1.0.3:compile
[INFO] |  +- org.glassfish.jersey.core:jersey-server:jar:2.29.1:compile
[INFO] |  |  +- org.glassfish.jersey.core:jersey-client:jar:2.29.1:compile
[INFO] |  |  +- org.glassfish.jersey.media:jersey-media-jaxb:jar:2.29.1:compile
[INFO] |  |  \- jakarta.validation:jakarta.validation-api:jar:2.0.2:compile
[INFO] |  \- jakarta.ws.rs:jakarta.ws.rs-api:jar:2.1.6:compile
[INFO] \- org.glassfish.jersey.inject:jersey-hk2:jar:2.29.1:compile
[INFO]    \- org.glassfish.hk2:hk2-locator:jar:2.6.1:compile
[INFO]       +- org.glassfish.hk2.external:aopalliance-repackaged:jar:2.6.1:compile
[INFO]       +- org.glassfish.hk2:hk2-api:jar:2.6.1:compile
[INFO]       +- org.glassfish.hk2:hk2-utils:jar:2.6.1:compile
[INFO]       \- org.javassist:javassist:jar:3.22.0-CR2:compile
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  3.918 s
[INFO] Finished at: 2021-08-11T10:10:34-04:00
[INFO] ------------------------------------------------------------------------

C:\Users\David Holberton\eclipse-workspace-2021-06\JerseyDemo>
```
