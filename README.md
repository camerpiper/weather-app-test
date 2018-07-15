# weather-app



The app requires you to have Java 1.8 and Maven and Eclipse or IntelliJ installed on your PC

Build / execution 

Clone the project to a directory on your pc - git clone https://github.com/camerpiper/weather-app-test.git    
Import the project to Eclipse (or IntelliJ) as an existing maven project and run update maven project.  
Right mouse click the project in project explorer and select run as JUnit Test.  
In the JUnit configuration set the test class to be RunCukeTest and the runner to be JUnit4.  
Run the tests.

Notes:

The specification states "Most dominant (or current) condition" & "Most dominant (or current) wind speed and direction".  
However looking at the App it is always the current condition that is displayed in the summary.  
I have therefore used the current values in the assertions.  


