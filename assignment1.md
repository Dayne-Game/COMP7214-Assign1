# Client-Server Computing

## Client-Server and Uses of Client Server

According to <i>webopedia.com</i>, Client-Server Computing is a computing model that involves client computers and a server. The process begins when the client computer communicates and makes a request to the server over a network.  The server shares its resources, applications and or data with the client computer, and can even share to multiple client computers at the same time on the network. A client computer is a device that is connected to the network (phone, tablet laptop, Desktop PC etc.).

## Why has Client-Server Computing Evolved

With technology evolving each year, Client Server Computing has evolved massivley from the start till now. When Client Server Computing first started out, the server did all of the grunt work, and than sent out the HTML to the clients computers, and thats what they see. Now with the evolution of Client Server Computing, the server only holds the data, and each client computer does all of the fetching and requesting straight from the browser, so instead of the server getting multiple requests, it only gets one request. This makes the servers work alot easy, making the maintenance, cost and up keep, alot cheaper and easier.  

## Advantages and Disadvantages

### Fat Client-Server Architectures

**Advantages**

*Rich Graphic User Interface*

Fat Client-Server Architectures have the capability of delivering rich graphical user interfaces. These interfaces include operating systems, immersive computer programs, and heavy graphic video games.

*Server Performance Efficency*

Fat Client-Server Architectures doesn't need high performing/powerful servers. Fat Client-Server performs tasks at a local or individual level not at a centralized level. This overall means low cost when purchasing, installing and maintaing of servers.

**Disadvantages**

*Maintenance*

Every computer will need to be maintained, tehy must be updated for bug fixes and security updates for each software program. The hardware must be maintained at levels acceptable for the software applications they will be using.

*Data Backing Up*

If data is stored on a local machine, it will need to be consistanly backend up to the server in order to protect organisations data.

### Thin Client-Server Architectures

**Advantages**

*Optimization of Hardware Resources*

Thin Client-Server Architectures require less/fewer hardware requirements. This means that Thin Client-Server Architectures need less cabling, bussing and switching, which makes Thin Client-Server Architectures cost-effective.

*Reduced Hardware and Software Maintenance*

Thin Client-Server Architectures offer easier hardware and software administration, troubleshooting, system or application patching, security updates, and data migration. 


**Disadvantages**

*Single Point of Faliure*

Since Thin Client-Server Architecture performs tasks at a centralized level, this cane bring a huge potential risk. Since Thin Clients are connected to one server, if that server goes down/crashes all the clients connected will be affected.

*Subject to Netwrok Loss*

Thin Client-Server Architecture gets responses from ther server. So if there is a network connection loss, users of a thin client wont be able to connect to the server so therefore wont be able to do any work.

# Full Stack Development

## What is a Full Stack Web Developer?

A Full Stack Web Developer is someone that develops both the Client Software and Server Software. Client Software is what the user sees and interacts with, this is also known as the Front-end. Server Software is what connects the website to the server, and database to get information to the website, this is also known as the back-end. 

## Full Stack Web Developer Skill Set

The skill set of a Full Stack Web Developer consists of multiple client and server software languages, that must be known by the person and how they work. There are three main Software Stacks, that are widely used in industry. LAMP, MERN, and MEAN Stack.

### LAMP STACK

The LAMP Stack is the oldest of the three stacks, and is very widely used in the industry, for web services (websites). LAMP uses four open-source components.

| Components |                                                            Description                                                            |
| :--------: | :-------------------------------------------------------------------------------------------------------------------------------: |
| L - Linux  |                Linux is an open-source operating system that is widely used on servers, and developers’ computers                 |
| A - Apache | Apache is the most used Server Software. It runs on 67% of all Web Servers in the world, it’s also very fast, reliable and secure |
| M - MySQL  |                                        MySQL is an open source database management system.                                        |
|  P - PHP   |                                        PHP is a server-side open source scripting language                                        |

Notable website that use the LAMP Stack, are Facebook, Yahoo!, Wikipedia and WordPress.

### MERN STACK

The MERN Stack uses a collection of JavaScript based Technologies. This stack is also used for creating web applications (websites)

