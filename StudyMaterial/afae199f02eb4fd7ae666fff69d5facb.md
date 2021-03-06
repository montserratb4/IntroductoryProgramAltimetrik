---
title: "[]{#_urcwq4z7wc3h .anchor}**Become a Front End Developer** "
---

**with Altimetrik \| 2nd Edition**

**Documentation**

\[Montserrat Briceño\]

# Index

**2**

**Agile methodology**

Agile methodology, centered on software development, focuses on the idea
of repetitive development involving the constant collaboration of all
interested parts of the project at all stages. It helps the team to
deliver the product with a better quality in less time than expected.
![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image12.jpg){width="3.7031255468066493in"
height="2.505323709536308in"}

Agile methodologies promote disciplined project management, encouraging
self-organization and teamwork, as well as frequent inspection and
adaptation of the field we're working on. It's intended for a fast and
high-quality delivery of the projects to make.

This method begins with a description of the product from the client
towards the work team, how it is supposed to function and what for. This
step helps the team to certainly know the expectations of the client.
Once the project starts, the work team plans the path to follow, the
execution and evaluation of said project, which might change in the
future to guarantee a better adaptation for the client\'s wants and
needs.![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image8.png){width="3.7021259842519685in"
height="2.932292213473316in"}

As said, all parts are involved in this, so it is fundamental for
everyone to keep in touch with the process to achieve a better final
product.

## **Scrum** 

Scrum is a subset of agile. In fact, it's the most used subset of agile
methodologies. It is most often used to manage complex software
development using iterative incremental practices. This method increases
productivity and reduces time compared to the waterfall processes. Scrum
enables rapid and smooth adjustments to the changes that the project may
present over time and allows more control over the project status by
needing the team to have regular meetings to discuss where the project
is heading.

These meetings include daily short meetings to dissipate doubts and an
extended weekly meeting to discuss more deeply how the project is going.

Scrum requires a Scrum master to provide an environment where:

1.  A product owner orders the work for a complex problem into a product
    > backlog.

2.  The scrum team turns a selection of the work into an Increment of
    > value during a Sprint.
    > ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image25.jpg){width="4.151042213473316in"
    > height="3.6746926946631673in"}

3.  The scrum team and its stakeholders inspect the results and adjust
    > for the next sprint.

4.  Repeat!

A sprint is a short period of time in which a scrum team works to
complete a set amount of work. Sprints are placed in the heart of scrum
and agile methodologies and they're the base to an efficient and
lightweight work.

## **Kanban**

Kanban is also a subset of agile. It's a framework that organizes tasks
by cards added to different columns on a board.

Columns are divided into: backlog, to do, doing, blocked and done. Each
card must be moved to its corresponding column until
*done*.![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image18.png){width="3.4218755468066493in"
height="2.1002854330708662in"}

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image2.png){width="6.5in"
height="2.5797036307961503in"}

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image26.png){width="3.369792213473316in"
height="3.088975284339458in"}

## **Extreme Programming (XP)**

It belongs to the subsets of agile methodologies as well. Instead of
delivering everything you could possibly want on some date far in the
future, this process delivers the software you need as you need it. This
process encourages developers to respond to customer changes even late
in the cycle of said project.

XP emphasizes teamwork and self-organization as any agile methodology;
managers, customers and developers are all equal partners in a
collaborative team. Implements a simple (yet effective) environment
enabling teams to become highly productive. Extreme Programming develops
a software project in five essential ways: constant and efficient
[communication]{.ul} between all parts involved, a [simple]{.ul} and
clean model of the project, [feedback]{.ul} from testing the project
with the customer, [respect]{.ul} between the team members and their
work, and [courage]{.ul} to respond to future changes and criticism.

## **Git**

Git is a version control system designed for efficiency, confidentiality
and compatibility between all the versions of the project to modify.

What makes it different from other models is its branching
functionality. Git encourages developers to have multiple branches that
can be entirely independent from each other. The creation, merging
(combination) and deletion of said branches takes seconds.

This means you can switch between branches without editing the main one,
have several branches for specific functions, and even create a branch
to experiment with without altering the main branch. Think about it as a
tree! You can cut off one branch, take off some leaves, even paint a
branch if you like, but the trunk itself is never affected. To do this,
we use commands!

### 10 most used commands: 

-   *Git clone:* this command makes an identical copy of the latest
    > version of a project in a repository (an online information
    > deposit) and saves it into your computer. A really easy way to do
    > this is by coding: *git clone
    > \<[[https://name-of-the-repository-link]{.ul}](https://name-of-the-repository-link)\>*

-   *Git branch:* we can use the branch command for, creating, editing
    > and deleting branches.

> To create a new one: *git branch \<branch name\>*. This will create it
> into the local repository.
>
> To push this new branch into the remote repository: *git push -u
> \<remote\> \<branch-name\>*
>
> To view the existent branches: *git branch* or *git branch \--list*
>
> To delete a branch: *git branch -d \<branch-name\>*

-   *Git checkout:* to work on a branch, first we need to switch to it.
    > We use this command to switch from one branch to another. We can
    > also use it for checking out files and commits: *git checkout
    > \<name-of-your-branch\>.*

> To successfully switch between branches you need to follow these
> steps:

-   The changes in your current branch must be committed or stashed
    > before you switch.

-   The branch you want to check out should exist in your local

Of course, there's a shortcut command that allows you to do combine
these and save time: *git checkout -b \<name-of-your-branch\>*

-   *Git status:* this command gives us all the necessary information of
    > the current branch. Like whether the current branch is up to date;
    > whether there is anything to commit, push or even pull; whether
    > there are file to stage, file unstaged or untracked; whether there
    > are files created, modified or deleted. To use it we code: *git
    > status*.

-   *Git add:* when we create, modify or delete a file, these changes
    > will happen in our local and won't be included in the next commit
    > unless we change the configurations. In order to do this, we need
    > to use the git add command to include the changes of a file into
    > our next commit. To add a single file: *git add \<file\>.* And to
    > add everything at once: *git add -A.* We need to make clear that
    > this command DOES NOT change the repository and changes are NOT
    > saved until we use git commit.

-   *Git commit:* used for saving our changes, it's like a checkpoint in
    > a videogame where we can go back later if needed. We need to write
    > a little message to explain what we have developed or changed in
    > the code: *git commit -m "commit message".* This command saves
    > your changes only locally.

-   *Git push:* this one submits your commits to the remote repository:
    > *git push \<remote\> \<branch-name\>*

-   Nonetheless, if your branch is fresh out of the oven, you also need
    > to upload the branch with this command right here: *git push -
    > -set-upstream \<remote\> \<name-of-your-branch\>* or *git push -u
    > origin \<branch_name\>.* This command only uploads changes that
    > are commited.

-   *Git pull:* this command is used to get updates from the remote
    > repository. It gets the updates from the repository and
    > immediately applies the latest changes into your local: *git pull
    > \<remote\>.*

-   *Git revert:* this one is used to undo our changes locally or
    > remotely, [carefully.]{.ul} To see our commit history, we need to
    > use *git log--online.* Then we just need to specify the code next
    > to our wanted commit: *git revert \<commit number\>.* This action
    > will deploy a window like this one but we just have to press
    > *shift + q* to
    > exit.![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image15.png){width="3.4583333333333335in"
    > height="2.1041666666666665in"}

> The git command will undo the given commit, but will create a new
> commit without deleting the older one. The advantage of using this
> little command is that it doesn't touch the commit history, with which
> you can still see all of the previous information in your history,
> even the reverted ones.
>
> Another advantage is that everything happens in our local system
> unless we push it into the remote repository. This is why git revert
> is safer to use.

-   *Git merge:* this command is the final step, for when you've
    > completed development in your branch and you are sure that
    > everything works just fine. We are going to merge the branch
    > (including all of its commits) with the dev branch using: *git
    > merge.* It's important to keep in mind that you first need to be
    > on the specific branch you want to merge with your feature branch.

> First, we need to switch to the dev branch by using: *git checkout
> dev*. Before merging, we have to update our local dev branch by
> coding: *git fetch*. Finally, we can merge the feature branch into the
> dev branch by using: *git merge \<branch-name\>.* Make sure our dev
> branch has the latest version before we merge our branches, or we may
> have some conflicts to resolve.

###  **Tags and commits:**

A tag is a feature of git. A specific point in the repository can be
identified by defining the tag for that point. It is used to move
between versions of the repository without altering them. The tag can be
created for a specific commit of the git history. It\'s better to know
how to create the tag for the repository before adding a tag to a
specific commit.

To create a new tag, we need to execute: *git tag \<tagname\>.* We
substitute *tagname* with a specific semantic name. A common pattern to
use are numbers of the version, like *1.04.2.*

###  **Stash**

This command (*git stash)* stores temporally the changes that have been
made in the code we\'re working on so we can work on another code and,
later on, we can come back and apply the wanted changes. It is practical
if you need to deal with other things constantly and rapidly but you
don\'t have the changes in the code finished to confirm and submit. Keep
in mind that the stash is only local and changes effectuated don\'t
transfer to the server when uploaded to the repo.

At this point, we have the liberty to go to another branch and put in
practice all we\'ve learned before with git, then once we\'re ready,
come back and apply the stash.

We can also apply a stash change using the command *git stash pop*. Once
we *pop* the stash, changes in it will be deleted and applied again to
the code we\'re working on.

Another option is to apply again the changes in the code we\'re working
on and keep them in our stash using the command *git stash apply.* This
is really useful if you want to apply the same changes of a stash in
several branches.

Also, we can use *git stash* multiple times to create several *stashes*,
and then use *git stash list* to visualize them. We can identify slashes
by the word \"WIP\" which stands for \"work in progress\" in the upper
part of the branch.

###  **Hooks**

This is the way git has to fire off custom scripts when certain
important actions occur. They can be divided in two groups: server-side
and client-side. Client-side Hooks are triggered by operations such as
committing and merging. While server-side hooks run on network operation
such as receiving pushed commits. The most used commands are
*pre-commit* and *pre-push.*

###  **Branching strategies and GitFlow**

A branching strategy is a set of rules that a work team develops when
writing, merging and deploying code when using a VCS. These rules enable
the team the possibility of stipulating how they interact with a shared
codebase.

Such strategy is necessary as it helps to keep the repository organized
to avoid errors in its application.
![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image4.png){width="3.1458333333333335in"
height="1.7395833333333333in"}

GitFlow is a branching strategy. This one enables parallel development
in a branch separated from the main branch. After said changes, the
developer merges this branch into the main one. This branching strategy
consist of these branches:

-   Main.

-   Development.

-   Feature (to develop new features that branches off the develop
    > branch).

-   Release (to help a new production release; usually branched from the
    > develop branch and must be merged both into the develop and main
    > branches).

-   Hotfix. This one also helps to prepare for a release, but -unlike
    > the release one- the hotfix branch will emerge if there's a bug
    > that needs to be solved. It enables developers to work on a
    > different branch while said bug is being fixed.

The *main* and the *develop* branches are considered to be the main ones
to work on, while the rest are supportive branches that are meant to
help developers to, well, develop, and are usually short-lived.

###  **Rebase**

In git, this is a command that integrates the changes from one branch to
another, and works as an alternative for the "merge" command. Most
visibly, this command differs from the other by rewriting the commit
history in order to produce a 'linear' succession of commits.

To do this we code *git rebase*.

###  **Squash**

With this command, we can combine multiple commits into one. We can do
this at any point in time but it's most often used when we want to
finally merge a branch. It's important to note that there's no *git
squash* to do this, it's an option when using other commands like rebase
or merge.

Teams often use 'squashing' when they have way too many commits and
prefer to use only one, however, in teams with junior developers, it's
not that common so as they won't have the commit history to check on.

### **Rebase vs merge**

  Rebase                                                                                             Merge
  -------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------
  Allows developers to integrate changes from one branch to another.                                 This command allows developers to merge branches.
  Logs are linear in git rebase as the commits are rebased.[^1]                                      With this one, the logs will be showing the complete history of the merging of commits.
  All the commits will be rebased and the same number of commits will be added to the main branch.   All the commits on the feature branch will be combined as a single commit in the main branch.
  This **should** be used when the target branch is a private branch.                                Merge is used when the target branch is a shared branch.

# ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image1.png){width="3.71875in" height="1.8333333333333333in"}

# 

# 

# 

# 

# **JavaScript**

It's the third part of the holy trinity of programming along with HTML
and CSS. JavaScript is a programming language or a commands' sequence
that allows us to implement complex functions in a web page. This
language is oriented to objects and gives the webpage its functionality.

Having previous knowledge in HTML and CSS is a recommendation to take
care of.

### **Syntax**

This is the set of rules under which JS programs are constructed.

To create a variable:

var x;

var y;

To use them:

x = 5;

y = 6;

let z = x + y;

The JS syntax defines two types of values: fixed and variable. Fixed
values are called "literals" and variable values are called "variables".

### [Concepts to keep in mind]{.ul}

-   Object oriented programming (OOP): is a programming style that
    > relies on the concept of classes and objects. It is used to
    > structure a software program into simple, reusable pieces of code
    > blueprint (called classes), which are used to create individual
    > instances of objects.

-   Class: it's an abstract blueprint used to create more specific,
    > concrete objects. Classes often represent wide categories like
    > "car" or "dog" that share attributes. These classes define what
    > attributes an instance of this type will have, like *color*, but
    > not the value of those attributes for a specific object. Classes
    > can also contain functions, called *methods* that are available
    > only to objects of that type. These functions are defined within
    > the class, and perform some action helpful to that specific type
    > of object.
    > ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image16.png){width="4.109375546806649in"
    > height="3.9411548556430445in"}

    -   Class templates: these are used as a blueprint to create
        > individual objects. These represent specific examples of the
        > abstract class, like *myCar* or *goldenRetriever*. Each object
        > can have unique values to the properties defined in the class.

```{=html}
<!-- -->
```
-   Variable: it is a value that can change, depending on conditions or
    > on information passed to the program. Typically, a program
    > consists of instructions that tell the computer what to do and the
    > data that the program uses when it's running. Echa data type
    > prescribes and limits the form of the data. In OOP, each object
    > contains the data variables of the class it is an instance of. The
    > object's methods are designed to handle the actual values that are
    > supplied to the object when said object is being used.

> JavaScript variables can be: numbers, strings, objects, arrays and
> functions. For example:
> ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image24.png){width="7.753871391076116in"
> height="2.9276071741032372in"}
>
> There are four ways to declare a JavaScript variable:

