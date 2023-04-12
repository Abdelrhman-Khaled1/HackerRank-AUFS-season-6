# HackerRank-AUFS-season-6

## _What we took in session 2_ 


**1- How to print a sentence**<br>
`System.out.print("hello in HackerRank");`<br>
or <br>
`System.out.println("hello in HackerRank with");`<br>

special characters needed to print<br>

- \\\   will print \
- \'   will print '
- \"   will print "
- \n   will make a new line
- \t   will make a horizontal tab

let's print that sentence 

hello\Abdelrhman\2002\new Year

```
System.out.println("hello\\Abdelrhman\\2002\\new year");
```
_take care if you want to print \ or another special characters, to print it in the form\\\\._

**2- Naming identifiers**<br>
an identifier (a variable name) can be a sequence of Unicode characters that represent letters, digits 0-9, a dollar sign ($), or an underscore (_).<br>

_some limitations_

- The first symbol of an identifier cannot be a digit.
- An identifier cannot have the same spelling as a keyword.
- It cannot be spelled as the boolean literal true or false, and or as the literal null.
- an identifier cannot be just an underscore (_).

_Here are a few unusual but legal examples of identifiers:_<br>
$$<br>
_30<br>
String<br>
ατηρε<br>
<br>
**3- Data Types**<br>
here is some data types we have in java

- Boolean<br>
to store true or false

- short
- int 
- long<br>
to store Integer numbers

- float
- double<br>
to store Decimal numbers like 3.31 

- char<br>
to store a single character 
- Stirng<br>
to store a text
<br>
that's good but what is the difference between short, int, long ?<br>
Is the maximum and minimum value that can hold .<br>

So let's see what is the maximum and minimum value that short dataType can hold<br>

```
System.out.println(Short.MAX_VALUE);
System.out.println(Short.MIN_VALUE);
```

that will print<br>
32767<br>
-32768<br>

so if you try to store a value like 999999 in a short variable it will give an error.<br>

try to know maximum and minimum value that int and long can hold<br>

```
System.out.println(Integer.MAX_VALUE);
System.out.println(Integer.MIN_VALUE);

System.out.println(Long.MAX_VALUE);
System.out.println(Long.MIN_VALUE);
```

NOW let's assign a value to a variable
```
int age = 21;
String name = "Abdelrhman Khaled";
System.out.println("My name is: "+name +" And my age is: "+age);
```

**4- Some usefull functions in class Integer**<br>
  
Let's try to convert numbers from int to Binary and Octal...

```
System.out.println(Integer.toBinaryString(42));
System.out.println(Integer.toOctalString(42));
System.out.println(Integer.toHexString(42));
```

That is very great the representation of number 42<br>
in Binary is 101010<br>
and in Octal 2a<br>
and in HexaDecimal 52<br>

**5- Some Logic operations in java**<br>

- to represent AND operation we use that symbol &&
- to represent  OR operation we use that symbol ||
- to know the equality we use ==
- and to assign a value to variable we use = 

**6- Ternary operation**<br>


The ? : operator is called a ternary operator. It evaluates a condition (before the sign ?) and, if it results in true, assigns to a variable the value calculated by the first expression (between the ? and : signs); otherwise, it assigns the value calculated by the second expression (after the : sign)

```
int n = 1, m = 2;
float k = n > m ? (n * m + 3) : ((float)n / m);
System.out.println(k);            //prints: 0.5
```

**7- We spoke about typeCasting**<br>

if you try to divide integer number on interger number the outPut must be integer.

`System.out.println(5/2);   //that will print 2`

And that is a problem the fraction disappeared !<br>
_So if you want to save the fraction you must divide Double or Float on that number_<br>

`System.out.println(5.0/2);     // Wow that's awesome the outPut is 2.5 `

that we done is called type case, and there is to ways to case from int to double<br>

1. multiply the number with 1.0
2. or and (double)before the number

**8- Finally we spoke about if statement**<br>

and the style of write it is 

```
if(condition){
            //do that orders
}
```
or

```
if(condition){
            //if the condition is true do that 
}else{
            // it the condition is false do that 
}
```
or

```
if(condition1){
           //if condition1 is true do that 
}else if(condition2){
           //if condition1 is false and condition2 is true do that 
}else {
           // if there isn't any condition is true do that
}
```
 **9- At the end of that session we spoke about loops and forLoop**<br>

_if you want to repeat some thing many times_

```
for(inti , condition , increment){
      //the thing we want to be repeated
}
```
example
```
for (int i = 0; i < 10; i++) {
            System.out.println(i);
}
```
find the summation of numbers from 1 to n
```
Scanner sc = new Scanner(System.in);
int number = sc.nextInt(); 
int sum = 0 ;
for(int i = 1; i <= number ; i++){
      sum +=i;
}
System.out.println("The summation of numbers from 1 to "+n+" is equals "+sum);
```





 

   



 


