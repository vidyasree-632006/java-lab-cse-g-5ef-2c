# java-lab-cse-g-5ef-2c
# experiment-2c
# construct implementation 
source code 
java 
```
class Student{
String name;
int age;
int marks;
Student(String n , int a,int m){
name=n;
age = a;
marks = m;}
void display(){
System.out.println("name:"+name);
System.out.println("age:"+age);
System.out.println("marks:"+marks);
}
public static void main (String[]args){
Student s1=new Student("Alice" , 20 , 85);
s1.display();}}
eaddit: 
import java.util.Scanner;

public class Fibonacci {
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter the value of n: ");
        int n = sc.nextInt();


        int a = 0, b = 1, sum = 0;

        System.out.print("The first " + n + " Fibonacci numbers are: ");

        for (int i = 1; i <= n; i++) {
            System.out.print(a );
            sum += a;
if (i<n){
System.out.print(", ");}

                      int next = a + b;
            a = b;
            b = next;
        }

        System.out.println("\nSum of the first " + n + " Fibonacci numbers: " + sum);
    }
}
```
# OUTPUT: 
[!output of exp 2c](e23.png)
