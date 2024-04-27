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

# Q6 

## EMAIL FROM ALEX

Hi, Alex.

My name is Mikaere, not only is this something i could do for you, i would love to design the Super Awesome Museum a functional and beautiful Website to display the amazing artifacts, objects and paraphenalia that your Museum has to display.

It's perfectly okay that you don't know much about websites as that's what I'm here for!
Firstly I'd like to do up some basic design plans for the website, in the biz we call them wireframes. That will essentially show what the end layout and design will look like taking into account, colors, picture locations, links to contact information aswell as the address to the venue. But the wireframe will show what each page will look like to the target audience.

Once everyone is happy with the end design i'll use a few different tools to display the website and add functionality, but through proper use of these tools I'll be able to increase your website traffic, create features that make it easy for not only yourself but your audience to browse and navigate and then of course add links to contact information and venue location so that the audience can find your museum and the Super Awesome Artefacts it holds to view in person.

However I can most certianly start designing some wireframes for your perusal if everything I've explained sounds like it suits your requirements.

I look forward not only to hearing back from you, but working with you to display your Super Awesome Museum artefacts. 

Regards, Mikaere

Fullstack Website Developer

# Q7

## Reflection

### Description of Project

The project i undertook was designing a webpage that would display some personal 
information about myself and what i do. It was a Profile webpage with minimum 4 HTML pages detailing a personal about me
a professional about me which had a resume attached, some blog posts that i made and pages/links to them a contact page that would connect you to all
my socials and lastly the CSS page filled with layouts and design of the webpage. 
I was also required to do up a sitemap and wireframe for the website to present to the audience and essentially explain the concept of the webpage
as well as the design and layout choice i made within it.

### Feelings and Future Plan

While i was designing the webpage I made multiple layout changes, but ultimately abondened them, which honestly was not the best decision as it left me quite time short. 
In retrospect i would carry out the same process but spend alot more time in the designing of the wireframes and sitemap portion of the project, as the time used there
to really hash out and perfect the layout would have been a better way to spend the time i otherwise spent completely redesigning and then coding other designs just to abandon them.
I was pretty happy with the "coding" of the webpage although, again, i believe a more detailed and indepth design process with the wireframe and sitemap would have definitely allowed me to
really set my webpage apart from the rest. So ultimately i wasn't "happy" with the webpages design/layout and styling but considering the time constraints and the level of knowledge of
the process I'm glad i made the mistakes i did, as now I have a very distinct and clear path for improvement in future projects.


# Q8

[Action Plan Q8](</ActionPlan PDF/Q8 Action Plan.pdf>)
Please open Action plan document to view.

# Q9

## Language Learning Techologies

### The uses of Language Learning Technologies

One of the many uses of language learning technologies is it can be used to create outlines and framework for all types of projects. For example it can create outlines for technical reports it can produce documents for coding softwares and a whole lot more.
Language learning technologies can also translate one language to another which is highly useful for large companies that perhaps have many different ethnicity employees working on the same projects as each other.
Chat gpt and other language learning technologies can also be used to spell check and check grammar, which is highly useful for vital documents or communications that need to convey the information properly and in a professional manner.
Language learning technologies are also incredibly good for finding and documenting different types of information, they can write code that a developer can then build ontop of and ultimately this can cut down the amount of time it can take to get certain aspects of a project started or even completed.
Language models are incredibly good at collection different information from different research articles and studies plus all of the content that is related to it from the internet itself.
Another great use for language learning technologies is it can really help with projects that require collaboration of different languages, as stated above it can translate the information being collect and output it to the user in a interface that can then be viewed and used by those it is required by.

# Q10
 
 ## Language Learning Technologies

 ### Legal and Ethical Impacts 

 When it comes to the ethical nature of using language learning technologies for code generation purposes it is important to understand and do your own research on whether or not the code you're using infringes on any copyrights or trademarks that may have been used by someone else. 
 Another ethical impact of language learning technologies is that they can take an authors words and phrase them basically identicle which can lead to plagerism, so it is highly important that if a language program is used that you refrence the proper authors and even the language technology that youre using.
 Another very large concern that is often under the limelight is the issue of privacy, as AI learning models and programs require access to alot of information, some of which may or may not be private which can become a very large concern if the sensitive information isnt handled how it should be.
 Due to the fact that information through the AIs research and collection is not balanced the AI and language models cant determine whether or not they're documenting and presenting bias in some situations, it's also high likely and most probable that the information given can lean towards and favour one side of an argument over another, making the information recieved anywhere from moderately bias to highly bias.

