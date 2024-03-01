# Introduction to The Internet & Associated Technologies

What's the internet? What does HTML do? What does it mean when people talk about APIs? 

If you're asking these questions, we've cobbled together this brief overview (and I do mean brief overview - nothing is in depth here) to give you a basic understanding of some of the terms used in our day-to-day lives.

We'll not be jumping into deep theory or concepts here, instead we'll try to give you a high-level understanding of the context.

<!-- TOC -->

- [Introduction to The Internet & Associated Technologies](#introduction-to-the-internet--associated-technologies)
- [What is the internet?](#what-is-the-internet)
    - [The internet is a network of networks](#the-internet-is-a-network-of-networks)
    - [Brief History](#brief-history)
        - [The Beginning of the internet](#the-beginning-of-the-internet)
        - [Email](#email)
        - [Domain Names](#domain-names)
        - [The World Wide Web](#the-world-wide-web)
        - [Web Browsers](#web-browsers)
        - [JavaScript & CSS](#javascript--css)
        - [The Cloud](#the-cloud)
    - [How the internet works](#how-the-internet-works)
        - [Protocols?](#protocols)
        - [IP & DNS](#ip--dns)
        - [HTTP](#http)
    - [Summary](#summary)
        - [Major Concepts](#major-concepts)
- [Internet Technologies](#internet-technologies)
    - [What is HTML](#what-is-html)
        - [Why do we use HTML?](#why-do-we-use-html)
        - [What does HTML look like?](#what-does-html-look-like)
    - [What is CSS?](#what-is-css)
        - [Why do we use CSS?](#why-do-we-use-css)
    - [Webpage architecture](#webpage-architecture)
        - [Architecture of static web site](#architecture-of-static-web-site)
- [Programming languages](#programming-languages)
    - [What is a programming language?](#what-is-a-programming-language)
    - [What are examples of programming languages?](#what-are-examples-of-programming-languages)
- [APIs (Application Programming Interface)](#apis-application-programming-interface)
    - [What is an API?](#what-is-an-api)
    - [Why do we user Web APIs?](#why-do-we-user-web-apis)
- [IDE](#ide)
    - [What is an IDE?](#what-is-an-ide)
    - [Why do we need to use an IDE?](#why-do-we-need-to-use-an-ide)
    - [Popular IDEs](#popular-ides)
- [Version Control](#version-control)
    - [What’s Version Control?](#whats-version-control)
    - [Benefits of using version control](#benefits-of-using-version-control)

<!-- /TOC -->

# What is the internet?

## The internet is a network of networks

![alt](<img/How The Internet Works 101 - IG Updates0.jpg>)

---

Before we learn what the Internet is, we need to understand what a *network* is. 

A network is a group of computers or other devices (*tablets, phones, etc*) which are connected to each other. For example, you at your home might have a network of computers and devices. Your friend living next door might have a similar network of devices. Their neighbour might have a similar network of devices. All these networks **when connected together** form the *internet*.

## Brief History

![alt](<img/How The Internet Works 101 - IG Updates1.jpg>)

Before we begin, it’s important to know the difference between “*the internet*” and “*the world wide web*.” 

*Internet* refers to a network of connected computers that exchange digital information. 

The *world wide web* is the system built on top of the internet that enables the sharing of graphic websites. 

Transferring files between computers and email is part of the internet but websites on the world wide web make it easier to perform these activities.

---

### The Beginning of the internet

![alt](<img/How The Internet Works 101 - IG Updates2.jpg>)

The internet started as a US military project. During the height of the Cold War between the US and the Soviet Union, the US government was afraid that if one computer center was destroyed then all the data at that center would be lost forever. They wanted a way to share data across computers in different geographies. 

In 1969, ARPANET, the Advanced Research Projects Agency Network, launched. The Advanced Research Projects Agency sponsors research and development at universities for the US government and military. ARPANET started off as a connection between computers at Stanford University and UCLA. 

The very first message sent between computers was **“LO”** from UCLA to Stanford. The message was supposed to be **“LOGIN”** but the network crashed before sending the “G”.

Starting in the 1970s, computers all across the country and world connected to ARPANET.

---

### Email

![alt](<img/How The Internet Works 101 - IG Updates3.png>)

The first email was sent in 1971. Email was originally meant to send messages between users on ARPANET. Before email, messages could be sent between computers but each computer had its own mailbox and was specific to that computer. Email addresses were still formatted with **user@location**. The very first email contained the message “QWERTYIOP”, the top row of the keyboard.

### Domain Names

The first domain name registered was symbolics.com

![alt](<img/How The Internet Works 101 - IG Updates4.jpg>)

In 1985, the first domain name was registered. Domain names are the .com, .edu, .org, etc. extension in a website name. Domain names made it easier to identify computers on ARPANET. The first domain name registered was symbolics.com, a website for what was at the time a computer parts manufacturer. Today the website commemorates the first domain name.

---

### The World Wide Web

![alt](<img/How The Internet Works 101 - IG Updates5.jpg>)

Starting in 1989, Tim Berners Lee, a British scientist working at CERN (the European Organization for Nuclear Research), began working on a way to organize documents on the internet that connected to each other by clicking on “links.” These documents would be written in HTML, *HyperText Markup Language*. 

HTML tells a computer how a web page should look like but is not considered a programming language. 

This was the very start of the world wide web.

---

### Web Browsers

In 1993, the MOSAIC web browser was first introduced by researchers at the University of Illinois at Urbana-Champaign. 

![alt](<img/How The Internet Works 101 - IG Updates6.jpg>)

A web browser is a graphic program that interprets pages on the world wide web. As the world wide web grew, so did MOSAIC. Companies began to customize the MOSAIC code to create other web browsers such as Netscape and Internet Explorer. Netscape eventually became Firefox in 2002. Apple created Safari in 2003 and Google launched Chrome in 2008.

Examples of browsers:

- Google Chrome
- Mozilla Firefox
- Opera Web browser
- Safari Web Browser
- Microsoft Edge

---

### JavaScript & CSS

![alt](<img/How The Internet Works 101 - IG Updates7.jpg>)

In 1995, the JavaScript (commonly also known as JS) programming language was introduced. Javascript enabled websites to be *interactive*. When you click a button and get a popup for instance, that's done using JS.

> Not to be confused with the programming language *Java*; JavaScript is unrelated.

In 1996, CSS was introduced. CSS made it easy to add complex styling to websites - in short, CSS is what makes sites look nice. 

HTML, CSS, and Javascript is the code that determines how websites are designed and how users interact with it. 

---

### The Cloud

The cloud is just *remote computers* – that’s it!

![alt](<img/How The Internet Works 101 - IG Updates8.jpg>)

One of the early challenges with starting a website was setting up the *servers* on which the website runs. 

Many websites failed because they grew too fast. A company may only buy enough servers for a couple thousand users but it then grows to millions of users. Cloud computing enables users to create servers on demand. 

Amazon Web Services started in 2006 and remains the leader in cloud computing today.

---

## How the internet works

![alt](<img/How The Internet Works 101 - IG Updates9.jpg>)

At a high level, the internet works by connecting devices and computer systems together using a set of standardized *protocols*. 

These protocols define how information is exchanged between devices and ensure that data is transmitted reliably and securely.

The core of the internet is a global network of interconnected routers, which are responsible for directing traffic between different devices and systems. When you send data over the internet, it is broken up into small packets that are sent from your device to a router. The router examines the packet and forwards it to the next router in the path towards its destination. This process continues until the packet reaches its final destination.

### Protocols?

![alt](<img/How The Internet Works 101 - IG Updates10.png>)

Protocols play a critical role in enabling communication and data exchange over the internet. A protocol is a set of rules and standards that define how information is exchanged between devices and systems.

There are many different protocols used in internet communication, including the Internet Protocol (**IP**), the Transmission Control Protocol (**TCP**), the User Datagram Protocol (**UDP**), the Domain Name System (**DNS**), and many others.

---

### IP & DNS



IP addresses and domain names are both important concepts to understand when working with the internet.

An *IP address* is a unique identifier assigned to each device on a network. It’s used to route data to the correct destination, ensuring that information is sent to the intended recipient. IP addresses are typically represented as a series of four numbers separated by periods, such as “192.168.1.1”.

*Domain names*, on the other hand, are human-readable names used to identify websites and other internet resources. They’re typically composed of two or more parts, separated by periods. For example, “google.com” is a domain name. Domain names are translated into IP addresses using the Domain Name System (*DNS*). You can think of DNS as a massive address book you can use to lookup the IP address:

![alt](<img/How The Internet Works 101 - IG Updates12.jpg>)

DNS is a critical part of the internet infrastructure, responsible for translating domain names into IP addresses. When you enter a domain name into your web browser, your computer sends a DNS query to a DNS server, which returns the corresponding IP address. Your computer then uses that IP address to connect to the website or other resource you’ve requested.

![alt](<img/How The Internet Works 101 - IG Updates11.png>)


### HTTP

HTTP (*HyperText Transfer Protocol*) and HTTPS (*HTTP Secure*) are two of the most commonly used protocols in internet-based applications and services.

![alt](<img/How The Internet Works 101 - IG Updates13.png>)

HTTP is the protocol used to transfer data between a client (such as a web browser) and a server (such as a website). When you visit a website, your web browser sends an HTTP *request* to the server, asking for the webpage or other resource you’ve requested. The server then sends an HTTP *response* back to the client, containing the requested data.

HTTPS is a more secure version of HTTP, which encrypts the data being transmitted between the client and server using SSL/TLS (Secure Sockets Layer/Transport Layer Security) encryption. This provides an additional layer of security, helping to protect sensitive information such as login credentials, payment information, and other personal data.

---

## Summary

### Major Concepts

- The internet is a **global network of interconnected computers** that uses a standard set of communication protocols to exchange data.

- The internet works by **connecting devices and computer systems together** using standardized protocols, such as IP and TCP.

- The **core of the internet is a global network of interconnected routers that direct traffic** between different devices and systems.

- Basic concepts and terminology include **packets, routers, IP addresses, domain names, DNS, HTTP, HTTPS, and SSL/TLS** .

- **Protocols** play a critical role in enabling communication and data exchange over the internet, allowing devices and systems from different manufacturers and vendors to communicate seamlessly.

---

# Internet Technologies

## What is HTML

HTML is the brainchild of Tim Berners-­Lee. In 1990, Berners­-Lee needed something that would help scientists coming from different colleges and universities access documents and research from other scientists. That problem led to Berners­-Lee inventing the World Wide Web, the hypertext transfer protocol or HTTP, and HTML.

![alt](<img/How The Internet Works 101 - IG Updates14.jpg>)

HTML is actually shorthand for HyperText Markup Language. It is the language of Web pages that tells a browser *how* to display certain elements, such as text and images through the use of codes and symbols. HTML is the standard when it comes to creating Web pages. 

The [World Wide Web Consortium](https://www.w3.org/), or W3C recommends it, and as such most browsers implement HTML to help display Web pages more or less uniformly.

---

### Why do we use HTML?

It is the skeleton of just about any website. It provides the bones that underpin everything else on site. Common things that HTML is used to define are:

- **Paragraphs** 
  - The HTML paragraph element is one of the most common elements and as you might have guessed it defines a paragraph.

- **Line Breaks** 
  - As with print media, a paragraph creates a line break below it to visually separate it from other paragraphs. This is used to emphasise a semantic separation of content. The same structure is used in a novel or a magazine.

- **Block Elements** 
  - Elements that create the spacing below themselves on a page are called block elements. Block elements appear vertically down the left-hand side of a page at least until they are styled by CSS. Examples of block elements are **\<div>**, **\<article>**, **\<table>**, and many more. This feature allows HTML to start separating a webpage into different sections

- **Headings** 
  - Paragraphs and headings work in concert to create the majority of the text content of a web page and its structure. HTML has six heading elements, which are numbered 1 through 6. h1 is the most significant and usually contains the title of the content – Not to be confused with the title that appears in the browser tab. h2 represents a subsection. h3 and so on represent identifiers of further subjects in subsections until we get to h6.

> The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. It defines the content and structure of web content

---

### What does HTML look like?

![alt](<img/How The Internet Works 101 - IG Updates15.jpg>)

## What is CSS?

CSS stands for Cascading Style Sheets.

CSS was developed by W3C ( [World Wide Web Consortium](https://www.w3.org/) ) in 1996 for a rather simple reason. HTML element was not designed to have tags that would help format the page. You were only supposed to write the markup for the web page.

Tags like \<font>  were introduced in HTML version 3.2, and it caused quite a lot of trouble for web developers. Due to the fact that web pages have different fonts, coloured backgrounds, and multiple styles, it was a long, painful, and expensive process to rewrite the code. Thus, CSS was created by W3C to solve this problem.

CSS is not technically a necessity, but you probably wouldn’t want to look at a web page that features only HTML elements as it would look completely bare-boned.

---

### Why do we use CSS?

CSS (Cascading Style Sheets) is used to  style and lay out web pages — for example, to alter the font, colour, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features.

CSS is designed to enable the separation of content and presentation, including layout, colours, and fonts. 

This separation can improve content accessibility.

## Webpage architecture

### Architecture of static web site

![alt](<img/How The Internet Works 101 - IG Updates16.png>)

Put simply, the *front end* is a combination of two different elements: the graphic design (the look) and the user interface (the feel).

*Back-end* development means working on *server-side software*, which focuses on everything you can’t see on a website.

This is often properly referred to as *client-server*.

> Your back-end might contain the business logic and a database for storage, whilst your front-end is focused of the display of the data provided from the back-end.

---

# Programming languages

## What is a programming language?

A programming language is a computer language programmers use to develop programs, scripts, or other sets of *instructions* for computers to execute.

Languages share common traits and sometimes syntax, but they’re not the same:

**Java**
```java
public class HelloWorld { 
  public static void main(String[] args) { 
    // Prints "Hello, World" in the terminal window. 
    System.out.println("Hello, World!"); 
  } 
} 
```


**C#**
```c#
using System; 

namespace HelloWorld { 
  class Program { 
    static void Main(string[] args) { 
      Console.WriteLine("Hello World!"); 
    } 
  } 
}
```

---

## What are examples of programming languages?

![alt](<img/How The Internet Works 101 - IG Updates19.png>)

There are thousands of programming languages available
Some commonly used languages are shown on this slide

1. Python – 29.48% market share
2. Java – 17.18% market share
3. JavaScript – 9.14% market share
4. C# – 6.94% market share
5. PHP – 6.49% market share
6. C/C++ – 6.49% market share
7. R – 3.59% market share
8. TypeScript – 2.18% market share
9. Swift – 2.1% market share
10. Objective-C – 2.06% market share

https://99firms.com/blog/most-popular-programming-languages/


# APIs (Application Programming Interface)

## What is an API?

An API is a set of programming code that enables data transmission between one software product and another.

It also contains the terms of this data exchange.

> API stands for Application Programming Interface.

In the context of APIs, the word "Application" refers to any software with a distinct function. Interface can be thought of as a *contract* of service between two applications.

This *contract* defines how the two communicate with each other using requests and responses.

We'll just look at web APIs here, although other APIs exist.

---

## Why do we user Web APIs?

Simply put, Web APIs allow for a greater connection between your business and the outside world, allowing you to integrate with other companies or third-party software so that they can communicate with each other.

![alt](<img/How The Internet Works 101 - IG Updates21.png>)

> An API serves as a messenger between an end user and a website or application. 
>
> That may sound simple, but APIs are powerful and vital tools. Without an API, a site, app, or service is relatively segregated and highly limited in functionality

---

# IDE

## What is an IDE?

An integrated development environment (IDE) is a software application that helps programmers develop software code efficiently. It increases developer productivity by combining capabilities such as software editing, building, testing, and packaging in an easy-to-use application.

![alt](<img/How The Internet Works 101 - IG Updates22.gif)

> An IDE normally consists of at least a source-code editor, build automation tools, and a debugger.

---

## Why do we need to use an IDE?

![alt](<img/How The Internet Works 101 - IG Updates23.png>)

Popular IDE features are designed to aid developers in organising their work and resolving issues. 

IDEs check code as it is written, allowing for real-time detection of problems caused by human mistakes. 

Developers can perform activities without switching between programs because utilities are represented by a single GUI.

Most IDEs have syntax highlighting, which uses visual clues to discern grammar within the text editor.

An IDE provides software developers with all the tools they require to complete projects in a central location.

IDEs contain tools such as a code editor, a compiler, debugger and build automation tools, and some have more task-specific tools such as object and class browsers. 

---

## Popular IDEs

* IntelliJ IDEA
  * Apart from supporting web, enterprise, and mobile Java programming, it is also a good option for JavaScript, SQL and JPQL programming
* Visual Studio
  * Visual Studio has the capability to support mobile app, web and game development. It also supports Python language, Node.js, ASP.NET and Azure. With Visual Studio, developers can easily create a development environment in the cloud
* Eclipse
  * Although Eclipse is best associated with Java, it also supports multiple programming languages. In addition, users can add their preferred plugins to the IDE to support software development projects.
* PyCharm
  * PyCharm is an IDE developed by JetBrains specifically for Python.
* NetBeans
  * it’s a no-nonsense software for Java, JavaScript, PHP, HTML 5, CSS and more.

![alt](<img/How The Internet Works 101 - IG Updates24.png>)

> The programming language you want to code in often dictates the choice of an IDE.
>
> Dedicated IDEs have automation features that particularly suit the syntax of specific languages.
>
> On the other hand, multi-language IDEs support multiple languages.

---

# Version Control

## What’s Version Control?

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.

As development environments have accelerated, version control systems help software teams work faster and smarter.

![alt](<img/How The Internet Works 101 - IG Updates25.png>)

---

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

For most software teams, the source code is a repository of the invaluable knowledge and understanding about the problem domain that the developers have collected and refined through careful effort. Version control protects source code from both catastrophe and the casual degradation of human error and unintended consequences.

> At its most basic, imagine a remote computer that keeps all your code safe for you and tracks all the changes automatically.

## Benefits of using version control

* Collaboration
  * Any number of people from other regions can contribute to a project
* Branching and merging
  * Branching allows teams of developers to easily collaborate inside of one central code base. When a developer creates a branch, the version control system creates a copy of the code base at that point in time. Changes to the branch don't affect other developers on the team.
  * Merging is an operation that reconciles multiple changes made to a version-controlled collection of files. Most often, it is necessary when a file is modified on two independent branches and subsequently merged. The result is a single collection of files that contains both sets of changes
* Single source of truth
  * The master branch of a repository becomes the source of truth for tracking changes and resolving conflicts
* Simplify rollback
  * In the event of a rollback, it’s simple to revert a merged branch and return to a previous state.
* Maintain full audit trail
  * Through commits, all changes are annotated and associated with a team member, so the whole team is able to monitor and track who made these changes and why

Examples of version control software are:

- Git
- CVS (Concurrent Versions System)
- SVN (Apache Subversion)
- TFS (Team foundation server)

