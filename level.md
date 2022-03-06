# 자바 레벨 테스트
참조 사이트: 
* https://www.hackerrank.com/domains/java
* https://github.com/iluwatar/java-design-patterns
* https://level.goorm.io/

## 레벨 1
* Basic

## 레벨 2
* Strings
* BigNumber

## 레벨 3
* Data Structures
* Regular Expressions
* Object Oriented Programming

## 레벨 4
* Exception Handling
* Design Patterns : Factory, Singleton, Visitor, Adaptor

## 레벨 5
* Advanced
* Design Patterns : Chain-of-responsibility, Commander

___

## 레벨 1 문제
### Basics

#### 1. Hello World
___

**Objective**

"Hello, World." 문자열을 stdout 으로 출력

**Test**
```java
public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Print output to STDOUT. 
           Your class should be named Solution. */
        System.out.println("Hello, World.");
    }
}
```

#### 2. Java Stdin and Stdout I
---

**Objective**

stdin으로 부터 입력을 받아 stdout으로 출력

**Sample Input**
```
42
100
125
```
**Sample Output**
```
42
100
125
```
>

**Test**
```java
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        int a = scan.nextInt();
        // Complete this line
        // Complete this line

        
        System.out.println(a);
        // Complete this line
        // Complete this line

        
    }
}
```

#### 3. Java If-Else
---

**Objective**
Given an integer, n, perform the following conditional actions:

* If n is odd, print Weird
* If n is even and in the inclusive range of  to , print Not Weird
* If n is even and in the inclusive range of  to , print Weird
* If n is even and greater than , print Not Weird
Complete the stub code provided in your editor to print whether or not  is weird.

**Input Format**

A single line containing a positive integer, n.

**Constraints**
* 1 <= n <= 100

**Output Format**

Print Weird if the number is weird; otherwise, print Not Weird.

**Test**
```
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. 
           Print output to STDOUT. 
           Your class should be named Solution. */
    }
}
```

#### 4. Java Stdin and Stdout II
---

**Objective**
In this challenge, you must read an integer, a double, and a String from stdin, then print the values according to the instructions in the Output Format section below. To make the problem a little easier, a portion of the code is provided for you in the editor.

**Note:** We recommend completing Java Stdin and Stdout I before attempting this challenge.

**Input Format**

There are three lines of input:

* The first line contains an integer.
* The second line contains a double.
* The third line contains a String.

**Output Format**

There are three lines of output:

* On the first line, print String: followed by the unaltered String read from stdin.
* On the second line, print Double: followed by the unaltered double read from stdin.
* On the third line, print Int: followed by the unaltered integer read from stdin.
* To make the problem easier, a portion of the code is already provided in the editor.

**Note:** If you use the nextLine() method immediately following the nextInt() method, recall that nextInt() reads integer tokens; because of this, the last newline character for that line of integer input is still queued in the input buffer and the next nextLine() will be reading the remainder of the integer line (which is empty).

**Sample Input**
```
42
3.1415
Welcome to HackerRank's Java tutorials!
```
**Sample Output**

```
String: Welcome to HackerRank's Java tutorials!
Double: 3.1415
Int: 42
```

**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. 
           Read input from STDIN. 
           Print output to STDOUT. 
           Your class should be named Solution. */
    }
}
```
#### 5. Java Output Formatting
---

**Objective**

**Input Format**

Every line of input will contain a String followed by an integer.
Each String will have a maximum of  alphabetic characters, and each integer will be in the inclusive range from 0 to 999.

**Output Format**

In each line of output there should be two columns:
The first column contains the String and is left justified using exactly 15 characters.
The second column contains the integer, expressed in exactly 3 digits; if the original input has less than three digits, you must pad your output's leading digits with zeroes.

**Sample Input**
```
java 100
cpp 65
python 50
```

**Sample Output**
```
================================
java           100 
cpp            065 
python         050 
================================
```

**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
    }
}
```

#### 6. Java Loops I
---

**Objective**
In this challenge, we're going to use loops to help us do some simple math.

**Task**
Given an integer, N, print its first 10 multiples. Each multiple N x i (where 1<= i <=10) should be printed on a new line in the form: N x i = result.

**Input Format**

A single integer, N.

**Constraints**
2 <= N <= 20

**Output Format**

Print 10 lines of output; each line i (where 1 <= i <= 10) contains the result of N x i in the form:
N x i = result.

**Sample Input**

```
2
```

**Sample Output**

```
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
```

#### 7. Java Loops II
---
**Objective**

