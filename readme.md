learn for scala
====


dir tree
```
- .idea (IntelliJ files)
- project (plugins and additional settings for sbt)
- src (source files)
    - main (application code)
        - java (Java source files)
        - scala (Scala source files) <-- This is all we need for now
        - scala-2.12 (Scala 2.12 specific files)
    - test (unit tests)
- target (generated files)
- build.sbt (build definition file for sbt)
```


## Run Main

From the Run menu, select Edit configurations

Click the + button and select `SBT Task`.

Name it `Run the program`.

In the Tasks field, type `~run`. The `~` causes SBT to rebuild and rerun the project when you save changes to a file in the project.

Click OK.

On the Run menu. Click Run ‘Run the program’.

In the code, change 75 to 61 and look at the updated output in the console.


## Reference

- [Getting start](https://docs.scala-lang.org/getting-started-intellij-track/building-a-scala-project-with-intellij-and-sbt.html)