-   Using *var*

-   Using *let*

-   Using *const*

-   Using nothing :)

[When to use *var*]{.ul}

Always declare JS variables using one of the options above. The *var*
keyword is used in all JS code from 1995 to 2015. The *let* and *const*
keywords were added to JavaScript in 2015, so if we want our code to run
in older browsers, we must use *var*.

[When to use *const* and *let*]{.ul}

If we want to generalize a rule, we must declare the variables with
*const*. If the value of the variable can change, we use *let*.

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image9.png){width="7.193349737532809in"
height="2.766673228346457in"}

### **Hoisting** 

This is JS' default behavior of moving declarations to the top.

In JavaScript, a variable can be declared after it has been used. In
other words, a variable can be used before it has been declared. The
next examples give the same results:

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image6.png){width="6.296875546806649in"
height="2.1960629921259844in"}

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image23.png){width="6.306590113735783in"
height="1.8941294838145233in"}

To understand this term better, we can say that hoisting is javaScript's
default behavior of moving all declarations to the top of the current
scope (to the top of the current script or the current function).

Variables defined with *let* and *cons* are hoisted to the top of the
block, but not *initialized*. Meaning that the block of code is aware of
the variable, but it can't be used until it has been declared. Using a
*let* variable before it's declared will result in a
[ReferenceError]{.ul}*.* The variable is in a "temporal dead zone" from
the start of the block until it is declared.

JS only hoists declarations, not initializations.

Hoisting is, mostly, an unknown or overlooked behavior of JS. if a
developer does not understand hoisting, programs may contain bugs. To
avoid them, we tend to always declare variables at the beginning of
every scope. It is always a good practice since this is how JavaScript
interprets the code. It is important to note that JS in strict mode
doesn't allow variables to be used if they are not declared.

### **DOM**

With the object model, JavaScript gets all the power it needs to create
dynamic HTML:

-   It can change: all the HTML elements in the page, all the HTML
    > attributes in the page and all the CSS styles in the page.

-   It can remove existing HTML elements and attributes.

-   It can add new HTML elements and attributes.

-   It can react to all existing HTML events in the page.

-   It can create new HTML events on the page.

The HTML DOM is a standard object model and programming interface for
HTML and it defines:

-   The HTML elements as objects.

-   The properties of all html elements.

-   The methods to access all HTML elements.

-   The events for all HTML elements.

Basically, is a standard for how to get, change, add or delete HTML
elements.

### **Scope** 

It determines the accessibility (visibility) or variables. There are
three types of scope: block scope, function scope and global scope.

[Block scope]{.ul}

It is provided by the keywords *let* and *const*. Variables declared
inside a { } block can't be accessed from outside the block. For
example:

{

let x = 2;

}

/ / x can not be used here

Variables declared with the *var* keyword cannot have block scope.
Variables declared inside a { } block can be accessed from outside the
block. For example:

{

var x = 2;

}

/ / x can be used here

[Local scope]{.ul}

Variables declared within a JS function become local to the function.
For example:

/ / code here can not use carName

function myFunction() {

let carName = "Volvo";

/ / code here can use carName

}

/ / code here can not use carName

Local variables have Function Scope, they can only be accessed from
within the function.

Since local variables are only recognized inside their functions,
variables with the same name can be used in different functions. Local
variables are created when a function starts and deleted when the
function is completed.

[Function scope]{.ul}

With this, each function creates a new scope. Variables defined inside a
function are not accessible (visible) from outside the function.
Variables declared with *var, let* and *cons* are quite similar when
declared inside a function. They all have function scope:

function myFunction() {

var carName = "Volvo"; / / Function Scope

}

function myFunction() {

let carName = "Volvo"; / / Function Scope

}

function myFunction() {

const carName = "Volvo"; / / Function Scope

}

[Global JavaScript Variables]{.ul}

A variable declared outside a function, becomes global. For example:

let carName = "Volvo";

/ / code here can use carName

function myFunction() {

/ / code here can also use carName

}

If a global variable has global scope, all scripts and functions on a
web page can access it.

[Global scope]{.ul}

Variables declared globally, or outside any function, have global scope.
These variables can be accessed from anywhere in a JS program. Variables
declared with *var, let* and *cons* are similar when declared outside a
block. For example:

var x = 2; / / global scope

let x = 2; / / global scope

const = 2; / / global scope

### **Strict mode** 

"Use strict" it's not a statement, but a literal expression. Its purpose
is to indicate that the code should be executed in "strict mode". With
this mode we can't, for example, use undeclared variables. All modern
browsers support this mode except Internet Explorer 9 and lower. It
helps us write a cleaner code.

Strict mode is declared by adding ["use strict";]{.ul} to the beginning
of a script or a function. By being declared at the beginning of a
script, it has global scope, meaning that all the code in the script
will be executed in strict mode. For example:

"use strict";

x = 3.14; / / this will cause an error because x is not declared

"use strict";

myFunction();

function myFunction() {

y = 3.14;

} / / this will also cause an error because y is not declared

Declared inside a function, it has local scope, that means that only the
code inside the function is in strict mode:

x = 3.14; / / this will not cause an error.

myFunction();

function myFunction() {

"use strict";

y = 3.14;

} / / this will cause an error

[Syntax]{.ul}

