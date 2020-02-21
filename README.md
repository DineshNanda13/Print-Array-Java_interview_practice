# Print-Array-Java_interview_practice
Java program to print an array
package printarray;

/**
 *
 * @author Dinesh Nanda
 */

public class PrintArray {

    public static void main(String[] args) {
        
        int arr [] = {3, 1, 5, 2, 9};
        
        for(int i = 0; i < arr.length; i++){
            System.out.print(arr[i] + " ");
        }
    }
}

