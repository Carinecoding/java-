# java-

这里是我学习Java basics的知识记录。


**LEARN JAVA: MANIPULATING VARIABLES**

Review

What’s the use of having variables if you can’t do anything with them? We’ve now seen some ways you can operate on variables and compare them. The possibilities are endless!

We covered:

 1. Addition and subtraction, using + and -
 2. Multiplication and division, using * and /
 3. The modulo operator for finding remainders, %
 4. Compound assignment operators +=, -=, *=, /=, and %=.

    

> The order of operations: parentheses -> multiplication -> division ->
> modulo -> addition -> subtraction

 5. Greater than, >, and less than, <
 6. Equal to, ==, and not equal to, !=
 7. Greater than or equal to, >=, and less than or equal to, <=equals() for comparing Strings and other objects


 8. Using + to concatenate Strings
 9. The final keyword which makes variables unchangeable

Practice some of these concepts here, to make sure you have a solid foundation for learning more complicated and exciting Java concepts!



 **In general, method declarations has these components :**

In general, method declarations has these components :

-   **Modifier**-: Defines **access type** of the method i.e. from where it can be accessed in your application. In Java, there 4 type of the access specifiers.
    -   **public**: accessible in all class in your application.
    -   **protected**: accessible within the class in which it is defined and in its **subclass(es)**
    -   **private**: accessible only within the class in which it is defined.
    -   **default** :(declared/defined without using any modifier) : accessible within same class and package within which its class is defined.
-   **The return type** : The data type of the value returned by the the method or void if does not return a value.
-   **Method Name** : the rules for field names apply to method names as well, but the convention is a little different.
-   **Parameter list** : Comma separated list of the input parameters are defined, preceded with their data type, within the enclosed parenthesis. If there are no parameters, you must use empty parentheses ().
-   **Exception list** : The exceptions you expect by the method can throw, you can specify these exception(s).
-   **Method body** : it is enclosed between braces. The code you need to be executed to perform your intended operations.

![Java Method Creation](https://sp-ao.shortpixel.ai/client/to_avif,q_glossy,ret_img,w_525/https://simplesnippets.tech/wp-content/uploads/2018/03/methods-in-java-programming.jpg)

**Method signature**: It consists of method name and parameter list (number of parameters, type of the parameters and order of the parameters). Return type and exceptions are not considered as part of it.  
Method Signature of above function:

    max(int x, int y)

**How to name a Method ?**: A method name is typically a single word that should be a **verb** in lowercase or multi-word, that begins with a **verb** in lowercase followed by **adjective, noun…..** After the first word, first letter of each word should be capitalized. For example, findSum, computeMax, setX and getX

[# Java Methods – Detailed Explanation with Example](https://simplesnippets.tech/java-methods-detailed-explanation-with-program-example/)