The syntax for declaring strict mode was designed to be compatible
versions of JS. Compiling a numeric literal (4+5;) or a string literal
("John Doe\'\';) in a JavaScript program has no side effects, it just
compiles to a non existing variable and dies. ["use strict";]{.ul} only
matters to new compilers that "understand" the meaning of it.

Strict mode makes it easier to write "secure" JS. It changes previously
accepted "bad syntax" into real errors. For example in normal JS,
mistyping a variable name creates a new global variable; with strict
mode, this will throw an error, making it possible to accidentally
create a global variable. In normal JS, a developer won't receive any
error feedback assigning values to non-writable properties; in strict
mode, any assignment to a non-writable property, a getter-only property,
a non-existing property, a non-existing variable or a non-existing
object, will throw an error.

[What is not allowed in strict mode]{.ul}

-   Using a variable without declaring it (objects are variables too).

-   Using an object without declaring it.

-   Deleting a variable or object.

-   Deleting a function.

-   Duplicating a parameter name.

-   Octal numeric literals.

-   Octal escape characters.

-   Writing to a read-only property.

-   Writing to a get-only property.

-   Deleting an undeletable property.

-   The word *eval* can't be used as a variable.

-   The word *arguments* cannot be used as a variable.

-   The *with* argument is not allowed.

-   For security reasons, *eval()* is not allowed to create variables in
    > the scope from which it was called.

-   The *this* keyword in functions behaves differently in strict mode.
    > It refers to the object that called the function. If the object is
    > not specified, functions in strict mode will return *undefined*
    > and functions in normal mode will return the global object
    > (window).

-   Keywords reserved for future JS versions can't be used as variable
    > names in strict mode. They are: implements, interface, let,
    > package, private, protected, public, static, yield.

It is important to note that the "use strict" directive is only
recognized at the beginning of a script or a function.

###  **Fetch** 

JS can send network requests to the server and load new information
whenever it's needed. We can use a network request to: submit an order,
load user information, receive latest updates from the server, etc.
without reloading the page. There are multiple ways to send a network
request and get information from the server and the *fetch()* method is
a modern and versatile one. It is not supported by older browsers but
it's very well supported by modern ones.

The basic syntax is:

let promise = fetch(url, \[options\])

*url* being the URL to access and *options* the optional parameters,
like method, headers, etc.

Without *options* this would be a simple GET request, downloading the
contents of the url.

The browser starts the request right away and returns a promise that the
calling code should use to get the result. Getting a response is usually
a two-stage process:

First, the *promise*, returned by *fetch*, resolves with an object of
the built-in response class as soon as the server responds with headers.

At this stage, we can check HTTP status, to see whether it is successful
or not, check headers, but do not have the body yet.

The promise rejects if the *fetch* was unable to make HTTP-request, (for
example: network problems), or there is no such site. Abnormal
HTTP-statuses, such as 404 or 500 don't cause an error.

We can see HTTP-status in response properties: *status* (HTTP status in
code) and *ok* (boolean[^2], [true]{.ul} if the HTTP status code is
200-299). For
example:![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image20.png){width="5.692708880139983in"
height="1.3998458005249343in"}

# 

# 

# 

Then, to get the response body, we need to use an additional method
call. *Response* provides multiple promise-based methods to access the
body in various formats: *response.text()* (to read the response and
return as text), *response.json()* (to parse the response as JSON[^3]),
*response.formData()* (returns the response as *FormData* object),
*response.blob()* (returns the response as [Blob]{.ul}, a binary data
with type), *response.arrayBuffer()* (returns the response as
[ArrayBuffer]{.ul}, a low level representation of binary data).
Additionally, *response.body* is a ReadableStream object, it allows us
to read the body chunk-by-chunk.

It's important to note that we can choose only one body-reading method.
If we have already got the response with *response.text()*, then
*response.json()* won't work, as the body content has already been
processed.

We also have [response headers]{.ul}. They are available in a Map-like
headers object in *response.headers*. It's not exactly a Map, but it has
similar methods to get individual headers by name or iterative over
them.

To set a request header in *fetch*, we can use the *headers* option. It
has an object outgoing headers, like
this:![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image7.png){width="6.339645669291339in"
height="1.1389873140857394in"}

There's a list of HTTP headers that we can't use, though:
*Accept-Charset*, *Accept-Encoding*, *Access-Control-Request-Headers*,
*Access-Control-Request-Method*, *Connection*, *Content-Length*,
*Cookie*, *Cookie2*, *Date*, *DNT*, *Expect*, *Host*, *Keep-Alive*,
*Origin*, *Referer*, *TE*, *Trailer*, *Transfer-Encoding*, *Upgrade*,
*Via*, *Proxy-\**, *Sec-\**.

These headers ensure proper and safe HTTP, so they are controlled
exclusively by the browser.

To make a [POST request]{.ul}, or request with another method, we need
to use *fetch* options:

-   *method:* HTTP-method, for example: *POST*.

-   *body:* the request body, one of:

    -   a string (JSON-encoded).

    -   *FormData* object, to submit the data as *multipart/form-data*.

    -   *Blob* / *BufferSource* to send binary data.

    -   URLSearchParams, to submit the data in *x-www-form-urlencoded*
        > encoding, which is rarely used.

The JSON format is used most of the time. If the request *body* is a
string, then *Content-Type* header is set to *text/plain;charset=UTF-8*
by default. When we're going to send JSON, we use *headers* option to
send *application/json* instead, the correct *Content-Type* for
JSON-encoded data.

We can also submit binary data with *fetch* using *Blob* or
*BufferSource* objects.

To summarize:

A typical fetch request consists of two *await* calls:

let response = await fetch(url,options); / / resolves with respone
headers

let result = await response.json(); / / read body as json

Or without await:

fetch(url, options)

.then(response =\> response.json())

.then(result =\> /\* process result \*/)

Response properties:

-   response.status (the HTTP code of the response).

-   response.ok (*true* if the status is 200-299).

-   response.headers (a map-like object with HTTP headers).

Methods to get response body:

-   response.text(): returns the response as text.

-   response.json(): to parse the response as JSON object.

-   response.formData(): returns the response as FormData object.

-   response.blob(): returns the response as Blob (binary data with
    > type).

-   response.arrayBuffer(): returns the response as ArrayBuffer
    > (low-level binary data).

Fetch options so far:

-   method: HTTP method.

-   headers: an object with request headers (not any header is allowed).

-   body: the to send (request body) as *string, FormData, BufferSource,
    > Blob* or *UrlSearchParams* object.

# 

### **AJAX**

It stands for Asynchronous JavaScript And XML. It is not a programming
language, just uses a combination of: a browser built-in XMLHttpRequest
object (to request data from a web server) and JavaScript and HTML DOM
(to display or use the data. AJAX applications might use XML to transfer
data, but it is equally common to transport data as plain text or JSON
text.

AJAX allows web pages to be updated asynchronously by exchanging data
with a web server behind the scenes, this means that it's possible to
update parts of a web page without reloading the whole page.

\` It works like this:

First, an event occurs in a web page (like the page being loaded or a
button being clicked); then, an XMLHttpRequest object is created by JS;
the XMLHttpRequest object sends a request to a web server and the server
processes the request; then, the server sends a response back to the web
page and the response is read by JS to finally perform a proper action
(like a page update).

Modern browsers can use Fetch API instead of the XMLHttpRequest Object.
This allows the web browser to make HTTP requests to web servers.

All modern browsers support the XMLHttpRequest object. It can be used to
exchange data with a web server behind the scenes. This means that it is
possible to update parts of a web page, without reloading the whole
page.

All modern browsers have a built-in XMLHttpRequest object. The syntax
for creating said object is: *variable = new XMLHttpRequest();*

A callback function is a function passed as a parameter to another
function. In this case, the callback function should contain the code to
execute when the response is ready.

xhttp.onload = function() {

/ / what to do when the response is ready

}

To send a request to a server, we can use the open() and send() methods
of the XMLHttpRequest object:

xhttp.open("GET", "ajax_info,txt");

xhttp.send();

It is important to note that, for security reasons, modern browsers do
not allow access across domains. This means that both the web page and
the XML file it tries to load, must be located on the sme server.

These are the XMLHttpRequest object methods and their description:

-   new XMLHttpRequest(): creates a new XMLHttpRequest object.

-   abort(): cancels the current request.

-   getAllResponseHeaders(): returns header information.

-   getResponseHeader(): returns specific header information.

-   open(*method, url, async, user, psw*): specifies the request.

    -   *method:* the request type GET or POST.

    -   *url:* the file location.

    -   *async:* true (asynchronous) or false (synchronous).

    -   *user:* optional user name.

    -   *psw:* optional password.

```{=html}
<!-- -->
```
-   send(): sends the request to the server. Used for GET requests.

-   send(*string*): send the request to the server. Used for POST
    > requests.

-   setRequestHeader(): adds a label/value pair to the header to be
    > sent.

These are the XMLHttpRequest object properties and their descriptions:

-   onload: defines a function to be called when the request is received
    > (loaded).

-   onreadystatechange: defines a function to be called when the
    > readyState property changes.

-   readyState: holds the status of the XMLHttpRequest.

    -   0: request not initialized.

    -   1: server connection established.

    -   2: request received.

    -   3: processing request.

    -   4: request finished and response is ready.

```{=html}
<!-- -->
```
-   responseText: returns the response data as a string.

-   responseXML: returns the response data as XML data.

-   status: returns the status-number of a request:

    -   200 for "OK".

    -   403 for "Forbidden"

    -   404 for "Not Found"

```{=html}
<!-- -->
```
-   statusText: returns the status-text (e.g. "OK" or "Not Found").

With the XMLHttpRequest object we can define a callback function to be
executed when the request receives an answer. The function is defined in
the *onload* property of the XMLHttpRequest object.

If we have more than one AJAX task in a website, we should create one
function for executing the XMLHttpRequest object, and one callback
function for each AJAX task. The function call should contain the URL
and what function to call when the response is ready.

The *readyState* property holds the status of the XMLHttpRequest. The
*onreadystatechange* property defines a callback function to be executed
when the readyState changes. The *status* property and the *statusText*
properties hold the status of the XMLHttpRequest object. The
*onreadystatechange* function is called every time the readyState
changes. When *readyState* 4 and status is 200, the response is ready.

To send a request to a server, we use the open() and send() methods of
the XMLHttpRequest object:

xhttp.open("GET", "ajax_info.txt", true);

xhttp.send();

The url parameter of the open() method, is an address to a file on a
server:

xhttp.open("GET", "ajax_test.asp", true);

The file can be any kind of file, like .txt and .xml, or server
scripting files like .asp and .php (which can perform actions on the
server before sending the response back).

Server requests should be sent asynchronously and the async parameter of
the open() method should be set to true:

> xhttp.open("GET", "ajax_test.asp", true);

By sending asynchronously, the JS doesn't have to wait for the server
response, but can instead: execute other scripts while waiting for
server response and deal with the response after the response is ready.

It's important to note that the default value for the async parameter is
async = true. We can safely remove the third parameter from your code.
And synchronous XMLHttpRequest (async = false) is not recommended
because the JS will stop executing until the server response is ready.
If the server is busy or slow, the application will hang or stop.

GET is simpler and faster than POST, and can be used in most cases.
However, we should always use POST requests when: a cached file is not
an option (update a file or database on the server); sending a large
amount of data to the server (POST has no size limitations); sending a
user input (which can contain unknown characters), POST is more robust
and secure than GET.

A simple GET request looks like this:

xhttp.open("GET", "demo_get.asp");

xhttp.send();

With this example we may get a cached result. To avoid this, we add a
unique ID or URL

xhttp.open("GET", "demo_get.asp?t=" + Math.random());

xhttp.send();

If we want to send information with the GET method, we just add the
information to the URL.

A simple POST request looks like this:

xhttp.open("POST", "demo_post.asp");

xhttp.send();

To POST data like an HTML form, we add an HTTP header with
*setRequestHeader()* and specify the data we want to send in the
*send()* method.

To execute a synchronous request, we change the third parameter in the
*open()* method to *false*. Sometimes async = false are used for quick
testing. We will aso find synchronous requests in older JS code. Ince
the code will wait for server completion, there's no need for an
*onreadystatechange* function.

It's important to note that, since the application will hang or stop if
the server response is not ready, modern developer tools are encouraged
to warn about using synchronous requests and may throw an
InvalidAccessError exception when it occurs.

The *responseText* property returns the server response as a JS string
and we can use it like this:

document.getElementById("demo").innerHTML = xhttp.responseText;

The XMLHttpRRequest object has an in-built XML parser. The *responseXML*
property returns the server response as an XML DOM object. Using this
property we can parse the response as an XML DOM object.

The *getAllResponseHeaders()* method returns all header information from
the server response, like this:

const xhttp = new XMLHttpRequest();

xhttp.onload = function() {

document.getElementById("demo").innerHTML =

this.getAllResponseHeaders();

}

xhttp.open("GET", "ajax2_info.txt");

xhttp.send();

The *getResponseHeader()* method returns specific header information
from the server response. Like this:

const xhttp = new XMLHttpRequest();

xhttp.onload = function () {

document.getElementById("demo").innerHTML =

this.getResponseHeader("Last-Modified");

}

xhttp.open("GET", "ajax_info.txt");

xhttp.send();

AJAX can be used for interactive communication with an XML file as well
as a database; and it's used to create more interactive applications.

#  

# **HTML**

"HTML" stands for Hyper Text Markup Language. It's one of the three main
used programming languages along with CSS and JavaScript. This one
describes and delimits the skeleton of the web page.

To use this type of language, we need a text editor, like "Visual Studio
Code", to give an example. We also need a web browser. The purpose of a
web browser (like chrome, for example) is to read HTML documents and
display them correctly.

A browser does not display the HTML tags, but uses them to determine how
to display the document.

HTML consists of a series of elements that tell the browser how to
display the content. These elements label pieces of content such as
"this is the heading", "this is a paragraph", "this is a link", etc.

An element is defined by a start tag, some content and an end or closing
tag: \<tagname\> content goes here... \</tagname\>. It is everything
from the start tag to the closing tag. It's important to note that not
all elements need a closing tag, like de \<br\> tag.

### **Elements**

There are several types of elements, but the most basic and common used
ones are:

-   \<!DOCTYPE html\>: is a declaration that establishes this document
    > as a HTML5 document.

-   \<html\>: is the root element of an HTML page.

-   \<head\>: these elements contains meta information[^4] about the
    > HTML page.

-   \<title\>: this element specifies a tite for the page, which is
    > shown in the browser's title bar ir in the page's tab.

-   \<body\>: defines the main content of the page (like the body of a
    > letter), and is a container for all the visible contents such as
    > paragraphs, images, hyperlinks, headings, etc.

-   \<div\>: divides the content in sections. Visually, it does nothing
    > to the page, but helps to organize the code.

-   \<h1\>: stands for heading and defines, of course, a heading. There
    > are also other sizes of heading, \<h2\>, \<h3\>, \<h4\>, etc. each
    > one will be smaller as the number increases. We can use these to
    > create titles, subtitles, and so on.

-   \<p\>: this element describes a paragraph.

-   \<strong\>: makes the text bold.

-   \<em\>: stands for "emphasize" and changes the text's font into
    > cursive.

-   \<small\>: makes the text smaller, really subtle.

-   \<ul\>: stands for "unordered list" and closes vertically just like
    > the html, head and body tags. Between these tags we code \<li\>
    > tags.

-   \<li\>: these provide a list made with ballpoints.

-   \<ol\>: stands for "ordered list" and creates a list organized by
    > numbers starting on 1.

-   \<img\>: is used to add an image. By itself it does absolutely
    > nothing. *Also does not need a closing tag.* To tell the browser
    > what image to show, we use an attribute.

An attribute is something inside the tags that gives more information to
the browser about that tag. For images we use the "src" (source)
attribute like this:

> \<img src= ".png"\>

The .png file has been previously dragged inside of the working sheet;
we just create a path that connects them by using that command. We can
also cluster images inside a folder; in that case instead it would be
coded as:

\<img src= "img/.png"\>

The "alt" attribute is a text representation of the image. It's used to
describe the image for screen readers. Does not have a visual effect, is
for accessibility.

We do not *need* to remember all of these and other commands to be a
good developer, but we *must know* how to use them. We must understand
the bases to create a good path of development.

### **Inputs and forms**

An \<input\> is an element that allows us to create interactive controls
for forms based on the web to collect users information.

An HTML form is used to collect users\' input. The users' input is often
sent to a server for processing.

To create a form for users' input, we use the \<form\> element and it
does have a closing tag. It's a container for different types of input
elements, such as text fields, checkboxes, submit buttons, etc.

The \<input\> element is the most frequently used for forms. This type
of element can be used in many ways, depending on the *type* attribute.
For example:

-   \<input type= "text"\>: displays a single-line text input field.

-   \<input type= "radio"\>: displays a radio button for selecting one
    > of many choices.

-   \<input type= "submit"\>: this one displays a submit button for
    > submitting the form, of course.

-   \<input type= "button"\>: displays a simple clickable button :).

### **HTML vs XHTML**

XHTML stands for "Extensible Hypertext Markup Language\'\' and is
considered as a part of the XML markup language. It can also be
considered as a combination between HTML and XML.

XML is a software and hardware -independent tool for storing and
transporting data. It stands for "eXtensible Markup Language" and was
designed to be self-descriptive. It doesn't do quite anything, it's just
information wrapped in tags.

Someone must write a piece of software to send, receive, store or
display it.

HTML and XHTML were designed with different goals. While HTML5 was
created to solve some of the existing cross-browser compatibility
problems, XHTML was thought of as a more rigorous version of HTML.

Some of the main differences:

-   HTML accepts that not all the elements present a closing tag,
    > whereas XHTML expects that all elements with no exception include
    > a closing tag.

-   XHTML requires that all attribute values, like the font size, are
    > quoted, even the numeric ones. Which does not happen with HTML.

-   For a document to be valid with XHTML, attributes can not be
    > minimized.

### **Data attributes**

They allow us to store additional information about an HTML element
without having to look for other more complex ways to do so and it's
used as *data-\*,* being "\*" the kind of data we want to store. For
example, inside of a list we could have:

\<li data-animal-type="bird"\>Owl\</li\>

This attribute allows us to lock up custom data on all HTML elements.

It consists of two parts:

-   The attribute name should not have any uppercase letters and must be
    > at least one character long after the "data-"

-   The attribute value can be any string.

### **Accessibility** 

It is a good practice to always try to code HTML keeping accessibility
in mind as it provides the user a good way to navigate and interact with
our site.

We always try to make our HTML code as semantic as possible, this means
that we are using the correct element for their correct purpose.
Semantic elements are elements with a specific meaning; if you want a
button, then use the \<button\> element.

Having a semantic HTML code provides non-vident users to have a
comfortable experience with our page providing screen readers the
context they need to read the information out loud.

> Continuing with the button example:

-   Buttons have more suitable styling by default.

-   A screen reader identifies it as a button.

-   They are clickable :D.

A button is also accessible for users relying on keyboard-only
navigation, as it can be clicked with both keyboard and mouse.

Some examples of semantic elements are: \<form\>, \<table\> and
\<article\> as it clearly defines its content. And some non-semantic
elements are: \<div\> and \<span\> as it does not clarify its content.

Headings are also important for the accessibility of users, as search
engines use the headings to index the content of our web page. It is
important to use them to organize the document structure and the
relationship between different sections of said document. Screen readers
also use headings as a navigational tool! The difference between
headings specify the outline of the page, starting by \<h1\> as the most
important and going down.

Remember also the \<alt\> element, mentioned earlier and used to give an
readable alternative to an image.

We can (and should) even declare the language at the beginning inside
the \<html\> tag, like this: \<html lang="en"\>. With this we can
provide some assistance to the browsers and engines.

A clear an easy to understand language is a must, we try as much as
possible to avoid characters that can't be read by a screen reader,
following rules like:

-   Keeping sentences as short as we can.

-   Avoiding dashes. Instead of "1-3", we type "1 to 3".

-   Avoiding abbreviations and slang words.

Creating good link texts is also really valuable. A link text should
explain clearly what information the user is gonna get when clicking on
it. A good link text example is "learn more about HTML accessibility"
instead of "click here" or "read more".

# **SEO**

Stands for "Search Engine Optimization" and it is the process of
improving your website so the visibility of it can be increased when
people search for products or services related to your page in a search
engine. The better visibility your site gets, the more likely you are to
gain attention and attract existing customers to your business.

Search engines use bots to crawl pages on the web, going between sites
and gathering information about said pages and putting them into an
index to help us find exactly what we're looking for.

Next, an algorithm analyzes the pages on the index taking into account
hundreds of ranking factors or signals to determine the order in which
pages should appear in the search results.

# **DOM** 

The Document Object Model is a programming API (Application Programming
Interface) for HTML and XML documents and it defines the logical
structure of documents and the way the document is accessed and
manipulated.

With this, we can create and build documents, navigate their structure
and add, modify or delete elements and content. Anything found in an
HTML or XML document can be accessed, modified, deleted or added using
the DOM.

One important objective for the DOM is to provide a standard programming
interface that can be used in a wide variety of environments and
applications. The Document Object Model can be used with any programming
language.

With this, documents have a logical structure which resembles very much
like a tree or a mental map. This model specifies the logical model for
the programming interface and this logical model may be implemented in
any way that a particular implementation finds convenient. For example,
we'll take this extract from an HTML document:

\<TABLE\>

\<ROWS\>

\<TR\>

\<TD\>Shady Grove\</TD\>

\<TD\>Aeolian\</TD\>

\</TR\>

\<TR\>

\<TD\>Over the River, Charlie\</TD\>

\<TD\>Dorian\</TD\>

\</TR\>

\</ROWS\>

\</TABLE\>

The Document Object Model will represent it like this:

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image17.png){width="4.598958880139983in"
height="2.725308398950131in"}

# 

# 

# 

# 

# **CSS**

Along with HTML and JS, CSS is part of the most used programming
languages. If HTML focuses on the skeleton of the page and JS on its
functionality, CSS will be focused on the styling of said page.

CSS stands for "Cascade Styling Sheet" and describes how HTML elements
should be displayed. It saves a lot of work and can control the layout
of multiple web pages all at once. It's used to define styles for our
web pages, including the design, layout and variations in display for
different devices and screen sizes.

###  **Syntax** 

A CSS rule consists of a selector and a declaration
block.![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image21.png){width="4.359375546806649in"
height="1.059359142607174in"}

The selector points out the HTML element we want to style. The
declaration block contains one or more declarations separated by
semicolons. Each declaration includes a CSS property name and value,
separated by a colon. Multiple CSS declarations are separated with
semicolons, and declaration blocks are surrounded by curly braces.

### **Selectors** 

Selectors are used to find or select the HTML elements we want to style
and we can divide them into five categories: simple selectors (which are
elements based on name, id, class), combinator selectors (these select
elements based on a specific relationship between them), pseudo-class
selectors (select elements based on a certain state), pseudo-elements
selectors (which select and style a part of an element) and attribute
selectors (that select elements based on an attribute or an attribute
value).

###  **How to integrate CSS**

There are three ways that we can use to insert a style sheet into our
project: with [external CSS]{.ul}, [internal CSS]{.ul} or [inline
CSS.]{.ul}

**External CSS**

With an external style sheet, we can change the look of an entire
website by changing just one file. Each HTML page must include a
reference to the external style sheet file inside the \<link\> element,
inside the \<head\> element.

An external stylesheet can be written in any text editor and must be
saved with a .css extension. The external .css file should not contain
any HTML tags.

It is important to note that we do not add a space between the property
value and the unit.

**Internal CSS**

This one may be used if one single HTML page has a unique style. The
internal style is defined inside the \<style\> element, inside the head
section of an HTML page.

**Inline CSS**

This style may be used to apply a unique style for a single element. To
use inline styles, we must add the attribute to the relevant element.
Said attribute can contain any CSS property. Though, inline styles loses
many of the advantages of a style sheet by mixing content with
presentation; it's recommended to use this method sparingly.

###  **Multiple style sheets**

If some properties have been defined for the same selector/element in
different style sheets, the value from the last read stylesheet will be
used.

###  **Cascading order** 

### All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1.  ### Inline style (inside an HTML element).

2.  External and internal style sheets (in the head section).

3.  Browser default.

### **Specificity** 

If there are two or more CSS rules that point to the same element, the
selector with the highest specificity value will "win" and its style
declaration will be applied to that HTML element.

Specificity could be thought of as a score or rank that determines which
style declarations are ultimately applied to an element. There are four
categories which define the specificity level of a selector:

-   Inline styles: \<h1 style="color: pink;"\>

-   IDs: \#navbar

-   Classes, pseudo-classes, attribute selectors: .test, :hover,
    > \[href\]

-   Elements and pseudo-elements: h1, :before

###  **Box model**

All HTML elements can be considered as boxes.

In CSS, the term "box model" is used when we talk about design and
layout. The CSS box model is essentially a box that wraps around every
HTML element. It consists of: margings, borders, padding and the actual
content. Like this:

The *content* defines the content of the box, where text and images are
shown. The *padding* clears an area around the content and it's
transparent. The *border* goes around the padding and content. The
*margin* clears an area outside the border and it is also
transparent.![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image10.png){width="6.354166666666667in"
height="2.8673906386701664in"}

This model allows us to add a border around elements and to define space
between elements.

[Width and height of an element]{.ul}

In order to set these characteristics correctly in all browsers, we need
to know the box model works. It is important to note that when we set
the width and height of an element in CSS, we just have to set the width
and height of the content area. To calculate the full size of an
element, we must also add padding, orders and margins. For example, this
\<div\> element will have a total width of 350px:

> div {
>
> width: 320px;
>
> padding: 10px;
>
> border: 5px solid gray;
>
> margin: 0;
>
> }

And we calculate it this way:

320px (width)

-   20px (left + right padding)

-   10px (left + right border)

-   0px (left + right margin)

> = 350px
>
> The total width of an element should be calculated like this:
>
> Total element width = width + left padding + right padding + left
> border + right border + left margin + right margin.
>
> The total height of an element should be calculated like this:
>
> Total element height = height + top padding + bottom padding + top
> border + bottom border + top margin + bottom margin.

### **Media queries**

A media query is a CSS technique that uses the "\@media" rule to include
a block of CSS properties only if a certain condition is true. For
example:

If the browser window is 900px or smaller, the background color will be
lightblue:

\@media only screen and (max-width: 600px) {

body {

background-color: lightblue;

}

}![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image5.png){width="5.473958880139983in"
height="3.4385148731408575in"}

Media queries can help for when a web page does not behave equally on
all screen sizes by adding a breakpoint where certain parts of the
design will behave differently on each side of the breakpoint.

It is recommended to always design for mobile first because this will
make the page display faster on smaller devices.

This means that we must make some changes in our CSS. Instead of
changing styles when the width gets smaller than 768px, we should change
the design when the width gets larger than 768px. This will make our
design Mobile First.

We can add as many breakpoints as you like. We will also insert a
breakpoint between tablets and mobile phones. We do this by adding more
media queries (at 600px), and a set of new classes for devices larger
than 600px (but smaller than 768px). If we are working with columns,
having two sets of identical classes gives us the opportunity in HTML to
decide what will happen with the columns at each breakpoint.

There are tons of screens and devices with different heights and widths,
so it is hard to create an exact breakpoint for each device. To keep
things simple you could target five groups.

Media queries can also be used to change the layout of a page depending
on the orientation of the browser. We can have a set of CSS properties
that will only apply when the browser window is wider than its height, a
so called "Landscape" orientation.

Another common use of media queries is to hide elements on different
screen sizes.

We can also use media queries to change the font size of an element on
different screen sizes.

# 

### **Units**

CSS has different units for expressing a length. Many CSS properties
take "length" values, such as *width*, *margin*, *padding*, *font-size*,
etc.

[Length]{.ul} is a number followed by a length unit, such as 10px, 2em,
etc. we can set different length values using px like this:

h1 {

font-size: 60px;

}

p {

font -size: 25px;

line-height: 50px;

}

It is important to note that a whitespace can't appear between the
number and the unit. However, if the value is *0*, the unit can be
omitted. For some CSS properties, negative lengths are allowed.

There are two types of length units: [absolute]{.ul} and
[negative.]{.ul}

Absolute length units are fixed and a length expressed in any of these
will appear as exactly that size. They are not recommended for use on
screen, 'cause screen sizes vary so much. Nonetheless, they can be used
if the output medium is known, such as for print layout. These are the
units and their description:

-   cm: centimeters

-   mm: millimeters

-   in: inches (1in = 96px = 2.54cm)

-   px\*: pixels (1px = 1/96th of 1in)

-   pt: points (1pt = 1/72 of 1in)

-   pc: picas (1pc = 12pt)

\*It's important to note that pixels are relative to the viewing device.

Relative length units specify a length relative to another length
property. These units scale better between different rendering mediums.
These are the units and their description:

-   em: relative to the font-size of the element (2em means 2 times the
    > size of the current font)

-   ex: relative to the x-height of the current font (rarely used)

-   ch: relative to the width of the the "0" (zero)

-   rem: relative to font-size of the root element.

-   vw: relative to 1% of the width of the viewport\*

-   vh: relative to 1% of the height of the viewport\*

-   vmin: relative to 1% of the viewport's\* smaller dimension.

-   vmax: relative to 1% of the viewport's\* larger dimension.

-   %: relative to the parent element.

It is important to note that the em and rem units are practical in
creating a perfectly scalable layout. A viewport is the browser's window
size. If the viewport is 50cmm wide,1vw = 0.

###  **Positioning and layout**

The *position* property specifies the type of positioning method used
for an element. There are five different position value:

-   static

-   relative

-   fixed

-   absolute

-   sticky

Elements are then positioned using the top, bottom, left and right
properties. However, these properties will not work unless the
*position* property is set first. They also work differently depending
on the position value.

[Position: static]{.ul}

HTML elements are positioned static by default. Static positioned
elements are not affected by the top, bottom, left and right properties.
An element with *position: static;* is not positioned in any special
way; it's always positioned according to the normal flow of the page.
Like this:

div.static {

position: static;

border: 3px solid \#73AD21;

}

[Position: relative;]{.ul}

An element with *position: relative;* is positioned relative to its
normal position. Setting the top, right, bottom and left properties of a
relatively-positioned element will cause it to be adjusted away from its
normal position. Other content will not be adjusted to fit into any gap
left by the element. For example:

div.relative {

position: relative;

left: 30px;

border: 3px solid \#73AD21;

}

[Position: fixed;]{.ul}

An element with *position: fixed*; is positioned to the viewport, which
means it always stays in the same place even if the page is scrolled.
The top, right, bottom and left properties are used to position the
element. A fixed element doesn't leave a gap in the page where it would
normally have been located. For example:

div.fixed {

position: fixed;

bottom: 0;

right: 0;

width: 300px;

border: 3px solid \#73AD21;

}

[Position: absolute;]{.ul}

An element with *position: absolute;* is positioned relative to the
nearest positioned ancestor (instead of positioned relative to the
viewport, like fixed). However, if an absolute positioned element has no
positioned ancestors, it uses the document body, and moves along with
page scrolling. It is important to note that absolute positioned
elements are removed from the normal flow, and can overlap elements.

[Position: sticky;]{.ul}

An element with this is positioned based on the user's scroll position.
A sticky element toggles between *relative* and *fixed*, depending on
the scroll position. It is positioned relative until a given offset
position is met in the viewport - then it sticks in place (like
position: fixed). Note that internet explorer does not support sticky
positioning and Safari requires a -webkit- prefix. We must also specify
at least one of *top, right, bottom* or *left* for sticky positioning to
work.

We can also position a text over an image!

###  **Flexible box (flexbox)**

The flexbox layout module makes it easier to design flexible responsive
layout structures without using float or positioning. Before it, there
were 4 layout modes: blacko (for sections in a webpage), inline (for
text), table (for two-dimensional table data) and positioned (for
explicit position of an element).

[Flexbox elements]{.ul}

![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image19.png){width="5.880865048118985in"
height="0.6892782152230971in"}

###  This element represents a flex container (the blue area) with three flex items its coded like this:

\<div class="flex-container"\>

\<div\>1\</div\>

\<div\>2\</div\>

\<div\>3\</div\>

\</div\>

[Parent element (container)]{.ul}

The flex container becomes flexible by setting the *display* property to
*flex*. Like this:

.flex-container {

display: flex;

}

The flex container properties are: *flex-direction, flex-wrap,
flex-flow, justify-content, align-items* and *align-content*.

Flex-direction

This property defines in which direction the container wants to stack
the flex items. The *column* value stacks the flex items vertically
(from top to bottom):

.flex-container {

display: flex;

flex-direction: column;

}

The *column-reverse* value stacks the flex items vertically (from bottom
to top). The *row* value stacks the flex items horizontally (from left
to right) and the *row-reverse* value stacks the flex items horizontally
(for right to left).

Flex-wrap

This property specifies whether the flex items should wrap or not. The
*wrap* value specifies that the flex items will wrap if necessary. Like
this:

.flex-container {

display: flex;

flex-wrap: wrap;

}

The *nowrap* value specifies that the flex items will not wrap. The
*wrap-reverse* value specifies that the flexible items will wrap if
necessary, in reverse order.

Flex-flow

This one is a shorthand property for setting both the *flex-direction*
and *flex-wrap* properties.

Justify-content

This property is used to align the flex items. The *center* value align
the flex items at the center of the container, for example:

> .flex-container {
>
> display: flex;
>
> justify-content: center;
>
> }

The *flex-start* value aligns the flex items at the beginning of the
container (this is default). The *flex-end* value aligns the flex items
at the end of the container. The *space-around* value displays the flex
items with space before, between and after the lines. The
*space-between* value displays the flex items with space between the
lines.

> Align-items

This property is used to align the flex items. The *center* value aligns
the flex items in the middle of the container:

.flex-container {

> display: flex;
>
> height: 200px;
>
> align-items: center;
>
> }

The *flex-start* value aligns the flex items at the top of the
container. The *flex-end* value aligns the flex items at the bottom of
the container. The *stretch* value stretches the flex items to fill the
container (this is default). The *baseline* value aligns the flex items
such as their baselines aligns.

Align-content

This align-content property is used to align the flex lines. The
*space-between* value displays the flex lines with equal space between
them:

.flex-container {

display: flex;

height: 600px;

flex-wrap: wrap;

align-content: space=between;

}

The *space-around* value displays the flex lines with the space before,
between and after them. The *stretch* value stretches the flex lines to
take up the remaining space (this is default). The *center* value
displays the flex lines in the middle of the container. The *flex-start*
value displays the flex lines at the start of the container. The
*flex-end* value displays the flex lines at the end of the container.

And to solve the perfect centering problem, we set both the
*justify-content* and *align-items* properties to *center*, and the flex
item will be perfectly centered.

[Child elements]{.ul}

The direct child elements of a flex container automatically becomes
flexible (flex) items. The flex item properties are: *order, flex-grow,
flex-shrink, flex-basis, flex* and *align-self*.

Order

This property specifies the order of the flex items. The first item in
the code does not have to appear as the first item in the layout. The
order value must be a number, default value is 0. For example:

\<div class="flex=container"\>

\<div style="order: 3"\>1\</div\>

\<div style="order: 2"\>2\</div\>

\<div style="order: 4"\>3\</div\>

\<div style="order: 1"\>4\</div\>

\</div\>

Flex-grow

This property specifies how much a flex item will grow relative to the
rest of the flex items; the value must be a number and by default is 0.

Flex-shrink

This one specifies how much a flex item will shrink relative to the rest
of the flex items; this value must be a number and by default is 1.

Flex-basis

This property specifies the initial length of a flex item.

Flex

This property is a shorthand property for the *flex-grow, flex-shrink*
and *flex-basis* properties.

Align-self

This property specifies the alignment for the selected item inside the
flexible container. This property overrides the default alignment set by
the container's *align-items* property.

### **Grid layout**

### The grid layout module offers grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image13.png){width="4.978278652668417in" height="1.1888429571303587in"}

### ** **

### 

[Elements]{.ul}

A grid layout consists of a parent element, with one or more child
elements.

Display property

An HTML element becomes a grid container when its display property is
set to *grid* or *inline-grid*. For example:

.grid-container {

display: grid;

}

.grid-container {

display: inline-grid;

}

All direct children of the grid container automatically become *grid
items.*

The vertical lines of grid items are called *columns.* The horizontal
lines of grid items are called *rows*. The spaces between each column or
row are called *gaps.* We can adjust the gap size by using one of these
properties: *column-gap, row-gap* and *gap*. Examples:

The *column-gap* property sets the gap between the columns:

.grid-container {

display: grid;

column-gap: 50px;

}

The *row-gap* property sets the gap between the rows:

.grid-container {

display: grid;

row-gap: 50px;

}

The *gap* property is a shorthand property for the *row-gap* and the
column properties:

.grid-container {

display: grid;

gap: 50px 100px;

}

The *gap* property can also be used to set both the row gap and the
column gap in one value:

.grid-container {

display: grid;

gap: 50px;

}

Lines

The lines between columns are called *column lines.* The lines between
rows are called *row lines.* Refer to line numbers when placing a grid
item in a grid container:

Place a grind item at column line 1 and let it end on column line 3:

.item1 {

grid-column-start: 1;

grid-column-end: 3;

}

Place a grind item at row line 1 and let it end on row line 3:

.item1{

grid-row-start: 1;

grid-row-end: 3;

}

These are all the grid properties and their description:

-   column-gap: specifies the gap between the columns.

-   gap: a shorthand property for the *row-gap* and the *column-gap*
    > properties.

-   grid: a shorthand property for the *grid-template-rows,
    > grid-template-columns, grid-template-areas, grid-auto,rows,
    > grid-auto-columns* and the *grid-auto-flow* properties.

-   grid-area: either specifies a name for the grid item, or this
    > property is a shorthand property for the *grid-row-start,
    > grid-column-start, grid-row-end* and the *grid-column-end*
    > properties.

-   grid-auto-columns: specifies a default column size.

-   grid-auto-flow: specifies how auto-placed items are inserted in the
    > grid.

-   grid-auto-rows: specifies a default row size.

-   grid-column: a shorthand property for the *grid-column-start* and
    > the *grid-column-end* properties.

-   grid-column-end: specifies where to end the grid item.

-   grid-column-gap: specifies the size of the gap between columns.

-   grid-column-start: specifies where to start the grid item.

-   grid-gap: a shorthand property for the *grid-row-gap* and
    > *grid-column-gap* properties.

-   grid-row: a shorthand property for the *grid-row-start* and the
    > *grid-row-end* properties.

-   grid-row-end: specifies where to end the grid item.

-   grid-row-gap: specifies the size of the gap between rows.

-   grid-row-start: specifies where to start the grid item.

-   grid-template: a shorthand property for the *grid-template-rows,
    > grid-template-columns* and the *grid-areas* properties.

-   grid-template-areas: specifies how to display columns and rows,
    > using named grid items.

-   grid-template-columns: specifies the size of the columns and how
    > many columns in a grid layout.

-   row-gap: specifies the gap between the grid rows.

[Container]{.ul}

To make an HTML behave as a grid container, we have to set the *display*
property to *grid* or *inline-grid.* Grid containers consist of grid
items, placed inside columns and rows.

Grid-template-columns

The *grid-template-columns* property defines the number of columns in
our grid layout, and it can define the width of each column.

The value is a space-separated-list, where each value defines the width
of the respective column. If we want our grid layout to contain 4
columns, specify the width of the 4 columns, or "auto" if all columns
should have the same width. For example:

.grid-container {

display: grid;

grid-template-columns: auto auto auto auto;

}

It's important to note that if we have more than 4 items in a 4 columns
grid, the grid will automatically add a new row to put the items in.

The *grid-template-columns* property can also be used to specify the
size (width) of the columns. For example:

Set a size for the 4 columns:

.grid-container {

display: grid;

Grid-template-columns: 80px 200px auto 40px;

}

Grid-template-rows

This property defines the height of each row. The value is
space-separated-list, where each value defines the height of the
respective row. For example:

.grid-container {

display: grid;

grid-template-rows: 80px 200 px;

}

Justify-content

This property is used to align the whole grid inside the container. It's
important to note that the grid's total width has to be less than the
container's width for the *justify-content* property to have any effect.
For example:

.grid-container {

display: grid;

justify-content: space-evenly;

}

The same way with, instead of *space-evenly*: *space-around,
space-between, center, start* and *end.*

Align-content

This property is used to vertically align the whole grid inside the
container. The grid's total height has to be less than the container's
height for the *align-content* property to have any effect. For example:

.grid-container {

display: grid;

height: 400px;

align-content: center;

}

The same way, instead of *center*: *space-evenly, space-around,
space-between, start* and *end.*

[Items (child elements)]{.ul}

A grid *container,* well, contains grid *elements.* By default, a
container has one grid item for each column, in each row, but we can
style the grid items so that they will span multiple columns and/or
rows.

Grid-column

This property defines on which column(s) to place an item. We define
where the item will start and where the item will end. The *grid-column*
property is a shorthand property for the *grind-column-start* and the
*grind-column-end* properties.

To place an item, we can refer to *line numbers* or use the keyword
"span" to define how many columns the item will span. For example, we'll
make "item1" start on column 1 and end before column 5:

.item1 {

grid-column: 1 / 5;

}

Then, we'll make "item1" star on column and span 3 columns:

.item1 {

grid-column: 1 / span 3;

}

And to make "item2" start on column 2 and span 3 columns:

.item 2 {

grid-column: 2 / span 3;

}

Grid-row

This property defines on which row to place an item. We define where the
item will start and where the item will end. The *grid-row* property is
a shorthand for the *grid-row-start* and the *grid-row-end* properties.

To place an item, we can refer to *line numbers*, or use the keyword
'span" to define how many rows the item will span:

Making "item1" start on row-line 1 and end on row-line 4:

.item1 {

grid-row: 1 / 4;

}

Making the "item1" start on row 1 and span 2 rows;

.item1 {

grid-row: 1 / span 2;

}

Grid-area

This property can be used as a shorthand property for the
*grid-row-start, grid-column-start, grid-row-end* and the
*grid-column-end* properties. For example:

To make "item8" start on row-line 1 and column-line 2, and end on
row-line 5 and column line 6:

.item8 {

grid-area: 1 / 2 / 5 / 6;

}

To make 'item8' start on row-line 2 and column-line 1, and span 2 rows
and 3 columns:

.item8 {

grid-area: 2 / 1 / span 2 / span 3;

}

The *grid-area* property can also be used to assign names to grid items.
Named grid items can be referred to by the *grid-template-areas*
property of the grid container. For example:

Item1 gets the name "myArea" and spans all five columns in a five column
grid layout:

.item1 {

grid-area: myArea;

> }
>
> .grid-container {
>
> grid-template-areas: 'myArea myArea myArea myArea myArea';
>
> }
>
> Each row is defined by apostrophes (' ') and the columns in each row
> are defined inside the apostrophes, separated by a space. A period
> sign represents a grit item with no name. For example:
>
> To let "myArea" span two columns in a five columns grid layout (period
> signs represent items with no name, remember):
>
> .item1 {
>
> grid-area: myArea;
>
> }
>
> .grid-container {
>
> grid-template-areas: 'myArea myArea . . . ';
>
> }
>
> To define two rows, define the column of the second row inside another
> set of apostrophes:
>
> To make "item1" span two columns and two rows:
>
> .grid-container {
>
> grid-template-areas: 'myArea myArea . . .' 'myArea myArea . . .';
>
> }
>
> To name all the items and make them ready-to-use webpage template:
>
> ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image11.png){width="5.0343875765529305in"
> height="2.6249343832021in"}

### [Order of the items]{.ul}

### The grid layout allows us to position the items anywhere we like. The first item in the HTML code does ot have to appear as the first item in the grid. For example:

### ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image22.png){width="4.203125546806649in" height="1.9504702537182852in"}

### 

### 

### 

### 

### We can also rearrange the order for certain screen sizes by using media queries:

### ![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image14.png){width="3.9196303587051617in" height="1.8090594925634296in"}

### 

### 

### 

### 

### **Bootstrap**

### Bootstrap is a free front-end framework for faster and easier web development. It includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many others, as well as optional JavaScript plugins. Bootstrap also gives you the ability to easily create responsive designs. 

### Responsive web design is about creating web sites which automatically adjust themselves to look good on all devices, from small phones to large desktops. 

This is a bootstrap example:
![](vertopal_afae199f02eb4fd7ae666fff69d5facb/media/image3.png){width="5.484375546806649in"
height="4.808846237970254in"}

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

### 

Some of the advantages of using bootstrap are:

-   It's easy to use. Anybody with just basic knowledge of HTML and CSS
    > can start using Bootstrap.

-   Its responsive features. Bootstrap's responsive CSS adjusts to
    > phone, tablets and desktops.

-   It has a mobile-first approach. In bootstrap 3, mobile-first styles
    > are part of the core framework.

-   Its browser compatibility. Bootstrap is compatible with all modern
    > browsers (Chrome, FireFox, Internet Explorer, Edge, Safari and
    > Opera).

###  **Materialize CSS**

It is a UI component library which is created with CSS, JavaScript and
HTML. It's created and designed by Google. Materialize CSS is also known
as Material Design. It is a design language which combines the classic
principles of successful design along with innovation and technology.
Google's goal is to develop a system of design that allows for a unique
user experience across all their products on any platform. It is used to
construct attractive, consistent, and functional web pages and web apps
while adhering to modern web design principles such as browser
portability, device independence and graceful degradation.

[Features]{.ul}

-   It's a standard CSS with minimal footprint.

-   In-built Responsive Design.

-   It's free to use and requires jQuery JavaScript library to function
    > properly.

-   It is cross-browser, compatible and can be used to create reusable
    > web components.

-   It contains enhanced and specialized features such as cards, tabs,
    > navigation bars, toasts, etc.

-   It provides new versions of common user interface controls such as
    > buttons, checkboxes and text fields adapted to follow Material
    > Design concepts.

Materialize has in-built responsive design so that a website created
using it will redesign itself as per the device size. Materialize
classes are created in such a way that the website can fit any screen
size, making them fully compatible with desktop, mobile and tablet
devices.

###  **Preprocessors**

CSS preprocessors are scripting languages that extend the default
capabilities of CSS. They enable us to use logic in our CSS code, such
as variables, nesting, inheritance, mixins, functions and mathematical
operations. CSS preprocessors make it easy to automate repetitive tasks,
reduce the number of errors and code bloat, create reusable code
snippets, and ensure backward compatibility.

Each css preprocessor has its own syntax that they compile into regular
CSS so that browsers can render it on the client side. Currently, the
three most popular and stable CSS preprocessors are SASS, LESS and
Stylus; however, there are several smaller ones as well. CSS
preprocessors all do similar things but in a different way and with
their own syntaxes. Each of them has some advanced features unique to
them and their own ecosystem (tools, frameworks, libraries) as well.

#### [SASS]{.ul}

It stands for Syntactically Awesome Stylesheet and it's an extension to
CSS, also completely compatible with all CSS' versions. It reduces
repetition and therefore saves time.

When stylesheets are getting larger, more complex and harder to
maintain, CSS preprocessors can help. SASS lets us use features that
don't exist in CSS, like variables, ested rules, mixins, imports,
inheritance, built-in functions, etc.

A browser does not understand SASS code. Therefore, we will need a SASS
preprocessor to convert SASS code into standard CSS. This process is
called "transpiling". So, we need to give a transpiler (some kind of
program) some SASS code and then get some CSS code back.

Transpiling is a term for taking a source code written in one language
and transform or translate it into another language.

SASS files have the ".scss" file extension. It supports standard CSS
comments /\* comment \*/ , and in addition it supports inline comments /
/ comment :

/\* define primary colors \*/

\$primary_1: \#a2b9bc;

\$primary_2: \#b2ad7f;

/\* use the variables \*/

.main-header {

background-color: \$primary_1; / / here you can put an inline comment

}

Variables

They are a way to store information that we can re-use later. With SASS
we can store information in variables like: strings, numbers, colors,
booleans, lists and nulls. SASS uses the \$ symbol followed by a name to
declare variables: \$*variablename: value;*

This example declares 4 variables named myFont, myColor, myFontSize and
myWidth. After the variables are declared, we can use the variables
wherever we want:

SCSS syntax:

\$myFont: Helvetica, sans-serif;

\$myColor: red;

\$myFontSize: 18px;

\$myWidth: 680px;

body {

font-family: \$myFont;

font-size: \$myFontSize;

Color: \$myColor;

}

\#container {

width: \$myWidth;

}

So, when the SASS file is transpiled, it takes the variables (myFont,
myColor, etc.) and outputs normal CSS with the variable values placed in
the CSS, like this:

CSS output:

body {

font-family: Helvetica, sans-serif;

font-size: 18px;

color: red;

}

\#container {

width: 680px;

}

SASS variables are only available at the level of nesting where they are
defined.

The default behavior for variable scope can be overridden by using the
*!global* switch. *!global* indicates that a variable is global, which
means that it is accessible on all levels. Global variables should be
defined outside any rules. It would be wise to define all global
variables in its own file, named "\_global.scss", and include the file
with the *\@include* keyword.

#### [OOCSS]{.ul} 

Object-oriented CSS isn't a tool, but rather a CSS writing methodology
that aims to make CSS modular and object-based. The "object" in OOCSS
refers to an HTML element or anything associated with it (like CSS
classes or JS methods). For example, you might have a sidebar widget
object that could be replicated for different purposes (newsletter
signup, ad blocks, recent posts, etc). CSS can target these objects
en-masse which makes scaling a breeze.

Summarizing OOCSS' GitHub entry, a CSS object may consist of four
things:

1.  HTML node(s) of the DOM.

2.  CSS declarations about the style of those nodes.

3.  Components like background images.

4.  JS behaviors, listeners or methods associated with an object.

> In general, CSS is object-oriented when it considers classes that are
> reusable and targetable to multiple page elements.
>
> A big part of OOCSS is writing code that separates page structure
> (width, height, margins, padding) from appearance (fonts, colors,
> animations). This allows custom skinning to be applied onto multiple
> page elements without affecting the structure.
>
> This is also useful for designing components that can be moved around
> the layout with ease. For example, a "RecentPosts" widget in the
> sidebar should be moveable into the footer or above the content while
> maintaining similar styles.
>
> Separating content from its container element is another important
> principle of OOCSS. In simpler terms. This only means that you should
> avoid using child selectors whenever it's possible. When customizing
> any unique page elements like anchor links, headers, blockquotes, or
> unordered lists, we should give the unique classes rather than
> descendant selectors.
>
> It's tough to nail down exact specifications because developers are
> constantly debating the purpose of OOCSS. But here are some
> suggestions that can help you write cleaner OOCSS code:

-   Work with classes instead of IDs for styling.

-   Try to abstain from multi-level descendant class specificity unless
    > needed.

-   Define unique styles with repeatable classes (like floats, clearfix,
    > unique font stacks).

-   Extend elements with targeted classes rather than parent classes.

-   Organize your stylesheet into sections, consider adding a table of
    > contents.

It's important to note that we should still use IDs for JS targeting,
but they're not required for CSS because they're too specific. If one
object uses an ID for CSS styling it can never be replicated since IDs
are unique identifiers. If we use oly classes for styling then
inheritance becomes much easier to predict.

Classes can be chained together for extra features. A single element
could have 10+ classes attached to it. Though 10+ classes aren't always
recommended, it does allow us to amass a library of reusable styles for
unlimited page elements.

For instance, using the SASS *\@extend* directive we can apply the
properties of one class into another class. The properties aren't
duplicated but instead are combined with a comma selector. This way we
can update CSS properties in one location.

####  [BEM]{.ul}

This is a front-end naming method for organizing and naming CSS classes.
The Block, Element, Modifier methodology is a popular naming convention
for class names in HTML and CSS. It helps to write clean CSS by
following some simple rules.

There are three main parts of BEM:

1.  Block: which holds everything (elements) inside and acts as a scope.

2.  Element: acts as a specific part of the component.

3.  Modifier: adds additional styles to a specific element(s).

As shown below, a block .head holds all two elements named .head\_\_eye.
The element name has block name at the beginning, followed by two
underscores and then goes the element itself. The element name is just
an element name and can't have underscores. When using multiple words we
must include "-" hyphen-minus to separate them. The modifier name has a
block name at the beginning, two underscores, an element name (just like
naming the element) and then two hyphen-minuses with a modifier name:

\<div class="head"\>

\<div class="head\_\_eye head\_\_eye\--left"\>(o)\</div\>

\<div class="head\_\_eye head\_\_eye\--right"\>(o)\</div\>

\</div\>

####  [SMACSS]{.ul}

It stands for "Scalable and Modular Architecture for CSS and it is a
style's guide which follows five simple categories. SMACSS is a way of
project examination and it helps us adapt those rigid frameworks into a
flexible thought process. These categories are: base, layout, module,
state and theme.

The main idea of this architecture is to not mix several categories
while coding in an only file and turn it really messy to look after if
we make a mistake and want to fix it. The purpose of this is to encode
patterns that are repetitive inside our design. Repetition results in
less coding, easier maintenance and greater consistency in the user's
experience.

-   Base: these are the default values. Like the margin, border, font
    > and other properties. These values are used in the totality of the
    > website and all the elements.

-   Layout: it divides a page into sections with elements like header,
    > footer, etc. These designs keep one or more modules together.
    > Oftentimes, developers show the design elements by prefixing the
    > class using l-, like: L-header.

-   Modules: these are the reusable parts in our design, like the
    > navigation bar, sidebar and some other repetitive elements around
    > the site.

-   State: these are forms of describing how our modules or designs will
    > look like when they're in a particular state (like: active,
    > inactive, expanded, etc). These present the prefix is-.

-   Theme: theme rules are similar to the state rules that describe how
    > modules and designs could look like. Is most applicable to bigger
    > sites with shared elements that look different anywhere.

# **Internet**

### **Cookies**

Cookies are text files with small pieces of data, like username and
password, that are used to identify our device as we use the network.
Specific cookies known as HTTP cookies are used to identify specific
users and improve our web browsing experience.

Data stored in a cookie is created by the server upon our connection.
This data is labeled with an ID unique to us and our device.

When the cookie is exchanged between our device and the network server,
the server reads the ID and knows what information to specifically serve
to us.

There are two types of cookies: "magic cookies" and "HTTP cookies". They
generally function the same but have been applied to different use
cases:

"Magic cookies" are an old computer term that refers to packets of
information that are sent and received without changes. Usually, this
would be used for a login to computer database system, such as a
business internal network.

"HTTP cookies" are a repurposed version of the one above built for
internet browsing. This one is what we currently use to manage our
online experiences, which is also what people can use to get into our
personal info. They are built specifically for internet web browsers to
track, personalize and save information about each user's session.

Cookies are created to identify us when we visit a new website. The web
server sends a short stream of identifying info to our web browser.
Browser cookies are identified and read by "name-value" pairs. These
tell cookies where to be sent and what data to recall. The server only
sends the cookie when it wants the browser to save it, the web browser
will store them locally to remember the "name-value pair" that
identifies our session.

Websites use HTTP cookies to streamline our web experiences. Without
them, we'd have to login again after we leave a site they are intended
to be used for:

-   Session management: cookies allow websites to recognize users and
    > recall our login information and preferences.

-   Personalization: customized advertising is the main way cookies are
    > used to personalize our session.

-   Tracking: shopping sites use cookies to track items users previously
    > viewed, allowing the sites to suggest other goods we might like
    > and keep items in the shopping cart while we keep shopping.

There are two types of HTTP cookies: session cookies and persistent
cookies.

Session cookies are used only while navigating a website. They are
stored in random access memory and are never written to the hard drive.

When the session ends, session cookies are automatically deleted. They
also help the "back" button or third-party anonymizer plugins work.
These plugins are designed for specific browsers to work and help
maintain user privacy.

Persistent cookies, on the other hand, remain on a computer
indefinitely, although many include an expiration date and are
automatically removed when that date is reached. They are used mostly
for:

1.  Authentication: as they track whether a user is logged in and under
    > what name. They also streamline login information, so users do not
    > have to remember site passwords.

2.  Tracking: they track multiple visits to the same site over time. The
    > information gained allows online merchants, for example, to
    > suggest other items that might interest visitors. So, gradually, a
    > profile is built based on a user's browsing history on that site.

It is important to always remember that cookies are an [optional]{.ul}
part of our internet experience.

### **Local and session storage**

> These properties are almost identical and have the same API. The
> difference is that with *sessionStorage*, the data is persisted only
> until the window or tab is closed. On the other hand, with
> *localStorage*, the data is persisted until the user manually clears
> the browser cache or until our web app clears the data.

# **Bibliography** 

###  For agile methodologies:

> [[https://scrumguides.org/scrum-guide.html]{.ul}](https://scrumguides.org/scrum-guide.html)
>
> [[https://www.atlassian.com/es/agile/scrum/sprint-planning]{.ul}](https://www.atlassian.com/es/agile/scrum/sprint-planning)
>
> [[https://www.atlassian.com/es/agile/kanban]{.ul}](https://www.atlassian.com/es/agile/kanban)
>
> [[http://www.extremeprogramming.org/]{.ul}](http://www.extremeprogramming.org/)

### For Git:

> [[https://git-scm.com/]{.ul}](https://git-scm.com/)
>
> [[https://git-scm.com/about]{.ul}](https://git-scm.com/about)
>
> [[https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/]{.ul}](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)
>
> [[https://www.atlassian.com/es/git/tutorials/saving-changes/git-stash]{.ul}](https://www.atlassian.com/es/git/tutorials/saving-changes/git-stash)
>
> [[https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks]{.ul}](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
>
> [[https://www.flagship.io/git-branching-strategies/]{.ul}](https://www.flagship.io/git-branching-strategies/)
>
> [[https://www.freecodecamp.org/espanol/news/la-guia-definitiva-para-git-merge-y-git-rebase/]{.ul}](https://www.freecodecamp.org/espanol/news/la-guia-definitiva-para-git-merge-y-git-rebase/)
>
> [[https://www.git-tower.com/learn/git/faq/git-squash]{.ul}](https://www.git-tower.com/learn/git/faq/git-squash)
>
> [[https://www.edureka.co/blog/git-rebase-vs-merge/\#:\~:text=Git%20Merge%20Vs%20Git%20Rebase%3A&text=Git%20merge%20is%20a%20command,of%20the%20merging%20of%20commits]{.ul}](https://www.edureka.co/blog/git-rebase-vs-merge/#:~:text=Git%20Merge%20Vs%20Git%20Rebase%3A&text=Git%20merge%20is%20a%20command,of%20the%20merging%20of%20commits).

### For JavaScript:

> [[https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript]{.ul}](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
>
> [[https://www.w3schools.com/whatis/whatis_js.asp]{.ul}](https://www.w3schools.com/whatis/whatis_js.asp)
>
> [[https://www.freecodecamp.org/news/what-exactly-is-a-programming-paradigm/\#:\~:text=The%20term%20programming%20paradigm%20refers,that%20strategy%20is%20a%20paradigm]{.ul}](https://www.freecodecamp.org/news/what-exactly-is-a-programming-paradigm/#:~:text=The%20term%20programming%20paradigm%20refers,that%20strategy%20is%20a%20paradigm).
>
> [[https://www.educative.io/blog/object-oriented-programming]{.ul}](https://www.educative.io/blog/object-oriented-programming)
>
> [[https://www.techtarget.com/whatis/definition/variable\#:\~:text=In%20programming%2C%20a%20variable%20is,uses%20when%20it%20is%20running]{.ul}](https://www.techtarget.com/whatis/definition/variable#:~:text=In%20programming%2C%20a%20variable%20is,uses%20when%20it%20is%20running).
>
> [[https://www.w3schools.com/whatis/whatis_js.asp]{.ul}](https://www.w3schools.com/whatis/whatis_js.asp)
>
> [[https://www.w3schools.com/js/js_variables.asp]{.ul}](https://www.w3schools.com/js/js_variables.asp)
>
> [[https://www.w3schools.com/js/js_syntax.asp]{.ul}](https://www.w3schools.com/js/js_syntax.asp)
>
> [[https://www.w3schools.com/js/js_hoisting.asp]{.ul}](https://www.w3schools.com/js/js_hoisting.asp)
>
> [[https://www.w3schools.com/js/js_htmldom.asp]{.ul}](https://www.w3schools.com/js/js_htmldom.asp)
>
> [[https://www.w3schools.com/js/js_scope.asp]{.ul}](https://www.w3schools.com/js/js_scope.asp)
>
> [[https://www.w3schools.com/js/js_strict.asp]{.ul}](https://www.w3schools.com/js/js_strict.asp)
>
> [[https://javascript.info/fetch\#summary]{.ul}](https://javascript.info/fetch#summary)
>
> [[https://www.w3schools.com/js/js_ajax_intro.asp]{.ul}](https://www.w3schools.com/js/js_ajax_intro.asp)
>
> [[https://www.w3schools.com/js/js_ajax_http.asp]{.ul}](https://www.w3schools.com/js/js_ajax_http.asp)
>
> [[https://www.w3schools.com/js/js_ajax_http_send.asp]{.ul}](https://www.w3schools.com/js/js_ajax_http_send.asp)
>
> [[https://www.w3schools.com/js/js_ajax_http_response.asp]{.ul}](https://www.w3schools.com/js/js_ajax_http_response.asp)

### For HTML:

> [[https://www.w3schools.com/html/html_intro.asp]{.ul}](https://www.w3schools.com/html/html_intro.asp)
>
> [[https://www.youtube.com/watch?v=hu-q2zYwEYs&list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G&index=1&t=1046s]{.ul}](https://www.youtube.com/watch?v=hu-q2zYwEYs&list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G&index=1&t=1046s)
>
> [[https://www.w3schools.com/html/html_forms.asp]{.ul}](https://www.w3schools.com/html/html_forms.asp)
>
> [[https://scandiweb.com/blog/html-vs-html5-vs-xhtml-the-difference-in-a-nutshell/]{.ul}](https://scandiweb.com/blog/html-vs-html5-vs-xhtml-the-difference-in-a-nutshell/)
>
> [[https://www.w3schools.com/xml/xml_whatis.asp]{.ul}](https://www.w3schools.com/xml/xml_whatis.asp)
>
> [[https://www.geeksforgeeks.org/difference-between-xhtml-and-html5/]{.ul}](https://www.geeksforgeeks.org/difference-between-xhtml-and-html5/)
>
> [[https://developer.mozilla.org/es/docs/Learn/HTML/Howto/Use_data_attributes]{.ul}](https://developer.mozilla.org/es/docs/Learn/HTML/Howto/Use_data_attributes)
>
> [[https://www.w3schools.com/tags/att_data-.asp]{.ul}](https://www.w3schools.com/tags/att_data-.asp)
>
> [[https://www.w3schools.com/html/html_accessibility.asp]{.ul}](https://www.w3schools.com/html/html_accessibility.asp)

###  For SEO:

> [[https://searchengineland.com/guide/what-is-seo]{.ul}](https://searchengineland.com/guide/what-is-seo)

###  For DOM:

> [[https://www.w3.org/TR/WD-DOM/introduction.html]{.ul}](https://www.w3.org/TR/WD-DOM/introduction.html)

###  For CSS:

> [[https://www.w3schools.com/css/css_syntax.asp]{.ul}](https://www.w3schools.com/css/css_syntax.asp)
>
> [[https://www.w3schools.com/css/css_selectors.asp]{.ul}](https://www.w3schools.com/css/css_selectors.asp)
>
> [[https://www.w3schools.com/css/css_howto.asp]{.ul}](https://www.w3schools.com/css/css_howto.asp)
>
> [[https://www.w3schools.com/css/css_specificity.asp]{.ul}](https://www.w3schools.com/css/css_specificity.asp)
>
> [[https://www.w3schools.com/css/css_rwd_mediaqueries.asp]{.ul}](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)
>
> [[https://www.w3schools.com/cssref/css_units.asp]{.ul}](https://www.w3schools.com/cssref/css_units.asp)
>
> [[https://www.w3schools.com/css/css_positioning.asp]{.ul}](https://www.w3schools.com/css/css_positioning.asp)
>
> [[https://www.w3schools.com/css/css3_flexbox.asp]{.ul}](https://www.w3schools.com/css/css3_flexbox.asp)
>
> [[https://www.w3schools.com/css/css3_flexbox_items.asp]{.ul}](https://www.w3schools.com/css/css3_flexbox_items.asp)
>
> [[https://www.w3schools.com/css/css_grid.asp]{.ul}](https://www.w3schools.com/css/css_grid.asp)
>
> [[https://www.w3schools.com/css/css_grid_container.asp]{.ul}](https://www.w3schools.com/css/css_grid_container.asp)
>
> [[https://www.w3schools.com/css/css_grid_item.asp]{.ul}](https://www.w3schools.com/css/css_grid_item.asp)
>
> [[https://www.w3schools.com/bootstrap/bootstrap_get_started.asp]{.ul}](https://www.w3schools.com/bootstrap/bootstrap_get_started.asp)
>
> [[https://www.javatpoint.com/materialize-css-tutorial]{.ul}](https://www.javatpoint.com/materialize-css-tutorial)
>
> [[https://raygun.com/blog/css-preprocessors-examples/]{.ul}](https://raygun.com/blog/css-preprocessors-examples/)
>
> [[https://www.w3schools.com/sass/sass_intro.php]{.ul}](https://www.w3schools.com/sass/sass_intro.php)
>
> [[https://www.w3schools.com/sass/sass_variables.php]{.ul}](https://www.w3schools.com/sass/sass_variables.php)
>
> [[https://www.hongkiat.com/blog/basics-of-object-oriented-css/]{.ul}](https://www.hongkiat.com/blog/basics-of-object-oriented-css/)
>
> [[https://www.devbridge.com/articles/implementing-clean-css-bem-method/\#:\~:text=BEM%20is%20a%20front%2Dend,by%20following%20some%20simple%20rules]{.ul}](https://www.devbridge.com/articles/implementing-clean-css-bem-method/#:~:text=BEM%20is%20a%20front%2Dend,by%20following%20some%20simple%20rules).
>
> [[https://swapps.com/es/blog/que-es-smacss-y-como-usarlo/]{.ul}](https://swapps.com/es/blog/que-es-smacss-y-como-usarlo/)

### For Internet:

[[https://www.kaspersky.com/resource-center/definitions/cookies]{.ul}](https://www.kaspersky.com/resource-center/definitions/cookies)

> [[https://www.digitalocean.com/community/tutorials/js-introduction-localstorage-sessionstorage\#step-1-understanding-localstorage-vs-sessionstorage]{.ul}](https://www.digitalocean.com/community/tutorials/js-introduction-localstorage-sessionstorage#step-1-understanding-localstorage-vs-sessionstorage)

[^1]: A log is an automatically produced and time-stamped documentation
    of events relevant to a particular system.. Virtually, all software
    applications and systems produce log files.

[^2]: Data type with two possible variables: true or false.

[^3]: JavaScript Object Notation is an open format used as an
    alternative for XML to transfer structured data from a web server to
    an app.

[^4]: Description of the information of an object.
