#include <stdio.h>

int main() {
    int arr[100], n;
    int largest, second;

    printf("Enter number of elements: ");
    scanf("%d", &n);

    printf("Enter the elements:\n");
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }

    largest = arr[0];
    second = arr[0];
    for (int i = 1; i < n; i++) {
        if (arr[i] > largest) {
            largest = arr[i];
        }
    }
    for (int i = 0; i < n; i++) {
        if (arr[i] > second && arr[i] < largest) {
            second = arr[i];
        }
    }

    printf("Second largest element = %d\n", second);

    return 0;
}
