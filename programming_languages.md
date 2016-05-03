# What is a programming language?
A programming language is a language that features a set of rules (*grammar*) to write softwares for computers, that are nothing but a set of instructions that, applying one or more algorithms on a given dataset, returns an output for that is useful for the user.

# What are compilers and interpreters and what they do?
A compiler is an application that translates a programming language (the *source laguage*) to another one (*the target language).

Today we have a huge amount of programming languages, most of them are very similar to the human language (*natural language*).
Computers, at a very low level, can understand only a language: the *machine code*.
This means that the only way to make whichever language we decide to use work is to translate it to the machine code. This is what a compilers (that's basically another application that generates an executable file written in said language) do.

Interpreters, on the other end, are softwares that read line-per-line a source code. Each line is translated and executed *on fly*, instead of generating an executable file that must be run separately.

# What's the difference between Frontend (FE) and Backend (FE)
In the acceptation we usually refer to, these terms distinguish the possibility of executing a language to generate code that will be run directly on the internet browsers (*client-side*) or instead working on the servers (*server-side*).

The languages that browsers understand are basically HTML, CSS and JavaScript (not the only, but for sure the most used :)). The HTML is a language that describes the layout of a page and its content and allows the injection of external resources, as the CSS that defines its visual style and the JavaScript is a programming language that allows to manipulate all the elements in the page, HTML and CSS included.

Long story short, frontend languages are executed in the browser (we get the source code as plain text), while backend languages are executed on servers that can live on the other side of the world, and usually generate... frontend!

For example, if we want to search inside a database and print the results on the browser, we need first of all to access these data and running certain algorithms, and then printing them in HTML (that, as said, describes the content of an internet page too). But the database is protected, we can't just read it as it is! If we want to read inside a database with JavaScript, we would need all the passwords and stuff on clear, and this is probably not something that its the owner would be happy to see.

The idea is then to use a programming language on the server (*server-side*) in order to do all the stuff and then return plain the HTML/CSS/JavaScript already filled with these secret informations. BRILLIANT!

Now, do you remember what I said about JavaScript?

> JavaScript is a programming language that allows to manipulate all the elements in the page

What I want to explain you is that it's not a language that is split in frontend and backend (or *client-side* and *server-side*), but its *implementation*, the use we make of it!

I mean, JavaScript is a programming language like the others. It's just that it's been *implemented* in all the browser for historical reasons. But the reality is that we can use JavaScript even ouside the browser, on the server-side. NodeJS is nothing but an implementation of the JavaScript programming language born to be run outside the browser (to make it simple...).

Just saying, there are implementations of Ruby (called Opal) that compiles Ruby to JavaScript. Is Ruby a frontend language? Could be, it's just that it's not much used. Same for Scala.js, for example.

The only difference is that all the browsers are shipped with a JavaScript implementation, so they can run only this programming language, and if we want to use another one we have to compile it in this (like if it is our machine code).

# What are some of the languages used for FE and BE?
We call "frontend" a language that is supposed to run inside a browser or that is supposed to be compiled to a language runnable by a browser.
We call "backend" all the languages that usually are used on a server and somehow interact with the user/browser (client).

**Frontend**: HTML, XML, CSS, JavaScript, CoffeeScript, ClojureScript, Scala.js, Opal... (TODO)

**Backend**: PHP, Java, Ruby, ASP, ASP.NET, C#, Scala, Clojure, Python, Javascript (NodeJS), Erlang, Elixir, Rust...

# What is a framework?
A framework is a collection of libraries that aims to let developers create applications with ease.
Frameworks usually cover a large area of responsibilities. *Ruby on Rails*, for example, allows developers to create web applications doing a huge amount of tasks under the hood and keeping code bases as more standard (this means that new developers can join project with ease, deliver features faster and mantain easier the current ones) as possible thanks to the conventions it imposes to the developers. Also generally they're safer as most of the protection to common vulnerabilities are demanded to the framework itself.
From the client side, they're usually useful because they keep applications cross-compatible among the browsers and devices (smartphones, tablets and so on).

# What is the difference between Scala and Scala.js?
Scala is a general purpose programming language based on the *Java Virtual Machine* (basically the "interpreter" used by the Java programming language).
It rethinks the design of Java introducing the functional paradigm with a new syntax and contructs.

Scala.js is a compiler that translates Scala to JavaScript.
In this way, developers can write frontends directly in Scala, even though browsers can't run it (as, I would recall you, the only programming language browsers can understand is JavaScript – HTML and CSS are not programming languages!) since it's the Scala.js compiler that translates *on the fly* their Scala code to JavaScript.

These kinds of compilers are also called *transpilers*. ClojureScript, TypeScript, Opal are other valid examples.

# ES7 (or ECMAScript 2016 or ES2016)
ES7 is the last iteration of ECMAScript, that is the programming language on which is JavaScript based on.
It introduces new features, of which some are totally new and some other ones were possible only with additional libraries, like jQuery or Lodash/Underscore.