We use the integers , a, b, and n to create the following series:
(a + 2^0 * b), (a + 2^0 * b + 2^1 * b), ..., (a + 2^0 * b + ... + 2^n * b)
You are given q queries in the form of ,a, b , and n. For each query, print the series corresponding to the given a, b and n values as a single line of n space-separated integers.

**Input Format**

The first line contains an integer, , denoting the number of queries.
Each line  of the  subsequent lines contains three space-separated integers describing the respective , , and  values for that query.

**Constraints**

**Output Format**

For each query, print the corresponding series on a new line. Each series must be printed in order as a single line of n  space-separated integers.

**Sample Input**

```
2
0 2 10
5 3 5
```

**Sample Output**

```
2 6 14 30 62 126 254 510 1022 2046
8 14 26 50 98
```

**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. 
           Read input from STDIN. 
           Print output to STDOUT. 
           Your class should be named Solution. */
    }
}
```


#### 8. Java Datatypes
---

**Objective**
Java has 8 primitive data types; char, boolean, byte, short, int, long, float, and double. For this exercise, we'll work with the primitives used to hold integer values (byte, short, int, and long):

* A byte is an 8-bit signed integer.
* A short is a 16-bit signed integer.
* An int is a 32-bit signed integer.
* A long is a 64-bit signed integer.
Given an input integer, you must determine which primitive data types are capable of properly storing that input.

To get you started, a portion of the solution is provided for you in the editor.

**Reference:**
https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html

**Input Format**

The first line contains an integer, T, denoting the number of test cases.
Each test case, T, is comprised of a single line with an integer, n, which can be arbitrarily large or small.

**Output Format**

For each input variable n and appropriate primitive dataType, you must determine if the given primitives are capable of storing it. If yes, then print:

```
n can be fitted in:
* dataType
```

If there is more than one appropriate data type, print each one on its own line and order them by size (i.e.: byte < short < int < long).

If the number cannot be stored in one of the four aforementioned primitives, print the line:

```
n can't be fitted anywhere.
```

**Sample Input**

```
5
-150
150000
1500000000
213333333333333333333333333333333333
-100000000000000
```

**Sample Output**

```
-150 can be fitted in:
* short
* int
* long
150000 can be fitted in:
* int
* long
1500000000 can be fitted in:
* int
* long
213333333333333333333333333333333333 can't be fitted anywhere.
-100000000000000 can be fitted in:
* long
```

**Explanation**

 -150 can be stored in a short, an int, or a long.

 213333333333333333333333333333333333 is very large and is outside of the allowable range of values for the primitive data types discussed in this problem.
 
**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
    }
}
```
 

#### 9. Java End-of-file
---

**Objective**
The challenge here is to read n lines of input until you reach EOF, then number and print all  lines of content.

Hint: Java's Scanner.hasNext() method is helpful for this problem.

**Input Format**

Read some unknown n lines of input from stdin(System.in) until you reach EOF; each line of input contains a non-empty String.

**Output Format**

For each line, print the line number, followed by a single space, and then the line content received as input.

**Sample Input**

```
Hello world
I am a file
Read me until end-of-file.
```

**Sample Output**

```
1 Hello world
2 I am a file
3 Read me until end-of-file.
```

**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
    }
}
```

#### 10. Java Static Initializer Block
---

**Objective**


#### 11. Java Int to String
---

**Objective**
You are given an integer , you have to convert it into a string.

Please complete the partially completed code in the editor. If your code successfully converts n  into a string  the code will print "Good job". Otherwise it will print "Wrong answer".

n can range between -100 to 100 inclusive.

**Sample Input 0**
```
100
```
**Sample Output 0**
```
Good job
```
```java
import java.util.*;
import java.security.*;
public class Solution {
 public static void main(String[] args) {

  DoNotTerminate.forbidExit();

  try {
   Scanner in = new Scanner(System.in);
   int n = in .nextInt();
   in.close();

   //Write your code here

   
   if (n == Integer.parseInt(s)) {
    System.out.println("Good job");
   } else {
    System.out.println("Wrong answer.");
   }
  } catch (DoNotTerminate.ExitTrappedException e) {
   System.out.println("Unsuccessful Termination!!");
  }
 }
}

//The following class will prevent you from terminating the code using exit(0)!
class DoNotTerminate {

 public static class ExitTrappedException extends SecurityException {

  private static final long serialVersionUID = 1;
 }

