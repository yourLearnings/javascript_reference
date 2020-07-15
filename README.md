# javascript_reference
Quick reference for java script


# javaScript
Basic syntax and learning. 

javaScript in client side and in server side it is nodeJS.  JavaScript interact / manipulates the HTML, through DOM manipulations. Html webpage content stored in DOM. 

# Reference for Git
GIT : https://guides.github.com/activities/hello-world/

GitPages: https://pages.github.com/

https://github.com/jonasschmedtmann/complete-javascript-course/blob/master/slides-students-C03.pdf

# Script for printing outputs different options 

          alert('testing any output'); // hit ok required to continue
          var age = prompt('What is your age'); // takes input from user 
          console.log('Type anything you like');
          console.log(typeof(var-type) ); /** prints the type of var */ 


# Variable types & declarations 
1. Numbers / Strings / Boolean
2. undefined ( value is not assigned yet) 
3. null ( non-existent)

<b> Variable mutation </b> 

     Change variable value 
<b> Type coercion </b> 

      Converts type of variable automatically 
      ex: console.log('xxxx' + ' ' + age);  //string gets concatenated with age which is integer.

<b> New in ES6/ES2015  </b>
let 
const


# State Variable 
State varibles are required when you want the system to remember something. 
Simply tells the condition of the system. 

# looping statements and Boolean
          if () {
          }
          else if () {
          }
          else {
          }
# Conditional operator 
          var switch_var = 'a';
          switch(switch_var) {
          case 'a': { // do something
          break;
          }
          default: {  // do something }
          }
          
<b> Boolean </b>
          AND --> &&
          OR --> ||
          NOT --> !== // strict comparison
          
          
<b> Ternary Operator </b> 
          a >= 100 ? 'Great' : ' had to wait' ; // executed before assignment operator

<b> Strict equal  </b>
          if ( a === b ) // used for strict equality checking 
                    a = 5; b =10; or 
          if ( a == b ) // non strict equality checking 
          
          if(martialStatus === 'married') // strict if martialStatus is a string type var
          
          height == '123'     // 123 is converted to string before comparison 
          
                              // performs type coercion
                              
          a = 5; // simple assignement 
          
<b> Boolean </b>
Falsy values : undefined, null, 0, '', NaN;

# Control Structures 

1. For loops 
2. While loop 
3. Continue & break statements
                    for( i=0 ; i <= 10; i ++){
                              if( typeof(a[i] !== 'string') 
                              continue;
                    }
                    for( i=0 ; i <= 10; i ++){
                              if( typeof(a[i] !== 'string') 
                              break;
                    }                  

# Functions 
<b> Two Types </b>

1. Statement 
          
          function calcAge(year){
                    var currentYear = 2020;
                    return (currentYear - year);
          ) // This requires a function declaration statement.
                    
2. Expression 

          Expressions are piece of code which always produce a value. 
          var funcName = function ( arg1, arg 2) {
                          
                          }
   Sample 
          var a = [1 , 2, 5];
          var c = new Array(1,2,3);
          var test = [ testResult(a[0]), testResult(a[1]) ]

# Function Constructor as instances of Object


//Function constructor

          var person1 = {
                    name = 'name',
                    age = 30,
                    occupation = 'Engineer'
          };
          
          var Person = function (name, age, occupation){
             this.name = name;
             this.age = age;
             this.occupation = occupation;
          }

          var person1 = new Person('name2', 40, 'tester');
new creates an empty object

New in ES6/ES2015
# Blocks and IIFES

# Strings 


New in ES6/ES2015


# Arrow functions 


New in ES6/ES2015

# Destructuring 

# Arrays 

          var names = ['name1','name2','name3','name4']; // most commonly used format
          var names = new array('name1','name2','name3','name4') ; 
          var add = ['name', 'street', 'houseno', 695010]; // multiple data types 
   
<b> Methods specific for arrays </b>

          1. names.push // add element to the end of the array
          2. names.unshift // add element to the begining of the array
          3. names.pop // remove element from the array <b> end</b>
          4. names.shift // remove element begining
          5. names.indexOf(value) // return in which position in the array value appears, if not present returns -1

New in ES6/ES2015

# Spread Operators 


New in ES6/ES2015

# REST and Default Parameters 



New in ES6/ES2015

# Maps



New in ES6/ES2015


# Classes and subclasses



New in ES6/ES2015

# Promises and node modules 

