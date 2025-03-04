## Some useful information that can be helpful

1. ### Speed of typing  
I have heard it many times, that speed typing is very helpful skill, however 
never had to type on my keyboard really fast. Of course, if you have a task with
lots of writing, and you know what to do, speed typing can save you a lot of time. 
If you want to check how fast you are, you can do it [here](https://www.typingtest.com/index.php).
You can also improve your typing speed in that site.  
Is it good for you, or you will treat it as a waste of time ... I'm leaving it up to you.

2. ### How the web browsers work?
#### What a web browser really is?
When you hear about web browser, you think about program, that allows you to 
browse world wide web pages. And you right, however it's not full answer. 
Web browsers are most complicated programs that is used by average user. 
Modern browsers can performa many tasks: generate a web page, with its static 
and dynamic content, display many popular documents formats, be used as an e-mail 
client or communicator, or even to wrok on a documents in cloud.  

On the other hand, web browser, as a kind of "world window", can be a source of
problems and infections. That is the way, our computers can get a malware, trojans
and other nasty and dangerous programs. Knowledge about how web browsers work, can
help us to be more safe, and also how to build a safer programs. 

#### Modern web apps.  
What is a web application? It is a software written by using a few technologies
(one of those you will learn in this course), which works on a client - server
architecture. It can communicate with another applications and / or servers and
performing actions on user's request. Some examples are: Facebook, LinkedIn, GMail,
internet shops, bank systems, communicators and games.  
For web apps development there's lots of technologies used, but for now we need to know
just some of them: HTML, CSS and JavaScript.  
**HTML** is a markup language which is used to describe web page structure - paragraphs,
tables, lists, header and footer, forms, hyperlinks etc. You will learn about it
a little bit later, however it would be good to go deeper into this topic (we're not
going to spend much time about it in this course). Latest HTML5 standard (described
in details on World Wide Web Consortium site) can also communicate with user,
handle multimedia content.
**CSS** - Cascading Style Sheet is used to describe the look of an elements on the
web page, including animations and transformations. As with HTML, we will cover only
basics here, and if you want to make your work look nice, you should also dive a little
bit into CSS world.
**JavaScript** can define a reactions of a web page in response to user's actions.
JavaScript can also be used to implement some part of application's logic on the
client side - web browser can interpret JavaScript code and run it.  

#### How it really works?  
The whole process which starts with your click on link, or hitting ENTER after you
wrote an address is called rendering of a web page. First stage is to "unload" 
the page you currently have displayed in the browser. After this, browser is reading
an address of link, or the one from address bar, and checks if requested page is
stored in browser's cache. If its found, you get it really fast on your screen.
If cache does not contains requested page, browser connects with DNS server to resolve
an IP address of the server, which has data you requested, and establishes connection
with that server. The next step is to use a proper HTTP protocol method (usually GET,
POST, PUT or DELETE - we will come back to those later in the course) which is actual
request. If server properly receive your browser's request, and can "serve" requested
data, sends those to your browser (this process is called response). At this moment
your browser starts to work hard - browser analyses received data, builds Document
Object Model (DOM - we will also cover this topic later) based on HTML, applies CSS,
executes JavaScript scripts and finally displays the page you requested. Due to this
schema, it is a good practice to put all JavaScript code at the end of HTML file,
just before closing `</body>` marker.

For the moment that's all you need to know about web browsers. During the
course we will come back to this topic to get a little bit more into details.

3. ### Lore ipsum

4. ### HTTP Protocol basics

**TOC:**  
[[README.md]](https://github.com/nazghulgda/Programming-Crash-Course/blob/main/README.md) - README  
[[INTRODUCTION.md]](https://github.com/nazghulgda/Programming-Crash-Course/blob/main/INTRODUCTION.md) - a few words about my reasons of doing this course  
[[USEFUL_INFORMATION.md]](https://github.com/nazghulgda/Programming-Crash-Course/blob/main/USEFUL_INFORMATION.md) - this file  
[[PREP_LINUX.md]](https://github.com/nazghulgda/Programming-Crash-Course/blob/main/PREP_LINUX.md) - installation and basics of Linux use  
[[PREP_SOFTWARE.md]](https://github.com/nazghulgda/Programming-Crash-Course/blob/main/PREP_SOFTWARE.md) - 
installation and basic information about software, which you will use in this course  