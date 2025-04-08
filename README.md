# java
Full stack java notes
Program
The set of instruction or block of code known as  program.
************

Language 
A language is medium which is used for communication purpose.
************
Programming Language
A language is used to write a set of instruction in order to 
commuction between programmer or user and machine.
************

Types of programming languaging 
1-High level Language
2-Mid level Language
3-Low level Language


1-High level Language
A programming language  which is easily understable and readeable by
user or programmer known as high level language.
eg. Java , Python,C,C++

2-Mid level Language
A languae whcih is not understable by user or programmer nor by machine 
Known as mid level  language.
eg. byte code 

3-Low level languae
A langauage which is understandable by machine known as low level  Language.
eg.Binary language(0,1)

Binary language 
It is low level language which is used to communicate  in 0's and 1s with
machine.
*************************************************************************
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
