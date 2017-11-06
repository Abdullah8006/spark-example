spark-examples
==============

## Content

To run the Java example go to the project folder and execute maven test command. Java 8 or above is required.

- **first-example**: Performs a simple word count task. Spark, Maven, Java.
- **streaming-twitter-custom-receiver**: A custom receiver to collect Twitter messages streams. Update resources/twitter4j.properties with your credentials to use it. Spark streaming, Maven, Java, Kryo serializer, Twitter custom receiver.

## How to run

Step 1 - Maven clean and build your project to get a jar file
Step 2 - Use this commnad in your terminal 
    - spark-submit --class org.sparkexample.WordCountTask --master local[2] ./target/first-example-1.0-SNAPSHOT.jar ./input.txt ./output.txt
