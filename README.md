# T1A1 Workbook

## Question 1:


### Concepts of Markup Languages

### What is it? 
#### "Put simply"

The main function and concepts for Markup Languages in web development is to act as a tool to take data given by a user (Web Developer) and then display that information onto the internet in a easy to read and structured layout using said languages.

### HTML: 

or Hypertext Markup Language is a markup language used to insert the "actual" content for a webpage to display. HTML does this by having a user (web developer, or that one person who can seemily do everything without ever learning) write in content using special syntax (computer speak) that the Markup Language understands and can then interpret and display on a webpage.

### CSS: 

Or Cascading stylesheet, is also a markup language however CSS is used to make the content displayed through HTML look better. So to expand on "better" CSS deals with the design layout and style aspects of the webpage, taking that barebones frame HTML makes and then improving on it to look more structured aswell as smoother to navigate.

### Accessibility: 

Accessability in web design is also a important component allowing for a screen reader (through using semantic tags) to interpret the information on the page and present it to the user. Proper and well done semantic tagging can allow for the user to navigate through the use of their keyboard, visually or through the use of audio.

### Search Engine Optimization:

Lastly we as the Web Designer can use techniques to increase our traffic on the website via Search Engine Optimization. Which through the use of meta tags and semantic tags can give the remote host the information required to display the content of the webpage being searched for to the user (local computer/tablet etc) but at a higher rate than a webpage without. Semantic tags aswell as providing user aids can also help give the content in the page importance or "hirarchy" so to speak, if its wrtten correctly which in turn can improve our pages search engine rankings thus improving traffic to said website.

# Q2

### Packets:

A packet or packets. are essentially a bundle of data sent over the internet in either small pieces or in one larger piece (packet) each packet will have a destination to where its going aswell as a message within itself. 

Packets are important as breaking down the pieces of data can greatly increase the speed at which the information is send and recieved. for example rather than recieving one large box from a courier service think of it as recieving lots of smaller packets making the delivery of informaiton smoother. 


### IP Addresses:

A IP address in laymans terms is a number that represents a certain address which every device connected to the internet will have. IPv4 and IPv6 are different versions of these numbers

Its important that every device have a certain number as it allows computers and other devices to find each other with ease. Sort of like how you and a family memeber have names, if you're ever looking for each other in a room and you yell out each others names you make it clear who you are looking for and where you/they are.

### Routers and Routing:

Routers basically control the path each of the packets take to reach their end goal.

This is important as it makes sure the packet of information takes the best route to reach their destination without getting lost or stuck with other packets in traffic.

### Domains and DNS (Domain Name System):

Domains are the location the packet is coming to or being send from, one example of a domain would be google.com
DNS is like is like a list of unique names and numbers (IP addresses) that computers understand.

Domain and DNS make it easier for the user to search for a webpage they're looking for as rather than entering a bunch of unqiue numbers the user can enter a domain name and the DNS quickly helps to find the Domain under that number so we can visit it.

All of these different technologies and their features work together in harmony to make it smoother and easier for the user to navigate the internet and the information they are looking for.

# Q3

### TCP

TCP or transmission control protocol just like UDP TCP holds information about the IP/port and checksum aswell other more fancy features. TCP unlike UDP has a labelling system for each packet that allows the packets to be sent and received in different order than what they arrive due to the fact that your computers operating system will receive the packets and then order them sequentially through the unique numbering TCP uses eg (1,2,3,4).
Also, once the computer receives a packet using TCP, the reciever will send back an acknowledgement to let the sender transmit the next packet, if enough time ticks without the receiver sending a acknowledgement the sender will send another identical packet that it didnt receive an ack for. It also doesnt matter if the receive did get the packet as if it did and it receive another identical packet from the sender the receiver will just discard the extra packet. Lastly TCP can send and receive mulitple packets and acks at once, which increases speed as you dont have to wait for acks to return. 

## HTTP and HTTPS

Http and https are protocols used to sending and reciving data over the internet. HTTP is unencrypted and https is encrypted. To explain encryption simply non encryted data can be things like photos and text to a blog post and encrypted data is things like passwords, credit cards and senstive/personal information that needs to be protected.

HTTP and HTTPS are the spinal system to the internet, they hold the body of the internet upright allowing for messages to be sent all over the internet using send and receive requests which leads to the transfer of data and information from remote and local servers to each other.

### Web Browsers (Requests, rendering and developer tools)

#### Web Broswer Request:

A Web Browser request is as simple as it sounds. A web browser will send a request to a web server which will in turn transfer back data to the server which contains the webpage requested and the data attached to said webpage.

#### Rendering:

