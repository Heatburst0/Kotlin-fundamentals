# Kotlin-fundamentals
code for Kotlin fundamentals for basic
package com.kv.kotlinfundamentals
/*This is the first code for kotlin fundamentals
in this I'll show you how the var and val keywords in kotlin work
 */

fun main(){//This is the main method when you run your code main method will execute first
    //So, if you want to store a value which you want to use in your code
    // you have to store that value in a variable
    //for example
    var x =9// here i am storing value 9 in a variable x and i am using a var key word before variable name
    //var and val keyword are basically used to allocate memory for that variable
    //without var and val memory will not be allocated for that variable and compiler will throw an error
    y=9 //here compiler will throw an error

    //so, what is the difference between val and var
    //if you declare a variable var this means that you can override the value on that variable
    //example
    var z=9
    z=8
    println(z)//here if you print the variable the value of z will be 8 instead of 9
    //val is opposite of val if you declare a variable val this means that you cannot override the value on that variable
    //example
    var const=9
    const=7//here compiler will throw an error
    println(const)
}