 public static void forbidExit() {
  final SecurityManager securityManager = new SecurityManager() {
   @Override
   public void checkPermission(Permission permission) {
    if (permission.getName().contains("exitVM")) {
     throw new ExitTrappedException();
    }
   }
  };
  System.setSecurityManager(securityManager);
 }
}
```

#### 12. Java Date and Time
---

**Objective**
The Calendar class is an abstract class that provides methods for converting between a specific instant in time and a set of calendar fields such as YEAR, MONTH, DAY_OF_MONTH, HOUR, and so on, and for manipulating the calendar fields, such as getting the date of the next week.

You are given a date. You just need to write the method, getDay, which returns the day on that date. To simplify your task, we have provided a portion of the code in the editor.


**Function Description**

Complete the findDay function in the editor below.

findDay has the following parameters:

* int: month
* int: day
* int: year

**Returns**

* string: the day of the week in capital letters

**Input Format**

A single line of input containing the space separated month, day and year, respectively, in MMDDYYYY format.

**Constraints**
* 2000 < year < 3000

**Sample Input**

```
08 05 2015
```

**Sample Output**

```
WEDNESDAY
```

**Explanation**

The day on August 5th 2015 was WEDNESDAY.

**Test**

```java
import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.function.*;
import java.util.regex.*;
import java.util.stream.*;
import static java.util.stream.Collectors.joining;
import static java.util.stream.Collectors.toList;

class Result {

    /*
     * Complete the 'findDay' function below.
     *
     * The function is expected to return a STRING.
     * The function accepts following parameters:
     *  1. INTEGER month
     *  2. INTEGER day
     *  3. INTEGER year
     */

    public static String findDay(int month, int day, int year) {
        
    }

}

public class Solution {
    public static void main(String[] args) throws IOException {
        BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
        BufferedWriter bufferedWriter = new BufferedWriter(new FileWriter(System.getenv("OUTPUT_PATH")));

        String[] firstMultipleInput = bufferedReader.readLine().replaceAll("\\s+$", "").split(" ");

        int month = Integer.parseInt(firstMultipleInput[0]);

        int day = Integer.parseInt(firstMultipleInput[1]);

        int year = Integer.parseInt(firstMultipleInput[2]);

        String res = Result.findDay(month, day, year);

        bufferedWriter.write(res);
        bufferedWriter.newLine();

        bufferedReader.close();
        bufferedWriter.close();
    }
}
```


#### 13. Java Currency Formatter
---

**Objective**

Given a double-precision number, payment, denoting an amount of money, use the NumberFormat class' getCurrencyInstance method to convert payment into the US, Indian, Chinese, and French currency formats. Then print the formatted values as follows:

```
US: formattedPayment
India: formattedPayment
China: formattedPayment
France: formattedPayment
```

where  _formattedPayment_ is _payment_ formatted according to the appropriate Locale's currency.

**Note:** India does not have a built-in Locale, so you must construct one where the language is en (i.e., English).

**Input Format**

A single double-precision number denoting payment.

**Constraints**
* 0 <= payment <= 10^9

**Output Format**

On the first line, print US: **u** where  is **payment** formatted for US currency.
On the second line, print India: **i** where  is **payment** formatted for Indian currency.
On the third line, print China: **c** where  is **payment** formatted for Chinese currency.
On the fourth line, print France: **f**, where **payment** is  formatted for French currency.

**Sample Input**
```
12324.134
```

**Sample Output**

```
US: $12,324.13
India: Rs.12,324.13
China: ￥12,324.13
France: 12 324,13 €
```

**Explanation**

Each line contains the value of **payment** formatted according to the four countries' respective currencies

**Test**

```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double payment = scanner.nextDouble();
        scanner.close();

        // Write your code here.
        
        System.out.println("US: " + us);
        System.out.println("India: " + india);
        System.out.println("China: " + china);
        System.out.println("France: " + france);
    }
}
```

## 레벨 2
#### 1. Java Stings Introduction
---

**Objective**

This exercise is to test your understanding of Java Strings. A sample String declaration:

```
String myString = "Hello World!"
```

The elements of a String are called characters. The number of characters in a String is called the length, and it can be retrieved with the String.length() method.

Given two strings of lowercase English letters,  A and B, perform the following operations:

1. Sum the lengths of A and B.
2. Determine if A is lexicographically larger than  B (i.e.: does B come before A in the dictionary?).
3. Capitalize the first letter in A and B and print them on a single line, separated by a space.

**Input Format**

The first line contains a string A . The second line contains another string B. The strings are comprised of only lowercase English letters.

**Output Format**

There are three lines of output:
For the first line, sum the lengths of A and B.
For the second line, write Yes if A is lexicographically greater than B otherwise print No instead.
For the third line, capitalize the first letter in both A and B and print them on a single line, separated by a space.

**Sample Input 0**

```
hello
java
```

**Sample Output 0**

```
9
No
Hello Java
```

**Explanation 0**

String A is "hello" and B is "java".

A has a length of 5, and B has a length of 4; the sum of their lengths is 9.
When sorted alphabetically/lexicographically, "hello" precedes "java"; therefore, A is not greater than B and the answer is No.

When you capitalize the first letter of both A and B and then print them separated by a space, you get "Hello Java".


**Test**

```java
import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        
        Scanner sc=new Scanner(System.in);
        String A=sc.next();
        String B=sc.next();
        /* Enter your code here. Print output to STDOUT. */
        
    }
}