Web browsers will receive the information from the server through the request and then begin to render in the information provided using the markup languages and programming languages that were used to create the content the page holds. This information is often held in HTML CSS and JavaScript but there could also be other languages being rendered in place of those, however those are the typical standard.

#### Developer Tools

Most if not all web browsers come with developer tools, these tools allow the developer (but ultimately anyone with the know how) to see what happens behind all the pretty front end of the webpage. Developer tools also allow the dev to tinker with the content of the page (although no permanent changes can be made in the DevTools), debug the page and also monitor the network. All this can lead to a smoother faster and more enjoyable experience to then end user.

#### Conclusion

In conclusion, all of these technologies work together to ensure that you as the user have the best and smoothest experience possible while always remaining safe while browsing or even creating new content on the web.

# Q4

## Interpreters and Compilers

interpreters and compilers are both processes used to translate our regular english language into machine code, which is fancy for interpreters and compilers turn "hello there" into a series of zeros and ones that a computer can understand and then output aslong as there are no errors.

There are a few differeces between a interpreters and compilers, the first difference is interpreters will iterate through the code line by line and execute/translate each line then return to the start and repeat the process which can be quite slow. Compilers on the other hand will translate all the code then it will return/execute it, which is much faster than what the interpreter does.

However, Interpreters while being slow, often are better at debugging issues as it will return the error and stop executing code at the error, compilers on the other hand will give the user better performance and optimisations. Interpreters are also more portable as you often don't, unlike compilers, need specific platforms to support the running enviroment. eg (mac to windows require recompilation to be transferred between enviroments)

lastly Interpreters can and often are installed onto the system but compilers are not. Compilers will and can be used standalone or used in "bytecode" giving them the ability to be executed indepedently. 


# Q5

## Programming Languages

### C++ Programming language

The benefits of C++ 

High performance, which allows for the user to optimize the code for speed and memory usage. Control is also another benefit of C++ allowing the user to have high control over the systems resources and hardware. C++ is also quite flexible allowing it to be used for many different applications in coding.
C++ can be considered portable although it isnt its main strength, its ability to write code for mulitple platforms makes it quite easy for it to be implemented over various platforms with very few changes needed.
Lastly c++ comes with a rather large and extensive library that provides all sorts of useful tools for the user, Be it data structures, algorithms and utilities.

Drawbacks

Some of the draws backs of C++ are, it is a rather complex language to learn so the time investment required can be very overwhelming for some.
Memory management  in C++ if not done correctly can also be quite dangerous to the user as it can cause memory leaks and losses.
C++ can also, compared to other languages, have a long creative process for the given project being worked on compared to other programming languages. If its not done correctly safety can and will be a rather large concern for the user/s as it can create corruptions issues and errors when things really go wrong from poor design and management.

### Python Programming Language

Benefits

One of Pythons benefits are its ease of learning. Being designed to be easily picked up and learnt python allows the user to deal with solving the problems of the projects rather than having to deal with the problems of syntax and programming within the code itself.
Python also has a rather large Library for the user to pull from which makes it useful in many different project enviroments be it data science, machine learning and to name another webpage functionality.
Python is also quite portable, as it can be written on multiple different OS systems/platforms making it quite a versatile and easing possible transfer of data over different platforms.
Since python is not only easy to use but highly portable that means that another benefit of the programming language is that it can be incredibly fast and easy to develop and integrate software designed with it (Python) to end use situations, an example of those situations are webpages, an ai like chatgpt to name just a few.
Another bonus to Python is it has a rather large community, meaning there's multiple recourses that can help you solve complex issues that may arise quicker than a more niche programming language, also the larger community can contribute to better collaberations/ease of collaboration for any project that may be undertaken using the language.

Drawbacks

Some of the drawbacks of python are that at the cost of higher productivity and ease of use it sacrifices performance compared to lower level languages like C++ as being a interpreter language it will be alot slower than a compiler language like C++.
Since Python also has a Global Interpreter Lock, it is unable to execute multiple lines of code in one process, which mighten sound like much but it effecitevly means it can bottleneck the interpreter for applications that require more performance.
Another drawback to Python is that due to the way it translates the code written by the user it can have run time errors and type errors which can then make debugging a little bit more difficults, especially in much larger projects.
While Python with the help of some other programs can develop mobile applications it's not its common or intended purpose as it requires the afformentioned dependencies to develop software on a mobile device, so this makes it mildly less portable in todays day and age with alot of things now being done with mobiles or tablets.
Python applications can also be quite difficult to put together and then finalise into their entended end user enviroment due to the fact that Python itself requires alot of dependencies to format the code for multiple systems/OS, which can make deployment quite tendious or difficult for large projects.

