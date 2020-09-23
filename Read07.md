# Introduction 

    - This review explains to us how to use JavaScript and how it can be used in browsers to make them more interactive for the user. 
    - When learning javascript you have to understand some of the basic programming concepts, the language itself and how it is applied into the website.

## How does javascript make web pages more interactive 

    -Access content, you can use java to select any element, attribute and text. For exmaple selsecing the text inside all of the <h1> elements on a page 
    - Modifying your content through java. You can add elements and attributes to the text or page. For example adding a paragraph text after the <h1> element
    - Program rules, you can specifiy a set of steps for the browser which allows you to access or change the content.
    - Reacting to events, you can run a script when a specific event is happening. For example when a link is clicked. 

## Examples of javascript in browser
    - Access the content of the page. 
    - Modify the content of the page.
    - Program rules or instructions the browser can follow.
    - React to events triggered by the user or browser.

## The structure of this book 
    - Core concepts the first nine chapters introduce you to the basicis of programming and the Java language. During the first nine chapters you will learn how to create a more engaging and interactive website. 
    - Pratical applications this is where all your techniques that you have learned will be put into place. 

        1. HTML elements are added to the content of the page to show its structure. A elements consists of an opening and closing tag. 
        2. CSS rules uses to indicate how the contents of one or more element should be displayed during our browser. 

    - Each browser adds a new feature and some of the features wont work.

## The ABC of programming
    - A is what a script and how do i create one.
    - B how do computers fit in with the world around them.
    - C how do i write a script for a web page.

 - A script is a series of instructions that a computer can follow. To compare scripts to any of the following:
        1. Recipes
        2. Handbooks
        3. Manuals
- Scripts change the way your website interacts, some scripts can run different sections of the code. 
- To write a script you need to first state your goal and then list the tasks.

# Rules for naming variables
        - Here are six rules you must follow when giving a variable;
                1. The name has to behing with a letter, $ , or an underscore.
                2. The name can containt letters, numbers, $, and an underscore. Do not use - or . in a variable name. 
                3. Use keywords, they are special words that tell the reader to do somthing specific. 
                4. All variables are case sensitive. 
                5. Use a name that describes some information that varibles can store. For example firstname might be used to store someone first name. 
                6. If the variable name is made of up more than one word, use a capital letter for the ifrst word letter of the every word after the first word.

# Arrays
    - An array is a special type of variable, it doesnt just store one value it stores a list of values. 
    - You should use array's when you are wokring with a list or a set of valued related to each other. 
    - Creating a array is used but inputting in java script this following command;    
            var colors;
            colors = ['white', 'black','custom']

            var el = document.getElementByID ('colors');
            el.textContent = colors[0];
    
# Values in arrayys
    - Values in an array are accessed as if they are in a numbered list.
        1. Numbering items in an array.
        2. Accessing items in an array.
        3. Number of items in an array.

    - Expression evalutes into a single value. There are two types of expressions:
        1. Expressions that just assign a value to a variable. In order for a variable to be usefull it needs a given value. 
        2. Expressions that use two or more values to return a single value.

    - Expressions rely on operators which allow programmers to create a single value from one or more valules. 

# Functions and methods
    - Browsers require very detailed instructions about what we want them to do. That is why they have very complex scripts and can run to thousands of lines. This is why programmers use functions and methods to organize their code.
        1. Functions and methods, functions consist of a series of states that have been grouped together. 
        2. Objects, we read about this in chapter 1 but programmers used objects to create models of the world using their data.
        3. Built in objects, The browser comes with sets of objects that act as a toolkit for creating interactive web pages 
    - Function let you group a series of statements together to perform a specific task. 