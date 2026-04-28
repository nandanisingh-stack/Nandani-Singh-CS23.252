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




[program11 wap to show  ArrayList operations](#assignment11)
##assignment11
```
import java.util.ArrayList;
import java.util.List;
import java.util.Iterator;

public class Arraylist{
    public static void main(String[] args) {
        // 1. Initialize List
        List<String> list = new ArrayList<>();

        // --- ADD ---
        list.add("Apple");          // add(E e) - Adds at end
        list.add("Mango"); 
        list.add(1, "Banana");      // add(int index, E e) - Inserts at index 1
        System.out.println("After Adding: " + list);

        // --- ACCESS ---
        String fruit = list.get(0); // get(int index)
        int position = list.indexOf("Banana"); // indexOf(Object o)
        System.out.println("Element at 0: " + fruit);
        System.out.println("Index of Banana: " + position);

        // --- UPDATE ---
        list.set(2, "Orange");      // set(int index, E e) - Replaces Mango
        System.out.println("After Update: " + list);

        // --- SIZE / CHECK ---
        System.out.println("Size of list: " + list.size()); // size()
        System.out.println("Is list empty? " + list.isEmpty()); // isEmpty()
        System.out.println("Contains 'Apple'? " + list.contains("Apple")); // contains()

        // --- TRAVERSAL ---
        System.out.print("Using forEach: ");
        list.forEach(item -> System.out.print(item + " ")); // forEach()
        System.out.println();

        System.out.print("Using Iterator: ");
        Iterator<String> it = list.iterator(); // iterator()
        while(it.hasNext()) {
            System.out.print(it.next() + " ");
        }
        System.out.println();

        // --- REMOVE ---
        list.remove(1);             // remove(int index) - Removes Banana
        list.remove("Apple");       // remove(Object o) - Removes Apple by name
        System.out.println("After Removing: " + list);

        list.clear();               // clear() - Wipes the list
        System.out.println("After Clear, size is: " + list.size());
    }

}

```
<img width="354" height="285" alt="image" src="https://github.com/user-attachments/assets/e55e87c4-202c-4f10-8cce-bc7b8067b7c0" />

[program12 wap to show  LinkedList operations ](#assignment12)
##assignment12
```
import java.util.LinkedList;
        public class Ldls {
            public static void main(String[] args) {

        LinkedList<String> list = new LinkedList<>();

        //  Add methods
        list.add("Apple");
        list.addFirst("Banana");
        list.addLast("Mango");

        // �Access methods
        System.out.println("First: " + list.getFirst());
        System.out.println("Last: " + list.getLast());

        // Update
        list.set(1, "Orange");
            
            }
        }
```
<img width="154" height="94" alt="image" src="https://github.com/user-attachments/assets/c50adafe-a886-401f-bd86-88d0c3a1472e" />


[program13 wap to show   Hashmap operations ](#assignment13)
##assignment13
```
import java.util.HashMap; // Fixed typo: mport -> import
import java.util.Map;

public class Hashmappg { // Class name must match your filename (Hashmappg.java)
    public static void main(String[] args) {

        HashMap<Integer, String> ht = new HashMap<>();

        // 1. put(K key, V value) - Adds or updates
        ht.put(10, "Apple");
        ht.put(20, "Banana");
        ht.put(30, "Cherry");

        // 2. putIfAbsent(K key, V value) - Adds only if key doesn't exist
        ht.putIfAbsent(20, "Blueberry"); // Won't change Banana
        ht.putIfAbsent(40, "Date");      // Will add Date

        // 3. get(Object key) - Retrieve value
        System.out.println("Key 10: " + ht.get(10));

        // 4. getOrDefault(Object key, V defaultValue)
        System.out.println("Key 50: " + ht.getOrDefault(50, "Not Found"));

        // 5. replace(K key, V value) - Updates existing key
        ht.replace(30, "Cranberry");

        // 6. remove(Object key)
        ht.remove(40);

        // 7. containsKey & containsValue
        System.out.println("Has key 20? " + ht.containsKey(20));
        System.out.println("Has value 'Apple'? " + ht.containsValue("Apple"));

        // 8. size() & isEmpty()
        System.out.println("Size: " + ht.size());
        System.out.println("Is empty? " + ht.isEmpty());

        // 9. keySet() - Get all keys
        System.out.println("All Keys: " + ht.keySet());

        // 10. values() - Get all values
        System.out.println("All Values: " + ht.values());

        // 11. entrySet() - Get key-value pairs
        System.out.println("Full Entries:");
        for (Map.Entry<Integer, String> entry : ht.entrySet()) {
            System.out.println(entry.getKey() + " => " + entry.getValue());
        }

        // 12. clear()
        ht.clear();
        System.out.println("Size after clear: " + ht.size());
    }
}



```
<img width="367" height="329" alt="image" src="https://github.com/user-attachments/assets/3f19712e-aeee-4fee-acd2-55f68313bbc9" />



[program14 wap to show  HashTree operations ](#assignment14)

##assignment14

```
import java.util.TreeSet;
public class HTree {
    public static void main(String[] args) {

    

        TreeSet<Integer> set = new TreeSet<>();

        // 1. add(E e) - Adds elements and sorts them automatically
        set.add(50);
        set.add(10);
        set.add(30);
        set.add(20);
        set.add(40);

        // 2. size()
        System.out.println("TreeSet: " + set + " | Size: " + set.size());

        // 3. contains(Object o)
        System.out.println("Contains 30? " + set.contains(30));

        // 4. first() and last()
        System.out.println("First (Lowest): " + set.first());
        System.out.println("Last (Highest): " + set.last());

        // 5. higher(E e) and lower(E e)
        System.out.println("Higher than 20: " + set.higher(20)); // Smallest element > 20
        System.out.println("Lower than 20: " + set.lower(20));   // Largest element < 20

        // 6. remove(Object o)
        set.remove(30);
        System.out.println("After removing 30: " + set);

        // 7. pollFirst() - Removes and returns the first (lowest) element
        System.out.println("Removed First: " + set.pollFirst());

        // 8. pollLast() - Removes and returns the last (highest) element
        System.out.println("Removed Last: " + set.pollLast());

        System.out.println("Set after polling: " + set);

        // 9. clear()
        set.clear();
        System.out.println("Is empty after clear? " + set.isEmpty());
    }
}
```





<img width="377" height="244" alt="image" src="https://github.com/user-attachments/assets/544e7b17-83ce-4776-9480-389f35fa5daa" />


[program15 wap to show  Stack operations ](#assignment15)

##assignment15
```
import java.util.Stack;


public class Stackpg {
    
    public static void main(String[] args) {
        // Initialize Stack
        Stack<Integer> stack = new Stack<>();

        // 1. push(E item) - Adds elements to the top
        stack.push(10);
        stack.push(20);
        stack.push(30);
        stack.push(40);
        System.out.println("Stack after pushes: " + stack);

        // 2. peek() - Looks at the top element without removing it
        System.out.println("Top element (peek): " + stack.peek());

        // 3. pop() - Removes and returns the top element
        System.out.println("Removed element (pop): " + stack.pop());

        // 4. isEmpty() - Checks if stack is empty
        System.out.println("Is stack empty? " + stack.isEmpty());

        // 5. search(Object o) - Returns 1-based position from the top
        int position = stack.search(20); 
        System.out.println("Position of 20 from top: " + position);

        // 6. size() - Returns number of elements
        System.out.println("Current size: " + stack.size());

        // 7. contains(Object o) - Checks if element exists
        System.out.println("Does it contain 10? " + stack.contains(10));

        // 8. iterator() - To traverse the stack
        System.out.print("Traversing with Iterator: ");
       
        
        // 9. clear() - Removes everything
        stack.clear();
        System.out.println("Stack after clear: " + stack);
        System.out.println("Is empty now? " + stack.isEmpty());
    }
}

```
<img width="429" height="232" alt="image" src="https://github.com/user-attachments/assets/12354dfc-ba74-4e31-8c12-5a7561c6234c" />

[program16 wap to show  ](#assignment16)

##assignment16



```
package com.mycompany.swati;

/**
 *
 * @author smoot
 */
public class Calc extends javax.swing.JFrame {
    
    private static final java.util.logging.Logger logger = java.util.logging.Logger.getLogger(Calc.class.getName());

    /**
     * Creates new form Calc
     */
    public Calc() {
        initComponents();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        jButton1 = new javax.swing.JButton();
        jLabel1 = new javax.swing.JLabel();
        jLabel2 = new javax.swing.JLabel();
        jButton2 = new javax.swing.JButton();
        jButton3 = new javax.swing.JButton();
        jButton4 = new javax.swing.JButton();
        jButton5 = new javax.swing.JButton();
        jLabel3 = new javax.swing.JLabel();
        jTextField1 = new javax.swing.JTextField();
        jTextField2 = new javax.swing.JTextField();
        jTextField3 = new javax.swing.JTextField();
        jToggleButton1 = new javax.swing.JToggleButton();

        jButton1.setText("jButton1");

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jLabel1.setText("num1");

        jLabel2.setText("num2");

        jButton2.setText("ADD");
        jButton2.addActionListener(this::jButton2ActionPerformed);

        jButton3.setText("SUB");
        jButton3.addActionListener(this::jButton3ActionPerformed);

        jButton4.setText("DIV");
        jButton4.addActionListener(this::jButton4ActionPerformed);

        jButton5.setText("MUL");
        jButton5.addActionListener(this::jButton5ActionPerformed);

        jLabel3.setText("Result");

        jTextField1.setText("1");
        jTextField1.addActionListener(this::jTextField1ActionPerformed);

        jTextField2.setText("2");

        jToggleButton1.setText("Clear");
        jToggleButton1.addActionListener(this::jToggleButton1ActionPerformed);

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(54, 54, 54)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addGroup(layout.createSequentialGroup()
                                .addComponent(jLabel3, javax.swing.GroupLayout.PREFERRED_SIZE, 37, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addComponent(jTextField3, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                .addComponent(jLabel2, javax.swing.GroupLayout.PREFERRED_SIZE, 37, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addComponent(jTextField2, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE))
                            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                                .addComponent(jLabel1, javax.swing.GroupLayout.PREFERRED_SIZE, 37, javax.swing.GroupLayout.PREFERRED_SIZE)
                                .addGap(63, 63, 63)
                                .addComponent(jTextField1, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE))))
                    .addGroup(layout.createSequentialGroup()
                        .addGap(42, 42, 42)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(jButton4)
                            .addComponent(jButton2))
                        .addGap(87, 87, 87)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
                            .addComponent(jButton3)
                            .addComponent(jButton5)))
                    .addGroup(layout.createSequentialGroup()
                        .addGap(123, 123, 123)
                        .addComponent(jToggleButton1)))
                .addContainerGap(127, Short.MAX_VALUE))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addGap(22, 22, 22)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel1)
                    .addComponent(jTextField1, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(26, 26, 26)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel2)
                    .addComponent(jTextField2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(25, 25, 25)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jLabel3)
                    .addComponent(jTextField3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addGap(27, 27, 27)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jButton2)
                    .addComponent(jButton3))
                .addGap(42, 42, 42)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jButton4)
                    .addComponent(jButton5))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(jToggleButton1)
                .addContainerGap(17, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         

        // TODO add your handling code here:
        try {
        double num1 = Double.parseDouble(jTextField1.getText());
        double num2 = Double.parseDouble(jTextField2.getText());

        double result = num1 - num2;

        jTextField3.setText(String.valueOf(result));
    } catch (Exception e) {
        jTextField3.setText("Invalid Input");
    }
}                                        

    private void jButton4ActionPerformed(java.awt.event.ActionEvent evt) {                                         
try {
        double num1 = Double.parseDouble(jTextField1.getText());
        double num2 = Double.parseDouble(jTextField2.getText());

        double result = num1 / num2;

        jTextField3.setText(String.valueOf(result));
    } catch (Exception e) {
        jTextField3.setText("Invalid Input");
    }            
    }                                        

    private void jButton5ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
        
        try {
        double num1 = Double.parseDouble(jTextField1.getText());
        double num2 = Double.parseDouble(jTextField2.getText());

        double result = num1 * num2;

        jTextField3.setText(String.valueOf(result));
    } catch (Exception e) {
        jTextField3.setText("Invalid Input");
    }    
    }                                        

    private void jTextField1ActionPerformed(java.awt.event.ActionEvent evt) {                                            
        // TODO add your handling code here:    
    }                                           

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
        try {
        double num1 = Double.parseDouble(jTextField1.getText());
        double num2 = Double.parseDouble(jTextField2.getText());

        double result = num1 + num2;

        jTextField3.setText(String.valueOf(result));
    } catch (Exception e) {
        jTextField3.setText("Invalid Input");
    }
    }                                        

    private void jToggleButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                               
                                        
    // This sets the text of all boxes to an empty string
    jTextField1.setText("");
    jTextField2.setText("");
    jTextField3.setText("");
    
    // Optional: Places the cursor back in the first box for a new calculation
    jTextField1.requestFocus();
                                     
    }                                              

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ReflectiveOperationException | javax.swing.UnsupportedLookAndFeelException ex) {
            logger.log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(() -> new Calc().setVisible(true));
    }
    // Variables declaration - do not modify                     
    private javax.swing.JButton jButton1;
    private javax.swing.JButton jButton2;
    private javax.swing.JButton jButton3;
    private javax.swing.JButton jButton4;
    private javax.swing.JButton jButton5;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel jLabel3;
    private javax.swing.JTextField jTextField1;
    private javax.swing.JTextField jTextField2;
    private javax.swing.JTextField jTextField3;
    private javax.swing.JToggleButton jToggleButton1;
    // End of variables declaration                   
}
```
<img width="434" height="454" alt="image" src="https://github.com/user-attachments/assets/b55fbe6c-1134-4d5f-8a59-937654587b48" />














