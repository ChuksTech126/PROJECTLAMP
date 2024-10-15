***
* THE       SOFTWARE    DEVELOPMENT        LIFE     CYCLE

**According to Amazon Web Service,** The software development lifecycle (SDLC) is the cost-effective(low expensive) and time-efficient(less time comsumption) process that development teams use to design and build high-quality software

**Simply put,** Software development life cycle (SDLC) is the term used in the software industry to describe the process for creating a new software product. Software developers use this as a guide to ensure software is produced with the lowest cost and highest possible quality in the shortest amount of time.

***BENEFITS OF SDLC***

 *Increased visibility of the development process for all stakeholders involved*

 _Efficient estimation, planning, and scheduling_

 _Improved risk management and cost estimation_

 _Systematic software delivery and better customer satisfaction_


***7 STAGES OF THE SOFTWARE DEVELOPMENT LIFE CYCLE***


1. **Plan and brainstorm**
:  The first step in the software development life cycle is planning. It's when you gather the team to brainstorm, set goals, and identify risks. At this stage, the team will work together to devise a set of business goals, requirements, specifications, and any high-level risks that might hinder the project's success

1. **Analyze requirements**:
Once you've come up with some ideas, it's time to organize them into a cohesive plan and design. This requires a lot of research and planning to ensure that your final product meets your expectations (and those of your customers). The big step is creating a detailed project plan document and work breakdown structure that outlines the requirements.

1. **Design the mockups**:
Once you've got your design plans in front of you, it's time for wireframing and mockups. This step builds upon the planning stage, building out the tasks you need to do in the work breakdown schedule. There are plenty of tools available, such as Adobe XD or InVision, that make this process much easier than ever before.

1. **Develop the code**:
The development phase is where coding begins to take place. It is one of the most time-consuming phases in the SDLC. This phase often requires extensive programming skills and knowledge of databases. The team will build functionality for the product or service, which includes creating a user interface and building the database so users can store information in your system.

1. **Test the product**:
Before releasing the mockups into final production, you'll need to test it to ensure it is free of bugs and errors. Any issues need to be fixed before moving forward with deployment. You'll also need to manage how the system will integrate into existing systems, software, and processes.

1. **Implement and launch the product**:
Once you've completed all testing phases, it's time to deploy your new application for customers to use. After deployment, the launch may involve marketing your new product or service so people know about its existence. If the software is in-house, it may mean implementing the change management process to ensure user training and acceptance.

1. **Set up maintenance and operations**:  The final stage of the software development life cycle is maintenance and operations. This is one of the most critical stages because it's when your hard work gets put to the test.  
Maintenance involves updating an existing software product to fix bugs and ensure reliability. It can also include adding new features or functionality to a current product. Operations refer to the day-to-day running of a software product or service, such as performing backups and other administrative tasks.

___
___
*  THE LAMP STACK UNDERSTANDING

The ***LAMP*** stack is a popular open source software stack for building and deploying web applications. LAMP is an acronym for the components in the stack: **Linux (operating system), Apache (HTTP server), MySQL (database) and PHP, Perl or Python (programming language**).

**LAMP stack components**
LAMP stands for Linux, Apache, MySQL, and PHP. Together, they provide a proven set of software for delivering high-performance web applications. Each component contributes essential capabilities to the stack:

***Linux: The operating system.*** Linux is a free and open source operating system (OS) that has been around since the mid-1990s. Today, it has an extensive worldwide user base that extends across industries. Linux is popular in part because it offers more flexibility and configuration options than some other operating systems.

***Apache: The web server.*** The Apache web server processes requests and serves up web assets via HTTP so that the application is accessible to anyone in the public domain over a simple web URL. Developed and maintained by an open community, Apache is a mature, feature-rich server that runs a large share of the websites currently on the internet. 

***MySQL: The database.*** MySQL is an open source relational database management system for storing application data. With My SQL, you can store all your information in a format that is easily queried with the SQL language. SQL is a great choice if you are dealing with a business domain that is well structured, and you want to translate that structure into the backend. MySQL is suitable for running even large and complex sites. 

***PHP: The programming language.*** The PHP open source scripting language works with Apache to help you create dynamic web pages. You cannot use HTML to perform dynamic processes such as pulling data out of a database. To provide this type of functionality, you simply drop PHP code into the parts of a page that you want to be dynamic. PHP is designed for efficiency. It makes programming easier and a bit more fun by allowing you to write new code, hit refresh, and immediately see the resulting changes without the need for compiling. If you prefer, you can swap out PHP in favor of Perl or the increasingly popular Python language.

LAMP has a classic layered architecture, with Linux at the lowest level. The next layer is Apache and MySQL, followed by PHP. Although PHP is nominally at the top or presentation layer, the PHP component sits inside Apache

***How LAMP stack elements work together***

