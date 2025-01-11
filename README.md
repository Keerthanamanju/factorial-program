class Factorial {
    // Recursive method to calculate factorial
    static int factorial(int n) {
        if (n != 0)
            return n * factorial(n - 1);
        else
            return 1;
    }

    public static void main(String[] args) {
        int number = 3;
        int result = factorial(number);
        System.out.println(number + " factorial = " + result);
    }
}


OUTPUT:

PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> javac hello.java
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> java hello.java
3factorial = 6
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> 

