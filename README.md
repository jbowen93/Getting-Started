# Getting-Started
This repository serves as a collection of tutorials and guides to develop a base understanding of software engineering as an industry. 

I will not cover interviewing techniques or study resources as I believe interviewing skills to be tangential at best to a professional software role. 
Additionally there a large number of available resources for those looking for tips on interviewing.

I will only be focusing on software roles in "web" companies and won't be discussing 
necesarry skills for Embedded software, High Performance Computing, or other more niche industries.
This isn't to say that there aren't great jobs in those industries. However they are traditionally less friendly
towards self taught developers and usually expect at least a Bachelors degree if not a Masters or PhD.  

# Step 0: Software Stacks

Software engineering jobs are often segemented based on a stack. There 3 main groupings: 
1. Front End 
2. Back End 
3. Fullstack 

## Front End Software Engineer

A front end software engineer is responsible for the user facing components of an application. 

A frontend engineer will frequently work alongside UI (User Interface) engineers, UX (User Experience) engineers and designers/artists. 

At smaller companies a frontend engineer may be responsible for some or all of the above roles. 

In the current world of software there are several platforms that a company may need/want to support for their application.
Tradditionally a different frontend had to be developed for each platform using a different language/framework.

| Platform | Languages             |
|----------|-----------------------|
| Webapp   | HTML, CSS, Javascript |
| Desktop  | Varies                |
| iOS      | Swift or Objective-C  |
| Android  | Java                  |

Fortunately, there has been an effort made in recent years to provide a single framework that allows cross-platform applications to be developed. 
The result of this effort is a plethora of available tools that allow a developer to create a traiditional web application and then deploy it to
native platforms. 

For the desktop there is [Electron.js](http://electron.atom.io/)  
For mobile applications there is [React Native](https://facebook.github.io/react-native/)

Due to this I will only be focusing on HTML, CSS and Javascript for frontend development. 
That's not to say that there aren't positions which require experience with a given platform's native framework.
The best native applications are developed either fully or partially using the native frameworks. 
However, for a beginner I believe a thorough understanding of the web frameworks provides more employment
opportunities than choosing to focus on a specific platform. 

## Back End Software Engineer

A back end software engineer is responsible for the data processing, business logic and database portions of an application.

Depending on the company a back end engineer's role may be broad, dealing with all of the above tasks, or narrow dealing with only one of the above tasks. 
For this reason I believe it is a best for a beginner to have an understanding of all of these tasks while not focusing too heavily on any of them before working in a professional role. 

Like frontend engineering there are multiple platforms where back end software may run,
however for modern applications there are really only two platforms worth mentioning: 
- Microsoft systems
- POSIX compatible systems. 

For the purposes of this guide I will only be only be focusing on applications targeting POSIX compatible systems. 
More specifically I will focus on software targetting x86-64 Linux Operating Systems. 
Development can be done using any Unix-like environment such as MacOS (BSD based) or Desktop Linux (Ubuntu, Mint).

While the number of targets for backend software is much smaller than for front end software the number of frameworks and Languages
that you are able to use is much larger. Below is a list of commonly used languages/frameworks that can target POSIX compatible systems. 

| Language   | Framework(s)           |
|------------|------------------------|
| Java       | J2E, Hibernate, Spring |
| Python     | Django, Flask          |
| Ruby       | Rails                  |
| Golang     | net/http               |
| Elixir     | Phoenix                |
| Javascript | Node.js                |

TOOD: Mention databases, NoSQL vs SQL. 

## Fullstack Software Engineer

It should be relatively obvious what a fullstack software engineer is by now. 
This is a generalist role, often seen in smaller companies which can't afford to have an engineer for every indivudal role. 
The job of a fullstack engineer is to manage all aspects of an application. This means being competent in:

- HTML
- CSS
- Javascript
- At least one backend language/framework

As of late it has become very common for companies to look for this set of skills in an applicant.
For that reason the focus of this tutorial will be on developing a set of skills wherein one could describe themselves
as a fullstack engineer. 

Due to personal experience/biases the backend language/framework I will be focusing on is Golang. 
Information on golang (referred to simply as Go from here on out) can be found [here](https://golang.org/). 
I will not be using any batteries included frameworks as they aren't considered idiomatic go. 

For the front end I will obviously be using the standard stack of HTML, CSS and Javascript.
I will also be using React as the framework for frontend development. 
This will be paired with Redux for creating SPAs (Single Page Apps).

# Step 1: Getting a grasp on syntax

For a true beginner, with no prior programming experience, code syntax can be daunting. 
For this reason I recommend starting with a guided, step by step tutorial. 

At this time I'm going to recommend starting with Codecademy's Javascript class [here](https://www.codecademy.com/learn/learn-javascript).

This is a relatively short tutorial that will give you a good base understanding of the most popular programming language on the planet. 
Additionally I feel that javascript provides a good balance of C-style syntax while allowing some aspects of functional programming.

In addition to this tutorial you should be somewhat familiar with HTML and CSS, I'll once again recomment Codecademy's course [here](https://www.codecademy.com/learn/learn-html-css).

For Go I believe the best introduction is [A Tour of Go](https://tour.golang.org/welcome/1) followed by 
[How to Write Go Code](https://golang.org/doc/code.html) and finally [Effective Go](https://golang.org/doc/effective_go.html).
This should give you a relatively good understanding of the syntax and some of the standard library. 

# Step 2: Basic Golang Web Router

# Step 3: Hello World SPAs

# Miscellaneous skills

## The command line

The command line is an extremely powerful tool for navigating a file system and manipulating files. 
Initially it can be intimidating to a user who is used to a GUI such as Finder or Explorer. 

A good starting point for this is Codecademy's tutorial [here](https://www.codecademy.com/learn/learn-the-command-line).

When playing around on your personal computer you can access the command line through a terminal application.

## The Cloud







 