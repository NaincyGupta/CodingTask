# CodingTask
GitHub Coding Task

# Files
> The Main file is **MostActiveCookie.java**

> The Test file is **MostActiveCookieTest.java**


# Setup
> Clone repository

> git clone https://github.com/NaincyGupta/CodingTask.git

# Run Program using Command-line Instructions
  ## Prerequisites:
>Install the latest version of Java.

>You may need to set your JAVA_HOME.

# Run the program
  ## (In Windows)
> cd CodingTask\QuantcastGithubProject\src\com\quantcast

> javac -cp "commons-cli-1.5.0.jar;commons-cli-1.5.0-javadoc.jar;commons-cli-1.5.0-sources.jar;commons-cli-1.5.0-tests.jar;commons-cli-1.5.0-test-sources.jar"  MostActiveCookie.java

>java -cp "commons-cli-1.5.0.jar;commons-cli-1.5.0-javadoc.jar;commons-cli-1.5.0-sources.jar;commons-cli-1.5.0-tests.jar;commons-cli-1.5.0-test-sources.jar" MostActiveCookie.java cookieData.csv -d 2018-12-09

  ## (In Mac)
> cd CodingTask/QuantcastGithubProject/src/com/quantcast

> javac -cp commons-cli-1.5.0.jar:commons-cli-1.5.0-javadoc.jar:commons-cli-1.5.0-sources.jar:commons-cli-1.5.0-tests.jar:commons-cli-1.5.0-test-sources.jar MostActiveCookie.java

> java -cp commons-cli-1.5.0.jar:commons-cli-1.5.0-javadoc.jar:commons-cli-1.5.0-sources.jar:commons-cli-1.5.0-tests.jar:commons-cli-1.5.0-test-sources.jar MostActiveCookie cookieData.csv -d 2018-12-09

  ## (General)
> java -cp commons-cli-1.5.0.jar:commons-cli-1.5.0-javadoc.jar:commons-cli-1.5.0-sources.jar:commons-cli-1.5.0-tests.jar:commons-cli-1.5.0-test-sources.jar *JavaFilePath* *CSV file path* -d *Input date*

  # Test Program using Eclipse
## Run the JUnit tests
  
> Open the cloned Project - QuantcastGithubProject
  
> Open Eclipse > Import Project QuantcastGithubProject
  
> Right-click on MostActiveCookieTest.java
  
> Run As > Junit Test

# Additional Information
  
> I have used apache.commons.cli library to use “-d” as parameter to enter date in command line.
  
> The above command line adds the class path of external libraries , takes cookieData.csv as 1st argument and input date as “-d ” parameter.
  
> Junit tests are added to MostActiveCookieTest.java
  
> The program has been designed such that an exception will be thrown in the following cases:
  
-	If the input CSV file path passed in the argument cannot be located at specified location
  
-	If the input CSV file path is not added as argument in the command line.
  
-	If input date is not passed as “-d” parameter.
  
-	If the input date entered is not in the correct format i.e. yyyy-MM-dd .


# Screenshot of successful execution of program: 
![image](https://user-images.githubusercontent.com/46656310/147737934-50427820-9ab7-4a9c-b6eb-e4d5644b8acf.png)



![image](https://user-images.githubusercontent.com/46656310/147737951-1e826597-e1e6-483e-9f14-28d00e30967c.png)

