public class Main {
    public static void main(String[] args) {
 
//1. Print Even Numbers from 2 to 10
//Starts from i = 2
//The loop runs while i <= 10
//i += 2 means increase i by 2 each time, so it prints only even numbers:
       
        for (int i = 2; i <= 10; i += 2) {
            System.out.println("Even: " + i);
        }
        System.out.println();
       
//2. Sum of First 5 Natural Numbers
//sum starts at 0
//The loop adds numbers 1 through 5 to sum one at a time
//sum += i means the current value of i is added to sum every loop

        int sum = 0;
        for (int i = 1; i <= 5; i++) {
            sum += i;
        System.out.println("Sum: " + sum); // Output: 15
        }
        System.out.println();
       
//3. Reverse Counting (from 5 to 1)
//Starts from i = 5
//Runs the loop as long as i >= 1
//i-- means decrease i by 1 each time

        for (int i = 5; i >= 1; i--) {
            System.out.println("Reverse: " + i);
        }
        System.out.println();
        
//4. Loop Through an Array 
//fruits.length returns how many items are in the array (in this case, 4)
//Loop starts at index 0 and goes up to 3 (last element)
//fruits[i] accesses the element at index i

        String[] fruits = {"Apple", "Banana", "Mango", "Orange"};

        for (int i = 0; i < fruits.length; i++) {
            System.out.println("Fruit: " + fruits[i]);
        }
        System.out.println();
        
        
//5. Nested For Loop (Multiplication Table of 1 to 3)
//Outer loop: i goes from 1 to 3 → for each number, it prints a multiplication table
//Inner loop: j goes from 1 to 10 → prints i x j = result
//This creates multiplication tables for 1, 2, and 3

        for (int i = 1; i <= 3; i++) {
            System.out.println("Multiplication Table of " + i);
            for (int j = 1; j <= 10; j++) {
                System.out.println(i + " x " + j + " = " + (i * j));
            }
            System.out.println(); // blank line between tables
        }    
    }
}