| Components  |                                   Description                                   |
| :---------: | :-----------------------------------------------------------------------------: |
| M - MongoDB |                         A free to use, no SQL database                          |
| E - Express |                 Easy, light and portable web program framework                  |
|  R - React  | Facebook developed, JavaScript framework for creating front-end/user interfaces |
|   Node.js   |                        A JavaScript server-side runtime                         |

This stack is the newest of the three, but it’s the most in demanded in the industry right now. 

### MEAN STACK

The MEAN Stack is another stack that uses a collection of JavaScript components. The MEAN stack was around before the MERN stack but has sort of been superseded by the MERN stack.

| Components  |                                                Description                                                |
| :---------: | :-------------------------------------------------------------------------------------------------------: |
| M - MongoDB |                                      A free to use, no SQL database                                       |
| E - Express |                              Easy, light and portable web program framework                               |
| A - Angular | A JavaScript framework for creating HTML5 and JavaScript web programs. Angular.js was developed by Google |
|   Node.js   |                                     A JavaScript server-side runtime                                      |

## What does a Full Stack Web Developer do?

As a Full Stack Developer, you get a lot more responsibility. To be full stack, you need to be able to work and develop on the front-end (Client Software/User Interface), and the back-end (Server Software). A Full Stack Developer should also be able to design the website if required/requested by the Project Manager who gets the requirements from the client.

## Differences between a Full Stack Web Developer and a Traditional Web Developer?

In web development there are two parts to a website. The front-end and the back-end. The front-end is the visual aspect of the website (what the user/client sees). This is the most common position for a web developer, as they can create static websites (website without a backend), and only need to work on what the website will look like, and the functionality. The back-end is the server-side aspect of the website. This is where all the data is kept (on some websites). A back-end developer works on how the data gets sent to the website when the user/client requests it and is just the behind the scenes for the website. A Full Stack Web Developer is a hybrid of both and has suitable and adequate knowledge of both front-end and back-end technologies. 

# Document Databases

## What is a Document Database (No SQL)?

A document database is a non-relational database that store information using JSON like documents. With the data being in JSON like documents, it allows the developers to query the data a lot easier as it is using the same document-model that is used in the application code. With the flexibility, semi structured, and hierarchical nature the JSON document format, allows the document database to evolve with the applications needs. According to AWS document databases work well with uses cases such as catalogs, user profiles, and content management systems.

## Background, History and Philosophy of Document Databases

The acronym “NoSQL” evolved from Carlo Strozzi in 1998, after he called his lightweight, open source relational database that didn’t use SQL. NoSQL has two meanings, “No SQL” or “Not only SQL”. NoSQL databases was developed as a response to web data, because of the need for faster processing of unstructured data. Due to the NoSQL distributed database system, NoSQL databases are a better fit for large unstructured datasets compared to the normal relational databases.  

### Cap Theorem 

Also known as the Brewer’s Theorem, this theorem states that a NoSQL/Non-relational database distributed data cannot simultaneously offer more than two of three established guarantees.

|     Guarantees      |                                                                                                      Description                                                                                                       |
| :-----------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     Consistency     |                         The data within the database remains consistent, even after an operation has been executed. For instance, after updating a system, all clients will see the same data.                         |
|    Availability     |                                                                           The system is constantly on (always available), with no downtime.                                                                            |
| Partition Tolerance | Even if communication among the servers is no longer reliable, the system will continue to function. This is because the servers can be partitioned off, into multiple groups which can’t communicate with each other. |

## Query Comparison

Scenario: **Find all contacts with at least one work phone!**

SQL (Database)
<br />
``` select * from contact A, phones B where A.did = B.did and B.type = 'work'; ```

MongoDB (Document Database)
<br />
``` db.contact.find({"phones.type":"work"}); ```

As you can see the query in MongoDB (which is a document database) is a lot easier to understand and alot simpler than the normal traditional SQL database query. 

# Single Page Applications

