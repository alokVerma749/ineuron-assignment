<p align="center"><img height = "200px" width= "250px" src="https://play-lh.googleusercontent.com/JKzSZ8dRSeN1SENxZMulZABnssSRgGXwrDgqCquDcLbzgxGCDhogGwzYPIyrWt1-igI"/></p>
<h1 align="center">JavaScript Marathon Assignment</h1>
<br>

> ### Note: This Readme is maintained by me just to get a better way to present the assignment solution. Please have a look

<br>

# Day-3

</b></details>

<details>
<summary>List all the Escape Sequences characters in javascript.</summary><br><b><b>
    
> Escape sequence characters are used to encode special characters in a strings. 
    
## Escape sequences characters are:
    - \' :- Used to denote single quotes in the string.
    - \" :- Used to denote double quotes in the string.
    - \n :- Used to escape to new line.
    - \t :- Use to denote a TAB space.
    - \v :- Vertical TAB
    - \r :- carriage return
    - \b :- backspace
    - \f :- form feed

```bash
    let myStr = 'Hello my name is Alok Verma.\n And I am learnig \'web development/' by /"Histeh Sir/".\n';
    console.log(myStrLength);
```
     OutPut: Hello my name is Alok Verma.
     And I am learnig "web development/" by 'Histesh Sir' 


</b></details>

<details>
<summary>Explain with example length and substring methods in javascript.</summary><br><b><b>
    
## length
    
>`length` is a property of the String.prototype object which reflects the `length` of the string.
    
```bash
    let myStr = 'Hello my name is Alok Verma and I am learnig web development';
    let myStrLength = myStr.length;
    console.log(myStrLength);
```
    
     Output: 60
    
    <br>

## substring()
    
> `substring()` method returns the string between start and end indexes.
    <br><br>
> NOTE: first index(indexStart) is `inclusive` while last index(indexLast) is `exclusivee`.

```bash
    const str = 'Hitesh';

    console.log(str.substring(1, 3));
    //str.cubstring(indexStart, indexEnd)


    console.log(str.substring(2));
    //str.cubstring(indexStart)

```    
    
    OutPut: it
            tesh

</b></details>

<details>
<summary>What are padStart and padEnd in javascript, explain with an example.</summary><br><b><b>
    
## padStart()
    
> `padStart()` pads/adds the given string from start to other string until it reaches to its given length.
    <br><br>

## Syntax
    
    padStart(targetLength)
    padStart(targetLength, padString)

    
```bash
    
'Alok'.padStart(10);         // "      Alok"
'Alok'.padStart(10, "foo");  // "foofooAlok"
'Alok'.padStart(6,"123465"); // "12Alok"
'Alok'.padStart(8, "0");     // "0000Alok"
'Alok'.padStart(1);          // "Alok"
    //NOTE: if given length is less than the given string then the original string is returned.


```    
    
## padEnd()
    
> `padEnd()` pads/adds the given string from end to other string until it reaches to its given length.
    <br><br>

## Syntax
    
    padStart(targetLength)
    padStart(targetLength, padString)

    
```bash
    
'Alok'.padEnd(10);         // "Alok      "
'Alok'.padEnd(10, "foo");  // "Alokfoofoo"
'Alok'.padEnd(6,"123465"); // "Alok12"
'Alok'.padEnd(8, "0");     // "Alok0000"
'Alok'.padEnd(1);          // "Alok"
     //NOTE: if given length is less than the given string then the original string is returned.

```   
    
</b></details>

<details>
<summary>Define Global Object in javascript along with the global scope.</summary><br><b><b>

## Global Object:- 

Global object are the objects which provides functions and variables that can be
used anywhere in the environment. In browsers the global object is known as 
`window` while in `Node` environment it is 'global'.<br><br>
This global object are came inbuilt in the languages/environments.<br><br>
Any variables or functions declared using `var` become a property of the `Global object`.<br>
`gobalThis` is the standard name for the global object and is supported by almost every environment.

 ## Global Scope:-

   - Scope which is accessible from everywhere is `global scope`.
   - variables which are declared globally has global scope.
   - variables declared using `var` has global scope.
    
</b></details>

<details>
<summary>List all the names of Javascript engines present currently. </summary><br><b><b>

Some of the notable JavaScript engines are:
    
- V8 :- Used and developend by `Chrome Browser`
    
- Spider Monkey:- Used in `firefox Browser` and developend by `Mozilla`
    
- JavaScriptCore :- It is `Apple's` engine for its `Safari browser`.
    
- Chakra :- It is the engine of the `Internet Explorer browser`

</b></details>