```

#### 2. Java Substring
---

**Objective**
Given a string, s, and two indices, start and end, print a substring consisting of all characters in the inclusive range from start to end - 1. You'll find the String class' substring method helpful in completing this challenge.

**Input Format**

The first line contains a single string denoting _s_.
The second line contains two space-separated integers denoting the respective values of _start_ and _end_.

**Constraints**
* 1 <= |s| <= 100
* 0 <= start < end <= n
* String _s_ consists of English alphabetic letters (i.e., [a-zA-Z]) only.

**Output Format**

Print the substring in the inclusive range from _start_ to _end_ - _1_.

**Sample Input**

```
Helloworld
3 7
```

**Sample Output**

```
lowo
```

**Explanation**

In the diagram below, the substring is highlighted in green:

![substring.png](https://s3.amazonaws.com/hr-challenge-images/22039/1470896981-637b6a022f-substring.png)


**Test**

```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        String S = in.next();
        int start = in.nextInt();
        int end = in.nextInt();
    }
}
```


#### 3. Java Substring Comparisons
---

**Objective**
We define the following terms:

* Lexicographical Order, also known as alphabetic or dictionary order, orders characters as follows:
  A < B < ... < Y < Z < a < b < ... < y < z
For example, ball < cat, dog < dorm, Happy < happy, Zoo < ball.

* A substring of a string is a contiguous block of characters in the string. For example, the substrings of abc are a, b, c, ab, bc, and abc.
Given a string, _s_, and an integer, _k_, complete the function so that it finds the lexicographically smallest and largest substrings of length _k_.

**Function Description**

Complete the getSmallestAndLargest function in the editor below.

getSmallestAndLargest has the following parameters:

* string s: a string
* int k: the length of the substrings to find

**Returns**

* string: the string ' + "\n" + ' where and are the two substrings

**Input Format**

The first line contains a string denoting ***s***.
The second line contains an integer denoting ***k***.

**Constraints**

* 1 <= |s| <= 1000
* ***s*** consists of English alphabetic letters only (i.e., [a-zA-Z]).

**Sample Input 0**

```
welcometojava
3
```

**Sample Output 0**

```
ava
wel
```

**Explanation 0**

String ***s***=**"welcometojava"** has the following lexicographically-ordered substrings of length ***k=3***:

**["ava", "com", "elc", "eto", "jav", "lco", "met", "oja", "ome", "toj", "wel"]**

We then return the first (lexicographically smallest) substring and the last (lexicographically largest) substring as two newline-separated values (i.e., ava\nwel).

The stub code in the editor then prints ava as our first line of output and wel as our second line of output.

**Test**
```java
import java.util.Scanner;

public class Solution {

    public static String getSmallestAndLargest(String s, int k) {
        String smallest = "";
        String largest = "";
        
        // Complete the function
        // 'smallest' must be the lexicographically smallest substring of length 'k'
        // 'largest' must be the lexicographically largest substring of length 'k'
        
        return smallest + "\n" + largest;
    }


    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        String s = scan.next();
        int k = scan.nextInt();
        scan.close();
      
        System.out.println(getSmallestAndLargest(s, k));
    }
}
```

#### 4. Java String Reverse
---

**Objective**


#### 5. Java Anagrams
---

**Objective**

#### 6. Java String Tokens
---

**Objective**

#### 7. Pattern Syntax Checker
---

**Objective**

## 레벨 3
#### 1. Java Regex
---

**Objective**

#### 2. Java Regex 2 - Duplicate Words
---

**Objective**

#### 3. Valid Username Regular Expression
---

**Objective**

#### 4. Tag Content Extrator
---

**Objective**

## 레벨 4
#### 1. 
---

**Objective**


## 레벨 5
#### 1. 
---

**Objective**