A high-level look at the LAMP stack order of execution shows how the elements interoperate. The process starts when the Apache web server receives requests for web pages from a user’s browser. If the request is for a PHP file, Apache passes the request to PHP, which loads the file and executes the code contained in the file. PHP also communicates with MySQL to fetch any data referenced in the code. 

PHP then uses the code in the file and the data from the database to create the HTML that browsers require to display web pages. The LAMP stack is efficient at handling not only static web pages, but also dynamic pages where the content may change each time it is loaded depending on the date, time, user identity and other factors. 

After running the file code, PHP then passes the resulting data back to the Apache web server to send to the browser. It can also store this new data in MySQL. And of course, all of these operations are enabled by the Linux operating system running at the base of the stack.
___
___
*  THE CHMOD and CHOWN

Linux File Permissions are essentially a set of rules that dictate who can access a particular file or directory and what actions they can perform with it. These permissions are generally divided into three categories: 
1. read 
1. write
1. execute permissions. 

Each of these categories serves a specific purpose:

Read Permissions: Allow the user to read the contents of the file.

Write Permissions: Enable the user to modify the file or directory.

Execute Permissions: Grant the user the ability to run the file as a program.

Understanding these permissions is not just a good-to-know feature; it’s a necessity for maintaining Linux Security and effective Linux Administration. The chmod Command is the go-to utility for setting these permissions, and it plays a pivotal role in File Access Control.

In the Linux universe, every file and directory is tagged with ownership information, which includes both the user and a group. This is what we refer to as User and Group Ownership. The chown Command is the specialized tool for altering this ownership data.

When you create a file in Linux, by default, the file is owned by the user who created it. However, there are scenarios, especially in a multi-user environment or in Linux Server Management, where you might need to change the ownership to a different user or group. This is where chown comes into play.

For instance, if you’re running a web server, you might want the web server software to own certain files to serve them to visitors. In such cases, changing file ownership becomes a critical task for Linux System Administration.

___
___
                            TCP AND UDP
TCP is the abbreviation of "Transfer Control Protocol" whereas UDP is the abbreviation of "User Datagram Protocol". TCP and UDP are both the main protocols which are used during the Transport layer of a TCP/IP Model. Both of these protocols are involved in the process of transmission of data.
While UDP is used in situations where the volume of data is large and security of data is not of much significance, TCP is used in those situations where security of data is one of the main concern.

__HTTP - 80__

Port 80 is associated with HTTP, Hypertext Transfer Protocol. It comes under the category of a TCP protocol. It is one of the most famous and widely used ports in the world. The main purpose of port 80 is to allow the browser to connect to the web pages on the internet.

**HTTPS - 443**

HTTPS - 443 is also associated with the TCP protocol. HTTPS port 443 also lets you connect to the internet by establishing a connection between the webpages and the browser. This lets you connect to the World Wide Web. However, this port has an added feature of security to it, which HTTP port 80 does not have.

**SSH - 22**

SSH is also referred to as 'Secure Shell'. It operates on the port number 22 of the TCP protocol. It carries out the task of remotely connecting to a remote server or host. It allows you to execute a number of commands and move your files remotely as well.

__TELNET - 23__

TELNET port 23 comes under the category of TCP Protocols. Its main function is to establish a connection between a server and a remote computer. It establishes a connection once the authentication method has been approved.

__FTP - 20, 21__

FTP is the abbreviation of "File Transfer Protocol". The purpose of FTP is to transfer files over the internet. It basically lays down all the rules which are to be followed during the transfer of data. Due to the concern of security, it also asks for authentication by the user before the transfer of data. It is associated with the TCP protocol and corresponds to two ports, port 20 and 21.

__SFTP 22__

SFTP uses port number 22 by default, facilitating secure data movement over a single internet connection. This SFTP port assignment allows SFTP to offer enhanced security and simplicity compared to other protocols like FTP/S, which require multiple ports.

___
___
 *                         THE VIM PRACTICE

 PRESSING THE KEY TO GET THE FOLLOWINGS RESULT

  * i, I:       change to insert mode

* h, j, k, l:    Move left, down, up, right

* w, b, e, ge:  move word at a time

* x, X:      remove a character

* a, A:
append

* f[char]:
move to next given char in line

* F[char]
move to previous char in line

* ; and ,
repeat last f or F

* /yourtext and then: n, N
Search text

* d[movement]
delete by giving movement

* r[char]
replaces character below cursor

* 0, $
move to start/end of line

* o, O
add new line

* %
Goto corresponding parentheses

* ci[movement]
change inside of given movement

* D
delete to end of line

* S
clear current line; to insert mode

* gg / G
move to start / end of buffer

* yy
copy current line

* p
Paste copied text after cursor.

* Q quit

* wq save and quit then
* hit **enter key**  
