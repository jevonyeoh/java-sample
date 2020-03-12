# Sample Java Repo

This is a sample repo. Use this to make sure that setting up a Java environment
works properly before the day of your onsite.

This is not an interview question; you will not be evaluated for this.

## Setup steps

1. `git clone` this repo
2. `cd java-sample`
3. `cd samsara-helloworld`
4. Install Java if you do not already have it - any version from Java 8 and up should work for us.

## Getting the test code to run
We'll be using Maven as our package manager.

There are a few suggested steps to getting the repository to run below for reference. However, these are just some guidelines
and it doesn't matter that much whether you follow them to the T.

As long as you are able to run the main function, and the associated test file, you'll be good to go!

### IntelliJ version 2018.3.6
1. Open IntelliJ
2. Click `Import Project`
3. Select this project
4. Select `Import project from external model > Maven`
5. Select your Java project SDK.
6. Open `App.java` and run it.
7. Open `AppTest.java` and run it.


### Eclipse
1. Open Eclipse
2. `File -> Import -> Maven -> Existing Maven Project -> Navigate to folder in browse -> Import`
3. Open `App.java` and run it.
4. Open `AppTest.java` and run it.


### Via the Command Line (Mac)
1. `brew install maven`
2. `mvn compile`
3. `mvn exec:java -Dexec.mainClass="com.samsaratest.app.App"`
4. `mvn test -Dtest=AppTest`

-- 

If the app and test run, you're all set!
