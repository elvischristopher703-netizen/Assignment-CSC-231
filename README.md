# Assignment-CSC-301
public class SumAndAverage {
    public static void main(String[] args) {
        // Declare five integers (primitive types)
        int a = 10;
        int b = 20;
        int c = 15;
        int d = 25;
        int e = 30;

        // Compute the sum
        int sum = a + b + c + d + e;

        // Compute the average
        double average = sum / 5.0;  // use 5.0 to avoid integer division

        // Output the results
        System.out.println("Sum = " + sum);
        System.out.println("Average = " + average);
    }
}
