import java.util.Scanner;

public class ArraySum {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // Read the number of elements
        System.out.print("Enter the number of elements: ");
        int n = sc.nextInt();

        // Create the array
        int[] arr = new int[n];

        // Input the elements
        System.out.println("Enter the elements:");
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        // Find the sum
        int sum = 0;
        for (int i = 0; i < n; i++) {
            sum = sum + arr[i];
        }

        // Display the sum
        System.out.println("Sum of the array elements = " + sum);

        sc.close();
    }
}