A Single Page Application, is an app that is used and works inside of a browser (Firefox, Google Chrome Safari etc.) that doesn't need page reloading when its used. SPA's use JavaScript to load and change the content of the pages, so there is no refresh or load time of pages (so no waiting!). This is to give the UX of the website a natural feel when using the website/application. 

## Background, History and Philosophy of SPA

Concise Meaning of a SPA (Single Page Application)
 - A **Single Page Application** is a web application that requires only a single page load in a web browser.

In the early 90's, the Internet was on the rise. During this period websites were being made using Tim Berners-Lee CERN. 

| Components |                                           Description                                            |
| :--------: | :----------------------------------------------------------------------------------------------: |
| Hypertext  | Formally HTML. A language that is used for creating documents/pages that can link to each other. |
|    HTTP    |                     A communication protocal for transferring HTML documents                     |
|    URLs    |                       An addressing convention for locating HTML documents                       |
|   httpd    |                       A basic web server that than become known as apache                        |

SPAs actually existed back in the mid 90s. In 1995 and 1996 two technologies were introduced, Java Applets and Flash. Java Applets were used for graphics and cpu intense tasks on the web, where as Flash is used for creating cool looking websites, with loading bars, click to enter links and so on. 

### Road to Single Page Applications

Before Single Page Applications (SPA), there were Multiple Page Applications (MPAs, which are still used today). These MPAs were builit in static HTML with a server-side language such as PHP, Ruby, ASP etc. These type of websites are still considered normal websites.

MPAs worked by getting mulitple requests from the Server to the Client. Doing this made the website and web services reliant, and demand on the server. Ajax came along and help alleviate that problem. Ajax allows web pages to be updated without sending another request to the server (reloading).

The first step in making SPAs work, was the launch of JQuery in 2006. JQuery was only a front-end framework for JavaScript. JQuery didn't support any elegant ways of handling the websites data. After JQuery Knockout.js came into the mix. Knockout.js is another JavaScript framework that brought MVVM data binding in. Knockout.js improved and simplified the data binidng process, by spearting the view and applications data. 

In 2009 Backbone.js was released. Backbone.js gave developers a light-weight client-side framework. Backbone.js was initally the start of SPA applications. you could create SPAs using bacbone.js but it involved alot of work and a lot of repeitive code.

Angular.js was the first true SPA solution out there. It was released in 2010 by Google. Angular provided client-side model-view-controller (MVC) architecture, with two-way data binding. 

## Multiple Page Applications

The Traditional (Normal) way of creating web applications is also known as Mulitple-Page Applications.

Multiple Page Applications are quite a bit larger than Single Page Applications, because they have to be. Due to the amount of content that is found on the web pages these webpages will need many levels of UI. Now with Ajax, you dont have to worry about big and complex web applications transfering a lot of data from the server to the browser. Ajax improves and allows to only refresh one particular part of the application that is requested by the client/user.

#### Pros of Multiple-page Applications
- Perfect for users that need a visual map on where to go, when using the web application. 
- Easy for proper SEO management. Multiple Page Applications gives better chances to rank for different keywords, since the web application can be optimized for each keyword on a page.

#### Cons of Multiple-page Applications
 - The front-end and back-end of the web application are tightly coupled.
 - Development of a multiple page applications can become quite complex to create. There needs to be frameworks used for either the client side and server side. This than results in longer development of the application.

## Technologies

The technologies used to create SPAs are JavaScript frameworks. Angular.js, Ember.js, Meteor.js, Knockout.js and React, are all frameworks that are used to create Single Page Applications. Whereas Multiple Page Applications use HTML5, CSS, JavaScript and a serverside language like PHP, RUBY etc.

### Strengths of SPA
- Fast and Responsive. Since everything is loaded in the browser and not the server, means you get information instantly.
- Caching Capabilites. SPAs can cache local data effectively, and stores all the data it recieves. This gives the application to use the stored data even without and internet connection.
- Debugging with Chrome. Most SPAs frameworks have their own debugging tools that can be downloaded directly from the Chrome store, to give you problems and debugging right in the browser.

