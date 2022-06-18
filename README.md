<p align="center"><img height = "200px" width= "250px" src="https://play-lh.googleusercontent.com/JKzSZ8dRSeN1SENxZMulZABnssSRgGXwrDgqCquDcLbzgxGCDhogGwzYPIyrWt1-igI"/></p>
<h1 align="center">JavaScript Marathon Assignment</h1>
<br>

> ### Note: This Readme is mintained by me just to get a better way to present the assignment solution. Please have a look

<br>

## Day-1

<details>
<summary>Explain the use of JavaScript ( or What you can do using a JavaScript)</summary><br><b>

Javascript is programming language that can be used as a replacement of any other language. It can be used for fullstack web development.
But originally JS is developed for enhancing the frontend of a webpage and now it enriched with a lot of functionalities(like OOPS, API DEVELOPMENT,ETC)
so that it used for `fullstack web-development`.
</b></details>

<details>
<summary>What is the difference between client-side and server-side?</summary><br><b>

Whatever this is happening on the users computer(i.e. HTML and CSS displayed on the screen, user interacting with the UI) it is called client-side.

And whatever is happening on the backend(on the servers like: Handling requests and sending responses, managing database, etc) is callend backend.
</b></details>

<details>
<summary> What is Nodejs?</summary><br><b>
  
Nodejs is runtime environment for the JS. It runs on the `v8 engine` and executes JavaScript code outside a web browser. 
  
Previously JS can be run inside the browsers because a engine is inbuild inside the the browsers which executes the JS.
It was used only inside the browsers because at that time JS is meant to be used only for only frontend purpose.
But some folks made a decision to take out the JS engine(i.e V8 frome chrome browser) from the browser and enhance it enough so
that it can be used on the machines without the browser. And now it is used on the servers as a backend scripting language.

</b></details>

<details>
<summary>Explain Scope in JavaScript ?</summary><br><b>

Scope can be considered as the boundary till which something will be applicable or have its existance.

In JS for every variable, function and object there exists a scope linked with it, apart from where they are not reachable.

### e.g: -

```bash
      let a = "Can be reachable throughout whole code";

        {
          let b = "Can be reachable only inside this scope";
        }
```

> NOTE: If instead of using `let` we use `var` keyword for declaring the varibles.Then the varible declared using `var`
> keyword can be accessed everywhere, this is because the scope of the variables declared using "var" have global scope.
> While `let` allows you to declare variables that are limited to the scope of a block statement.
> </b></details>

<details>
  <br>
<summary>JavaScript is asynchronous or synchronous.</summary><br><b>

JavaScript shows both synchronous and asynchronous behaviour.

If less time consuming task is executing then the execution will be done in synchronous manner, but if a more time consuming task kicks in the stack then JS starts showing its asynchronous behaviour.

Most asynchronous JavaScript operations has two primary triggers i.e. WebAPI's`and`promises`.

</b></details>

<details>
<summary>JavaScript is Single-threaded or Multi-threaded.</summary><br><b>

JavaScript is a single-threaded language because it has only one call stack and one memory heap. JS executes the code sequentially and function calls are get stored in the call stack. These calls are poped out of the stack when its execution is done. Here it behave like a synchronous language.

But this approach can be harmfull if a time consuming task is executing. In this case JavaScript engine halts the execution of the other sequential code. So to rescue JS manages these situations with the help of `WebAPI's` and `promises`. If it finds any function which is going to take time then the time consuming function will the handled asynchronously.

</b></details>

<details>
<summary>Explain DOM in your own word.</summary><br><b>

DOM(Document Object Model) is not a programming language. It is a API used by JS to convert the web document into nodes and objects so that it becomes easy to interact with the web page using a programming language.

In simple words DOM provides object-oriented representation of the web pageand allows web page to be manipulated.

</b></details>

# Day-2

<details>
<summary>What is lexical structure?</summary><br><b>

Lexical structure is the the bascic syntax for writing any programming language. It is also considered as the lowest level syntactical structure which needs to be follwed.
Some lexical structure rules in JavaScript is :

