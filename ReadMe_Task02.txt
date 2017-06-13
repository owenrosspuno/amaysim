1. Create folder c:\java\
2. Extract the following files on folder created above
   - workspace.zip
   - apache-maven-3.5.0-bin.zip
   - chromedriver.zip

Note:   
directory should look like this   
- c:\java\workspace\
- c:\java\apache-maven-3.5.0-bin\
- c:\java\chromedriver.exe
   
3. Go to workspace\Amaysim
4. Open a command prompt on directory mentioned above
5. type ..\..\apache-maven-3.5.0\bin\mvn test site
6. Test will run and wait until done.
7. Go to workspace\Amaysim\target\site and open surefire-report.html
