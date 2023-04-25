# Lab Report 2 - Servers and Bugs
## Experimenting with StringServer
Below is my code for StringServer as well as an untouched Server.java file from the Week 2 lab.

![Image](StringServer.png) ![Image](Server-pic.png)

After running and compiling the files, it will tell us we can now visit the site!

![Image](Running-server.png)

Now that we have the link, we want to add a message to the site by using:

`/add-message?s=<string>`
  
* Note: The <, string, and, > in the URL needs to be replaced with an actual string like: "hello" or "goodbye"
  
This means that the full link will be:
> http://localhost:4000/add-message?s=<string>

* Note: In this case, the port number is 4000 so it should be replaced with a different number if a different one is used!
  
Here is an example of adding "Greetings!":

![Image](Greetings-pic.png)
  
1. The methods that are called in my code are *handleRequest* in StringServer.java and within Server.java we have *start* and *handle*
2. 
  
Here is an example of adding "Goodbye":
  
![Image](Goodbye-pic.png)
