# Experiment-7

# Insert an element in an Array

## Aim:
  To write a Java program to insert an element in an Array.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create an array with a name of your choice.

Step 3 : Using Scanner, Input a number or a element from the user.

Step 4 : Using for loop insert the input element at the end of the array.

Step 5 : Display the append array in the terminal.

## Program

```
import java.util.Scanner;
public class Insert_Array
{
public static void main(String[] args)
{
int n, pos, x;
Scanner s = new Scanner(System.in);
System.out.print("Enter no. of elements you want in array:");
n = s.nextInt();
int a[] = new int[n+1];
System.out.println("Enter all the elements:");
for(int i = 0; i < n; i++)
{
a[i] = s.nextInt();
}
System.out.print("Enter the position where you want to insert
element:");
pos = s.nextInt();
System.out.print("Enter the element you want to insert:");
x = s.nextInt();
for(int i = (n-1); i >= (pos-1); i--)
{
a[i+1] = a[i];
}
a[pos-1] = x;
System.out.print("After inserting:");
for(int i = 0; i < n; i++)
{
System.out.print(a[i]+",");
}
System.out.print(a[n]);
}
}
```


## Output

![image](https://github.com/SaiDarshan2003/Experiment-9/assets/94692595/cf07a2e1-fb33-4abb-a1e8-857299caba80)

## Result 
  We have successfully created a Java program to Insert an element in an Array.
