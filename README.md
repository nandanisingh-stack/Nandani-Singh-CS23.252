# Nandani-Singh-CS23.252




[program1 wap to reverse the array](#assignment1)
##assignment1
```
import java.util.Scanner;
public class Revarray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Arraytest t1=new Arraytest();
        t1.input();
       
        t1.outarrorg();
         t1.rev();
        t1.outarrrev();
    }
    
}
class Arraytest{
    int x[];
    int rev[];
    
void input(){
    x=new int [5];
    Scanner sc = new Scanner(System.in);
    for(int i=0;i<5;i++){
        System.out.println("Enter array elements");
         x[i]=sc.nextInt();
    }
}
void outarrorg(){
    for(int i=0;i<5;i++)
    {
        System.out.println("The array is"+x[i]);
    }
}
void rev(){
    rev=new int[5];
    for(int i=4;i>=0;i--){
        
        
    }
}
void outarrrev(){
    for(int i=4;i>=0;i--){
        System.out.println("the reverse array is"+x[i]);
        
      
    
    }
        
}

}
```
<img width="557" height="448" alt="image" src="https://github.com/user-attachments/assets/afcdb4f5-0d02-496c-a104-44c604e2ecfb" />

[program2 to input/ output methods](#assignment2)
##assignment2 
```
import java.util.Scanner;
public class Test {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
           
        Test1 t1=new Test1();
t1.input(5,9);
t1.output();
    }
    
}
class Test1
{
    int x;
    int y;
void input(int a,int b)
{
    x=a;
    y=b;
}
void output()
{
    System.out.println(x);
    System.out.println(y);
}
}
```
<img width="338" height="98" alt="image" src="https://github.com/user-attachments/assets/cda85ccc-bc5b-4f8c-bb0a-a7d42bf868e1" />


[program3 wap to take input from user and dispaly it](#assignment3)
##assignment3
```
import java.util.Scanner;

public class Test2 {

    /**
     * Main method - program execution starts from here
     */
    public static void main(String[] args) {
        
        // Creating object of Test3 class
        Test3 t1 = new Test3();
        
        // Calling input method to take values from user
        t1.input();
        
        // Calling output method to display values
        t1.output();
    }
}

/**
 * Test3 class handles input and output operations
 */
class Test3 {

    // Declaring variables
    int x;
    int y;

    /**
     * Method to take input from user
     */
    void input() {
        // Creating Scanner object for user input
        Scanner sc = new Scanner(System.in);

        // Asking user to enter value of x
        System.out.println("Enter value of x");
        x = sc.nextInt();

        // Asking user to enter value of y
        System.out.println("Enter value of y");
        y = sc.nextInt();
    }

    /**
     * Method to display the entered values
     */
    void output() {

        // Printing value of x
        System.out.println("Value of x: " + x);

        // Printing value of y
        System.out.println("Value of y: " + y);
    }
}

```
<img width="361" height="132" alt="image" src="https://github.com/user-attachments/assets/cb0a8271-bf0a-408b-bf9c-2e1370682f9a" />

[program4 wap to input numbers , multiply it , and display the results](#assignment4)
##assignment4
```
import java.util.Scanner;

public class Test4 {

    // Main method - starting point of the program
    public static void main(String[] args) {
        
        // Creating object of Test5 class
        Test5 t1 = new Test5();
        
        // Calling methods for input, processing, and output
        t1.input();
        t1.proc();
        t1.output();
    }
}

// Class to handle input, processing and output
class Test5 {

    int x, y;   // Variables to store numbers

    // Method to take input from user
    void input() {
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Enter value of x");
        x = sc.nextInt();
        
        System.out.println("Enter value of y");
        y = sc.nextInt();
    }

    // Method to double the values
    void proc() {
        x = 2 * x;
        y = 2 * y;
    }

    // Method to display the result
    void output() {
        System.out.println("Value of x after doubling: " + x);
        System.out.println("Value of y after doubling: " + y);
    }
}
```
<img width="313" height="151" alt="image" src="https://github.com/user-attachments/assets/3089b2cd-c983-46c9-8ede-fb58bbd3cf45" />

[program5 wap to perform time operations ](#assignment5)
##assignment5

```
import java.util.Scanner;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author IBM4
 */
public class Test6 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        long st=System.currentTimeMillis();
        Test7 t1=new Test7();
        t1.input();
        
        t1.proc();
        t1.output();
        Test7 t2=new Test7();
        t2.input();
        t2.proc();
        t2.output();
        long end=System.currentTimeMillis();
        System.out.println("Total time in"+(end-st)+"milliseconds");
        System.out.println(System.getProperty("java.version"));
        
    }
    
    
}
class Test7
{
    int x;
    int y;
    int z;
    int k;
void input()
{
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter value of x");
    x=sc.nextInt();
    System.out.println("Enter the value of y");
    y=sc.nextInt();
    System.out.println("Enter the value of z");
    z=sc.nextInt();
    System.out.println("Enter the value of k");
    k=sc.nextInt();
}
void proc()
{
    x=2*x;
    y=2*y;
    z=2*z;
    k=2*k;
    
    
}        
        

void output()
{
    System.out.println(x);
    System.out.println(y);
    System.out.println(z);
    System.out.println(k);
}
}

```
<img width="292" height="448" alt="image" src="https://github.com/user-attachments/assets/d6f52b8f-8fff-43f1-a2f6-d4022593241c" />

[program6 wap to add time](#assignmet6)
##assignment6
```
import java.util.Scanner;
public class TimeAdd2 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        TimeTest2 t1=new TimeTest2();
        TimeTest2 t2=new TimeTest2();
        TimeTest2 t3=new TimeTest2();
        t1.input();
        t2.input();
        t3.add2(t1,t2);
        t3.output();
    }
    
}
class TimeTest2
{
    int hrs;
    int min;
    int sec;
void input(){
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter the value of hour");
    hrs=sc.nextInt();
    System.out.println("Enter the value of minute");
    min=sc.nextInt();
    System.out.println("Enter the value of second");
    sec=sc.nextInt();
}
void add2(TimeTest2 o1,TimeTest2 o2){
    sec=o1.sec+o2.sec;
    min=o1.min+o2.min;
    hrs=o1.hrs+o2.hrs;
    if(sec>=60){
        sec=sec-60;
        min=min+1;
    }
    if(min>=60){
        min=min-60;
        hrs=hrs+1;
    }
    
}
void output(){
    System.out.println("hrs="+hrs);
    System.out.println("min="+min);
    System.out.println("sec="+sec);
        
}
}

```
<img width="305" height="275" alt="image" src="https://github.com/user-attachments/assets/4064e168-79fa-483d-ab36-82a8ba3a7a92" />


[program7 wap to add time (2) ](#assignment7)
##assignment7
```
import java.util.Scanner;
public class Time_Add {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        TimeTest t1=new TimeTest();
        TimeTest t2=new TimeTest();
        t1.input();
        t2.input();
        t1.add(t2);
        t1.output();
    }
    
}
class TimeTest
{
    int hrs;
    int min;
    int sec;
void input(){
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter the value of hour");
    hrs=sc.nextInt();
    System.out.println("Enter the value of minute");
    min=sc.nextInt();
    System.out.println("Enter the value of second");
    sec=sc.nextInt();
}
void add(TimeTest o){
    sec=sec+o.sec;
    min=min+o.min;
    hrs=hrs+o.hrs;
    if(sec>=60){
        sec=sec-60;
        min=min+1;
    }
    if(min>=60){
        min=min-60;
        hrs=hrs+1;
    }
    
}
void output(){
    System.out.println("hrs="+hrs);
    System.out.println("min="+min);
    System.out.println("sec="+sec);
        
}
}

```

<img width="325" height="271" alt="image" src="https://github.com/user-attachments/assets/a17c10f1-8a30-4882-91d4-1b0b422e557b" />


[program8 wap to add distances](#assignment8)
##assignment8
```

import java.util.Scanner;
public class DistAdd {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        DistTest t1=new DistTest();
        DistTest t2=new DistTest();
        
        t1.input();
        t2.input();
        t1.add3(t2);
        t1.output();
    }
    
}
class DistTest
{
    int mm;
    int cm;
    int m;
void input(){
    Scanner sc=new Scanner(System.in);
    System.out.println("Enter the value of millimeter");
    mm=sc.nextInt();
    System.out.println("Enter the value of centimeter");
    cm=sc.nextInt();
    System.out.println("Enter the value of meter");
    m=sc.nextInt();
}
void add3(DistTest d){
    mm=mm+d.mm;
    cm=cm+d.cm;
    m=m+d.m;
    if(mm>=10){
        mm=mm-10;
        cm=cm+1;
    }
    if(cm>=100){
        cm=cm-100;
        m=m+1;
    }
    
}
void output(){
    System.out.println("m="+m);
    System.out.println("cm="+cm);
    System.out.println("mm="+mm);
        
}
}

```
<img width="298" height="308" alt="image" src="https://github.com/user-attachments/assets/e6b09783-1498-4c5c-aa28-f6dfefcd4eb2" />

[program9 wap to perform operations on 2D array](#assignment9)
##assignment9
```
import java.util.Scanner;

public class Array2 {
    public static void main(String[] args) {
        Array a1 = new Array();
        a1.input();
        a1.outputarr();
        a1.transpose();
        a1.outputtrans();
    }
}

class Array {
    // 1. Initialize arrays at the class level or in a constructor
    int arr[][] = new int[3][3];
    int trans[][] = new int[3][3];

    void input() {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter 9 elements for the 3x3 matrix:");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                // 2. Removed 'int' prefix to use the class-level variable
                arr[i][j] = sc.nextInt();
            }
        }
    }

    void outputarr() {
        System.out.println("Original Array elements are:");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                // 3. Changed 'trans' to 'arr' to show original elements
                System.out.print(arr[i][j] + " ");
            }
            System.out.println();
        }
    }

    void transpose() {
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                trans[j][i] = arr[i][j];
            }
        }
    }

    void outputtrans() {
        System.out.println("Transposed Array elements are:");
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                System.out.print(trans[i][j] + " ");
            }
            System.out.println();
        }
    }
}

```
<img width="296" height="319" alt="image" src="https://github.com/user-attachments/assets/aa088cd3-952f-41d3-a99c-6eccf446ccb7" />


[program10 wap to show abstraction](#assignment10)
##assignment10
```
package swati singh;

/**
 *
 * @author IBM4
 */

abstract class Photo {
    abstract void fun();
    abstract void fun1();
}    
class D extends Photo{
    void fun(){
        System.out.println("This is class D with first method");
    }
    void fun1(){
        System.out.println("This is class D with second method");
    }

   
}
class E extends Photo{
    void fun(){
        System.out.println("This is class E with first method");
    }
    void fun1(){
        System.out.println("This is class E with second method");
    }

   
}
public class Abst {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        D obj = new D();
        E obj1 = new E();
        obj.fun();
        obj.fun1();
        obj1.fun1();
        obj1.fun();
    }
    
}
```
<img width="286" height="101" alt="image" src="https://github.com/user-attachments/assets/99333c7b-9eac-485b-bb37-81623b6fe7dc" />

[program11 wap to show ](#assignment11)
##assignment11
```
```