1.  JS is written in UNICODE(it is an iternational standard for character encoding).
2.  JS is a case sensitive language.
3.  Using semicolons are optional in JS, as it adds semicolons behind the scenes by `Automatic Semicolon Insertion` technique
    This `Automatic Semicolon Insertion` follows <a href= "https://www.freecodecamp.org/news/lets-talk-about-semicolons-in-javascript-f1fe08ab4e53/">7 Rules</a>
    to insert semicolons while parsing the code.
4.  There are two types of comments present in JS:
    - Single Line Comment(// THis is a comment)
    - Multi Line Comment(/_ This is a comment _/)
5.  Whitespaces,Line breaks and Comments are ignored whit executing.
6.  A variable name can only be start with a letter, the dollar sign ($) or an underscore \_.
7.  There are reserved keywords and future reserverd keywords whih cannot be used as a variable name.

</b></details>

<details>
<summary>What is Unicode?</summary><br><b><b>
Unicode is a international standard for character encoding. It assignes a unique code to every charcters known as code point.
This helps to identify charcter more easily and with less chances of error

Previously when UNICODE was not there, every language, machine or company uses there own encodings which results as conflicts between them.
All these conflicts are solved by UNICODE as it gives a character encoding which is accepted and used by all as common entity.

</b></details>

<details>
<summary>Explain all the keywords present in the JavaScript with examples.</summary><br><b>
  
  <center>
    <table>
      <tr>
     <td align="center"><button/><br/><b>await</b></button></td>
     <td align="center"><button/><br/><b>break</b></button></td>
     <td align="center"><button/><br/><b>case</b></button></td>
     <td align="center"><button/><br/><b>catch</b></button></td>
     <td align="center"><button/><br/><b>class</b></button></td>
     <td align="center"><button/><br/><b>const</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>continue</b></button></td>
     <td align="center"><button/><br/><b>debugger</b></button></td>
     <td align="center"><button/><br/><b>default</b></button></td>
     <td align="center"><button/><br/><b>delete</b></button></td>
     <td align="center"><button/><br/><b>do</b></button></td>
     <td align="center"><button/><br/><b>else</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>else</b></button></td>
     <td align="center"><button/><br/><b>enum</b></button></td>
     <td align="center"><button/><br/><b>export</b></button></td>
     <td align="center"><button/><br/><b>extends</b></button></td>
     <td align="center"><button/><br/><b>false</b></button></td>
     <td align="center"><button/><br/><b>finally</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>for</b></button></td>
     <td align="center"><button/><br/><b>function</b></button></td>
     <td align="center"><button/><br/><b>if</b></button></td>
     <td align="center"><button/><br/><b>implements</b></button></td>
     <td align="center"><button/><br/><b>import</b></button></td>
     <td align="center"><button/><br/><b>in</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>instanceof</b></button></td>
     <td align="center"><button/><br/><b>interface</b></button></td>
     <td align="center"><button/><br/><b>let</b></button></td>
     <td align="center"><button/><br/><b>new</b></button></td>
     <td align="center"><button/><br/><b>null</b></button></td>
     <td align="center"><button/><br/><b>package</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>private</b></button></td>
     <td align="center"><button/><br/><b>protected</b></button></td>
     <td align="center"><button/><br/><b>public</b></button></td>
     <td align="center"><button/><br/><b>return</b></button></td>
     <td align="center"><button/><br/><b>super</b></button></td>
     <td align="center"><button/><br/><b>switch</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>static</b></button></td>
     <td align="center"><button/><br/><b>this</b></button></td>
     <td align="center"><button/><br/><b>throw</b></button></td>
     <td align="center"><button/><br/><b>try</b></button></td>
     <td align="center"><button/><br/><b>true</b></button></td>
     <td align="center"><button/><br/><b>true</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>typeof</b></button></td>
     <td align="center"><button/><br/><b>var</b></button></td>
     <td align="center"><button/><br/><b>void</b></button></td>
     <td align="center"><button/><br/><b>while</b></button></td>
     <td align="center"><button/><br/><b>with</b></button></td>
     <td align="center"><button/><br/><b>yield</b></button></td>
    </tr>
    </table>
  </center>

</b></details>

<details>
<summary>What are shorthand operators, explain with a suitable example?</summary><br><b>

</b></details>

<details>
<summary>What is “use Strict” in JavaScript?</summary><br><b>

</b></details>
