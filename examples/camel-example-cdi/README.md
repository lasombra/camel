# CDI Example

### Introduction

This example shows how to work with Camel using CDI to configure components,
endpoints and beans.

A timer triggers a Camel route to run every 5th second which creates a message that is logged to the console.

### Build

You will need to compile this example first:
  
	mvn compile

### Run

To run the example type
  
	mvn camel:run
  
You can see the routing rules by looking at the java code in the
  `src/main/java` directory

  To stop the example hit `ctrl + c`
  
When we launch the example using the camel maven plugin, a local CDI container
is created and started.

### Forum, Help, etc 

If you hit an problems please let us know on the Camel Forums
  [http://camel.apache.org/discussion-forums.html](http://camel.apache.org/discussion-forums.html)

Please help us make Apache Camel better - we appreciate any feedback you may
have.  Enjoy!

------------------------
The Camel riders!
