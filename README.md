# Starter Project for the Entelect TDD Code Retreat

Clone this repo to your local environment:
```shell
git clone git@github.com:ndonnan/tdd-retreat.git
```
Navigate into the directory and verify that the sample JUnit 5 test runs and fails using maven:
```shell
cd tdd-retreat
mvn clean test
```
Output should look similar to the following:
```
[INFO] Scanning for projects...
[INFO]
[INFO] ---------------------< za.co.entelect:tdd-retreat >---------------------
[INFO] Building tdd-retreat 1.0-SNAPSHOT
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ tdd-retreat ---
[INFO]
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ tdd-retreat ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\Users\neal.donnan\Projects\test\tdd-retreat\src\main\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:compile (default-compile) @ tdd-retreat ---
[INFO] Nothing to compile - all classes are up to date
[INFO]
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ tdd-retreat ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] skip non existing resourceDirectory C:\Users\neal.donnan\Projects\test\tdd-retreat\src\test\resources
[INFO]
[INFO] --- maven-compiler-plugin:3.1:testCompile (default-testCompile) @ tdd-retreat ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to C:\Users\neal.donnan\Projects\test\tdd-retreat\target\test-classes
[INFO]
[INFO] --- maven-surefire-plugin:2.22.2:test (default-test) @ tdd-retreat ---
[INFO]
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running za.co.entelect.tddretreat.GameOfLifeTest
[ERROR] Tests run: 1, Failures: 1, Errors: 0, Skipped: 0, Time elapsed: 0.04 s <<< FAILURE! - in za.co.entelect.tddretreat.GameOfLifeTest
[ERROR] test  Time elapsed: 0.034 s  <<< FAILURE!
org.opentest4j.AssertionFailedError: expected: <1> but was: <2>
        at za.co.entelect.tddretreat.GameOfLifeTest.test(GameOfLifeTest.java:11)

[INFO]
[INFO] Results:
[INFO]
[ERROR] Failures:
[ERROR]   GameOfLifeTest.test:11 expected: <1> but was: <2>
[INFO]
[ERROR] Tests run: 1, Failures: 1, Errors: 0, Skipped: 0
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  3.408 s
[INFO] Finished at: 2022-01-25T09:33:59+02:00
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-surefire-plugin:2.22.2:test (default-test) on project tdd-retreat: There are test failures.
[ERROR]
[ERROR] Please refer to C:\Users\neal.donnan\Projects\test\tdd-retreat\target\surefire-reports for the individual test results.
[ERROR] Please refer to dump files (if any exist) [date].dump, [date]-jvmRun[N].dump and [date].dumpstream.
[ERROR] -> [Help 1]
[ERROR]
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR]
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException

```
You can now open the project in IntelliJ IDEA and begin the exercises!