### Weaknesses of SPA
- Browser History. When a user clicks the back button on the browser, its takes the user back to the previous page, but not the previous state in the website.
- Security. SPAs are less immmune to cross-site scripting (XSS) attacks, than your normal Traditional/multi-page applications.

## Business Problems

Single Page Applications aren't the best fit for forums, blogs, news sites and public content aggregation/curation services. Single Page Applications are best for for static websites, such as small business website, portfolio websites, athlete/famous peoples websites etc.

# REST APIs

REST stands for Representational state transfer technology (REST), and API stands for Application Program Interface (API).

## What is REST
REST is an architectural style for providing standards between the computer systems located on the web. This allows the computer systems to communicate with eachother a lot easier. A RESTful-compliant system is characterized by how they are stateless, and the speration of Client-side and Server-side.

## What is a REST API

A REST API uses HTTP requests to GET, PUT, POST and DELETE data.

There are three main features that allows a API to be considered a RESTful API.
1. **Client-server** - Frontend is the Client Side and Backend is the Server-side. They are both independent of eachother.
2. **Stateless** - No client data is stored on the server between requests. This means that this type of data is stored on teh client.
3. **Cacheable** - Clients can cache response to improve performance.

## Benefits of using REST API in a SPA

### Client and Server

When using SPA and REST API, your client and server are seperate from eachother. This allows you to test your client-side and server-side independantly as they do not rely on eachother. If you have a bad UI/UX design, you can change and update that design without even touching the server-side of your website.

### Better Code Quality


# References

SkillCrush. (21/06/2019). Front End, Back End, Full Stack – What does it all mean?. Retrieved from https://skillcrush.com/2017/02/27/front-end-back-end-full-stack/

AWS. (n.d). The document database refined. Retrived from https://aws.amazon.com/nosql/document/

Cyber Craft. (n.d). Top 10 Projects Developed with PHP Technology. Retrieved from https://cybercraftinc.com/blog/top-10-projects-developed-with-php-technology

Guru99. (n.d). What is Full Stack Developer? Skills to become a Web Developer. Retrieved from https://www.guru99.com/full-stack-developer.html

Wpbeginner. (n.d). What is: Apache. Retrieved from https://www.wpbeginner.com/glossary/apache/

W3Schools. (n.d). What is Full Stack?. Retrieved from https://www.w3schools.com/whatis/whatis_fullstack.asp

Webopedia. (n.d). Client/Server Computing. Retrieved from https://www.webopedia.com/Computer_Science/Client_Server_Computing

Medium. (Dec 2, 2016). Single-page application vs. multiple-page application. Retrieved from https://medium.com/@NeotericEU/single-page-application-vs-multiple-page-application-2591588efe58

Paislee. (n.d). Evolution of the Single Page Application. Retrieved from http://paislee.io/evolution-of-the-single-page-application/

Quora. (Apr 17, 2017). What is the history of SPA Single Page Applications. Retrieved from https://www.quora.com/What-is-the-history-of-the-SPA-single-page-application

Dev. (n.d). Single Page Application Benefits & Technology Stack. Retrieved from https://dev.to/dianamaltseva8/single-page-applications-benefits--technology-stack-nhb

Search App Architecture (n.d). RESTful API. Retrieved from https://searchapparchitecture.techtarget.com/definition/RESTful-API

Codeacademy. (n.d). What is REST?. Retrieved from https://www.codecademy.com/articles/what-is-rest

Sitepoint. (n.d). DO you know what a REST API is?. Retrieved from https://www.sitepoint.com/developers-rest-api/

Medium. (Sep 6, 2017). What is REST - A Simple Explanation for Beginners, Part 1: Introduction. Retrieved from https://medium.com/extend/what-is-rest-a-simple-explanation-for-beginners-part-1-introduction-b4a072f8740f

Profolus. (n.d). Thick Client vs Thin Client: Advantages and Disadvantages. Retrieved from  https://www.profolus.com/topics/thick-client-vs-thin-client-advantages-and-disadvantages/

FHB. (Apr 07, 2016). Thin Clients versus Fat Clients Explained. Retrieved from http://blog.fhblackinc.com/thin-clients-vs-fat-clients-explained
