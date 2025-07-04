# Assignment-
Assignment 
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // Static array of size 10

    cout << "Enter 10 integers:" << endl;
    for (int i = 0; i < 10; i++) {
        cin >> arr[i];
    }

    cout << "You entered:" << endl;
    for (int i = 0; i < 10; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}
import java.util.Scanner;

public class StaticArrayExample {
    public static void main(String[] args) {
        int[] arr = new int[10]; // Static array of size 10
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter 10 integers:");
        for (int i = 0; i < arr.length; i++) {
            arr[i] = scanner.nextInt();
        }

        System.out.println("You entered:");
        for (int i = 0; i < arr.length; i++) {
            System.out.print(arr[i] + " ");
        }
        scanner.close();
    }
}
