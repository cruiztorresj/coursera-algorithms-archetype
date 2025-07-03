# coursera-algorithms-archetype

Maven Archetype to generate a starter project for the Algorithms Course taught by Robert Sedgewick and Kevin Wayne, available for free in Coursera.

# Using the Archetype
You will need to have `algs4.jar` in your local Maven Repository.

There are some videos I have prepared to assist you in the process.
1. In [this video](https://www.youtube.com/watch?v=_B9-7sjm1Us) you can learn how to use the `jar` tool (Arriving with the JDK) to extract .zip files.
2. In [this video](https://www.youtube.com/watch?v=rF7Ivqe65oA) you see how to install the aforementioned library in your local maven repository, the official code repository for the aforementioned library can be found [here](https://github.com/kevin-wayne/algs4). If you want a shortcut you can use `curl -O https://lift.cs.princeton.edu/java/linux/lift-cli.zip` to download the file containing the .jar file, find `algs4.jar` in the folder `lift/lib/algs4.jar` Once you have extracted the content from `lift-cli.zip`
3. Clone this repository
4. Change directory to the recently cloned repository.
5. Execute `mvn clean install`
6. Execute `mvn archetype:generate -DarchetypeCatalog=local`
7. Follow the instructions, and that's it.