So in conclusion using language models and AI like chatGPT can be incredibly benefical but also quite determental if not used correctly, under strict guidelines/personal accountability and research. The importance of understanding that the software is provided to be an additive to the enviroment of coding and other tasks and not the replacement. Sort of like why would you replace eating delicious full course meals with drinking supplements and taking pills to meet nutritional requirements?
When used properly and responsibly these softwares are a supplement in the world, that can build upon and improve that which is already there serving as the "meat and potatoes".

# Q11

## Soft and Hard Skills Useful to software developing 

### Soft Skills:

Communication in the software development space is crucial, and it is rather important to be able to communicate the goals, designs and implementations of the software being developed. But having skills in communicating with colleuges and clients is very important as it keeps the process running smoothly aswell as fixing, improving and maintaining the project/s not only in its infancy but into its launched state.

Linking closely with communication and as it may of slightly been touched on, TeamWork is another crucial soft skill in program development as more often than not you as a programmer/developer will be working in a team enviroment where multiple groups of people and then singular people within groups will be given tasks to complete or alternatively need to monitor their own task work, and if communication to the team is poor in this particular instance time can be wasted due to things being done twice or completely missed because the start/during and end of the task was not communicated effectievly.

Adaptability is a important softskill within programming as the likelihood that projects will always be using the programming language or tech frameworks/platforms that you are familliar, isnt always guarantted. Which may require you and even team memmbers to become more versatile and adapt to the software/languages specified.

The ability to problem solve as a developer is easily one of the most important soft skills. You could have all of the coding ability, team work and leading capabilties but ultimately if you and yoru team cannot problem solve through analyzation of the issue, debug the issue or even make the program more responsive and performative all while being in an enviroment that is controlled by external factors often related to time and launch dates.

Before moving from soft skills to hard skills the final soft skill that is important is scheduling. Or as its typically worded TIME MANAGEMENT. Time management is very important as, if the team and or the dev for certain project/s is missing all the due dates, not communicating through missing meetings and always run off their feet trying to catch up because they don't manage their time correctly and effectively then all within the scope of the project suffer. The client won't recieve their product when specified, the team won't recieve the information used to build strategies and or debug improve or adapt to situations and ultimately all this will lead to a poor product delivery, if delivered atall. Which then hurts the potential of more work and under takings within the space of Technology.

### Hard Skills:

So whether or not it's obvious having program language literacy is not only very important but a hard skill. being able to code in complier languages and interateable languages is important, but its also important that the developer understand how the code is to be structured and what best practice is within the lanuague being used.

While being well versed in programming languages is a important hard skill to have, being able to use Development Frameworks like React, Django and the likes can be very beneficial as it can supply alot of reusable features for coding in certain languages through pre defined structures within the software.

The ability to use Versio control systems is another essential hard skill, as being competent in git is crucial to being able to be useful in a large scale project with teammates aswell as serving as a great way to store projects safely outside of a local device. So being able to use cloud software and collabrative software is very crucial to the longevity and ease of development in a software project.

Being able to use Databases to manage information is another hard sill that is required by developers. It's important that the developer can use these softwares so applications that are specifically used for data collection/use and security can be implemented to increase the software being made/projects quality and performance. A few examples if Database management softwares are SQL, NoSQL, MySQL and DevOps.

Finally testing and debugging is a highly important hard skill for developers. As it is very unlikely if not mere' impossible that a developer/coder/language enthusiast won't encounter bugs, errors and performance issues. Being able to compentently engauge in and use debuggers to accurately determine the cause of the bug or see step by step what is decreasing performance is vital to project creation. 

In conclusion the combination of soft and hard skills is an important and highly valued ability. 
As with enough experience and the afformentioned a single developer can become quite a potent and well oiled cog in the space of software develpoment and technology. 

