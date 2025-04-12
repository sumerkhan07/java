# java
Full stack java notes<br>
Program<br>
The set of instruction or block of code known as  program.

<br>Language 
A language is medium which is used for communication purpose.
<br>
Programming Language
A language is used to write a set of instruction in order to 
commuction between programmer or user and machine.
<br>
<br>

Types of programming languaging 

1-High level Language
<br>
2-Mid level Language
<br>
3-Low level Language
<br>

<br>
1-High level Language
A programming language  which is easily understable and readeable by
user or programmer known as high level language.
eg. Java , Python,C,C++
<br>
2-Mid level Language
A languae whcih is not understable by user or programmer nor by machine 
Known as mid level  language.
eg. byte code 

<br>
3-Low level languae
A langauage which is understandable by machine known as low level  Language.
eg.Binary language(0,1)

<br>
Binary language 
It is low level language which is used to communicate  in 0's and 1s with
machine.
<br>

<br>
Histroy of java
<br>
Java is develop by GAMES GOSLING and his team in the year 1991 under a company SUN MICRO SYSTEM.<br>by 
Initillay the name of this language was GREEN TALK, letter they have changed the name from GREEN TALK to OAK.
<br>
Since the name OAK is already taken by some other organization again they changed name from OAK to JAVA.
<br>
The name  JAVA come from Java bean.<br>
The 1st version of Java was released in the year 1995 named as java alphabeta.
<br>
In 1996 a new version is releasd JDK 1.0 and they keep on releasing new versios.
<br>

Platform Independent  Language 
<br>
An application which is develop in one platfrom using programming language,if it can use
any other platform is then we call this Pltform Independent Programming language.
<br>
Simple Definition:<br>
Platform independent means the ability of a program to work on any operating system or hardware platform.
  <br>     
<br>
Java is a high level programming language which support OOPS principle.<br>
Feature of Java
<br>
1-Java is a simple programming language.<br>
2-Java is a secure language.<br>
3-Java is a platform independent language.<br>
4-Java is a Robust language.<br>
5-Java has automatic garbage collecter.<br>
6-Java is a portabble language.<br>
7-Java support multithreading and multi tasking.<br>
8-Java provides built in library which helps programmer to perform complex task easily.<br>
9-Java Supports OOPS principle <br>
  -Encapsulation<br>
  -Inheritance <br>
  -Polymorphism <br>
  -Abstraction <br>

<br>
Uses of java
Java is used to develop an application or software such as web application,mobile aplication
,banking application,J2MEE application etc
<br>

[note :- It is also used to develop some tools such as seleneum which is an automation tool].

************************************************************************
//Data types in java 

class datatypes{

    public static void main(String[] args){
        //intger
        short s=2;   // (Range -32,768 to 32,767) 2 bytes
        long l=3;     // (Range -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807) 8 bytes
        byte b=4;      // (Range -128 to 127) 1 byte
        int a=10;   // (Range -2,147,483,648 to 2,147,483,647) 4 bytes

        System.out.println(a+"\t"+ l +"\t" + b+ "\t" +s);

        //floating data types 
        //In java the decimal is by default double

        float f=4.33f;         // (Range -3.40282347E+38 to 3.40282347E+38) 4 bytes
        double d=33.32;          // (Range -1.79769313486231570E+308 to 1.79769313486231570E+308) 8 bytes
        System.out.println(f+"\t"+d);


        //char data type
        //char is used to store a single character. It is a 16-bit Unicode character. 
       //Char it should be in single  cote.
        char c='a'; // (Range 0 to 65,535) 2 bytes
        char c1='A'; // (Range 0 to 65,535) 2 bytes 
        char c2='1'; // (Range 0 to 65,535) 2 bytes
        System.out.println(c+"\t"+c1+"\t"+c2);

        //string data type
        //String is a class in java. It is used to store a sequence of characters.      
        //String is a reference data type. It is used to store a sequence of characters.
        String str="Hello java"; // (Range 0 to 2^31-1) 2 bytes
        System.out.println(str);

        //boolean data type
        //Boolean is used to store true or false. It is a 1-bit value.  
        //Boolean is a reference data type. It is used to store true or false.
        boolean b1=true; // (Range 0 to 2^31-1) 2 bytes
        boolean b2=false; // (Range 0 to 2^31-1) 2 bytes
        System.out.println(b1+"\t"+b2);

    }
}


***************************************************************************************
