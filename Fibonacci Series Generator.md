# # Fibonacci Series Generator

## 🧠 Aim

To write a program to generate the Fibonacci series for `n` numbers using a function that:
- Has no return type.
- Takes no arguments.

## 📋 Algorithm

1. Define a function `fib()` that calculates the Fibonacci series.
2. Inside `fib()`:
   - Read input value `n` from the user.
   - Initialize two variables: `a = 0`, `b = 1`.
   - Print the first two Fibonacci numbers: `a` and `b`.
   - Use a loop to generate and print the next `n-2` Fibonacci numbers.
3. In the `main()` function:
   - Call the `fib()` function.
   - Return 0 to indicate successful program termination.

## 🧾Program
```
#include <stdio.h>
void fib() {
    int n, i;
    int a = 0, b = 1, c;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    if(n >= 1) {
        printf("%d ", a);
    }
    if(n >= 2) {
        printf("%d ", b);
    }

    for(i = 3; i <= n; i++) {
        c = a + b;
        printf("%d ", c);
        a = b;
        b = c;
    }
}
```
int main() {
    fib();
    return 0;
}

## Sample Output
<img width="437" height="251" alt="image" src="https://github.com/user-attachments/assets/3ac54d45-5c53-4958-bc3d-d3a888ac2476" />

## Result
program to generate the Fibonacci series for `n` numbers using a function that:Has no return type, Takes no arguments is written.t

