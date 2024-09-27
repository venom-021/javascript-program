Javascript :-

- javascript is used for building logics of a web page.
- javascript is a high level programming language used in both clint side as well as server side.
- javascript is comes from echma script so we see the latest version of javascript in the form of echma script
- now we used javascript version 6 i.e ES6(echma-script 6)
- In another way we called ES6 as the vanilla javascript.
- Node js is the run time environment of javascript.

Variable :-

- variable is a countainer to store some data.
- in javascript there are 3 types of variable are there...

1. let :-
- let is a type of variable which is used for changing the variable name
later.
- Now these days, most of the cases we used let for creating variable.
- let is a block scope code so we have been used let for most of the cases. 

2. var :-

- var is a type of variable which is also used for changing the variable in later stage.
- var is used in oldest browseer so now a days we are don't use var most of the cases.
3. const :- const means constant.



 <!-- task- difference between let & var -->


 Rules for creating varibale name :-

  - variable names are case sensative "a", & "A" is different.
  - Only letter, digit, underscore, & special character is allowed,(not even white space).
  - only letter, underscore or special character should be the 1st character only.
  ex- let today_is = "monday"
  - reserved words cannot be a variable name. ex- for, while, switch, do-while, console


  Datatypes in JS :-


- datatypes is an attributes associated with a piece of data that tells a computer
system how to interprit its value.
- in datatype we used "typeof" operator to know that what type of data it is .
- mainlly in javascript there are 2 types of datatype we used.

1. Primitive Datatype :-

- in javascript there are 7 types of primitive datatype we used :-
  1. Number - Number are the type of datatype those it contain some numerical values
  2. Boolean - in Boolean datatypes we get boolean value like true/false
  3. Undefined - data is not define
  4. Null - in this datatuype we get null for the means nothing.
  5. bigInt - in bigInt we will get the big integer value(-999999999 to +999999999) on the above.
  6. String - String is a type of datatypes that can hold some character like names or words etc...
  7. Symbol - in Symbol we get one symbol of more than one value.

2. Reference Datatype :-

- reference datatype are the type of datatype which can hold multiple element in a single time.
- reference datatypes are -> array, object, function

  1. Array:-
   - array is a datatype where we can store similar type of data is a contigious memory location.
   - array indexing starts from "0".

   ex- let arr = ["ram", "hari", "sita", "rita"]
                   0       1       2       3      

  2. Object :-

  - object is reference type of datatype where are we can store more than one element in a single entity.
  - mainly objects are working on (key:value) pair.


  ex.

  let emp1 = {
    "name" : "sonu kumar",
    "age" : "76",
    "address" : "bhubaneswar",
    "mobile no." : "546789032"
    "salary" : 56789332
      }

      in the above example we can see that the left hand side elements are the keys & the right hand side element are values so we can tell that object is the key:value pair structure.


  3. Function :-

 - in function , we repeatedlly do the task in function.
 - function reduce our code complexity and time & space complexity.
 - syntax ->

// function
 function my_schedule(){
  console.log("we wake up at 6 am")
  console.log("we go for a morning walk")
  console.log("we go to our college for time pass")
 
}

// function calling 
my_schedule()


Operator in JS:-

- opertor are the key features to do some task or operate some task.
- ex A+B
- in above example A,B are the operands & "+" is the operator.
- there are 5 types of operator are present in javascript.

1. Arithmetic operator :-
(+,-,*,/,), %(modulus), **(exponentiation)
2. Logical operator :-
logical AND (&&), logical OR (||)

3. Assignment operator:-
(=, =, +=, -=, *=, %=, **=)
4. Unary operator:-
increment (++), decrement (--)
5. comparision operator:-
(==, !==, === etc....)


Conditional statement:-

- To implement some condition in the code.
- there are 3 types of conditional statement are there
1. if condition :- 
- if condition is true then statement is true.
-syntax :-
if(condition){
  statement
} 

2. if-else condition :-
-if condition is true then statement is true otherwise false.
-syntax :-
if(condition){
  statement
} else{
  statement
}

3. if-elif condition :-
-its check the condition multiple times , where the condition is true.
-syntax :-
if(condition){
  statement
} else if(condition){
     statement
} else {
  statement
}



