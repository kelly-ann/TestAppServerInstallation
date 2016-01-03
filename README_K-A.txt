This project's purpose is to test a particular server instance that has been setup.

To setup:
FIRST:
Window --> Preferences --> Type "jdk" --> Click on "Compiler" and "JRE environment" (respectively) and 
make sure they are appropriately set.

SECOND:
In the Servers tap right click and click "New" --> Select your server --> setup run config.

THIRD:
Make sure the server can start up and shutdown, via right-clicking on it and clicking "Start" and "Stop" 
(respectively).


To test the entire installation:

FIRST:
In this TestAppServerInstallation project right-click on the "WebContent" folder and create a new file 
named "hello.jsp".

SECOND:
Go to the "WebContent" folder --> right-click on the "hello.jsp" file and 
select "Run as..." --> "Run on Server" --> "Choose an existing server" --> select your server instance 
--> click "Next" --> make sure "TestAppServerInstallation" shows in the "Configured" box on the right
--> click "Finish".

FINALLY:
Your web browser should open up in Eclipse or locally and the contents of the "hello.jsp" page should show.

Done!  :-)

