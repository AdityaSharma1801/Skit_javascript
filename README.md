# Java Script basics
    JAVASCRIPT  (1995)

CLIENT SIDE LANGUAGE  ------to make css dynamic
PROGRAMMING LANG
SERVER SIDE LANG TOO!   (node.js express.js)




<script>
       
       console.log("Hello JavaScript")               ----see in console
       alert("Hello everyone")			     ----popup on the screen	
       document.write("Today is Monday")

    </script>


DOM document object method





						JAVASCRIPT BASICS

-no datatype required

  output()
        function output(){
            console.log("hello js")
        }

THIS IS JAVA SCRIPT HOSTING --------WE CAN USE FUNCTION EVEN BEFORE DEFINING IT






 console.log(a=20)
          var a ;                       ---- var is a hosting variable......we can not host using let or char




QUESTIONS ON KEYWORD
                      =DATA TYPES IN JS?
-REDEFINE REASSIGN?
-GLOBAL LOCAL SCOPE
-HOSTING VARIABLE?





					OPERATORS








//TYPES OF FUNCTIONS IN JS
        // 1. naming Function       ------IIFE (immediatly invoke function expression)
        // 2. anyonomous function
        // 3. arrow function



arrow func does not has This pointer ka scope and does not have return  

while  anonymous function has This pointer scope and it has return







 //Call back function -----accepts othre function as a argument

        function f1 (a){
            a()
        }

        function f2(){
            console.log("I am F2 function")
        }

        f1(f2)





		 function output(x,y,z){
            z(x,y)

        }
        function add(a,b){
            console.log(a+b)
        }
        output(30,50,add)
