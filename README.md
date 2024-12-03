#include <iostream>
using namespace std;

int main() {
    const int SIZE = 3; // Define the size of the matrices
    int matrix1[SIZE][SIZE];
    int matrix2[SIZE][SIZE];

    // Input elements for the first matrix
    cout << "Enter elements for Matrix 1 (3x3):" << endl;
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            cout << "Element [" << i << "][" << j << "]: ";
            cin >> matrix1[i][j];
        }
    }

    // Input elements for the second matrix
    cout << "\nEnter elements for Matrix 2 (3x3):" << endl;
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            cout << "Element [" << i << "][" << j << "]: ";
            cin >> matrix2[i][j];
        }
    }

    // Display the first matrix
    cout << "\nMatrix 1:" << endl;
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            cout << matrix1[i][j] << " ";
        }
        cout << endl;
    }

    // Display the second matrix
    cout << "\nMatrix 2:" << endl;
    for (int i = 0; i < SIZE; i++) {
        for (int j = 0; j < SIZE; j++) {
            cout << matrix2[i][j] << " ";
        }
        cout << endl;
    }

    return 0;
}

#include <iostream>
using namespace std;

int main() {
    const int size = 4; // Define matrix size (4x4)
    int matrix1[size][size], matrix2[size][size], sumOfMatrices[size][size];

    // Input for the first matrix
    cout << "Enter elements for the first 4x4 matrix:" << endl;
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            cout << "matrix1[" << i << "][" << j << "]: ";
            cin >> matrix1[i][j];
        }
    }

    // Input for the second matrix
    cout << "\nEnter elements for the second 4x4 matrix:" << endl;
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            cout << "matrix2[" << i << "][" << j << "]: ";
            cin >> matrix2[i][j];
        }
    }

    // Calculate the sum of the matrices
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            sumOfMatrices[i][j] = matrix1[i][j] + matrix2[i][j];
        }
    }

    // Display the first matrix
    cout << "\nMatrix 1:" << endl;
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            cout << matrix1[i][j] << " ";
        }
        cout << endl;
    }

    // Display the second matrix
    cout << "\nMatrix 2:" << endl;
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            cout << matrix2[i][j] << " ";
        }
        cout << endl;
    }

    // Display the sum of the matrices
    cout << "\nSum of Matrices:" << endl;
    for (int i = 0; i < size; i++) {
        for (int j = 0; j < size; j++) {
            cout << sumOfMatrices[i][j] << " ";
        }
        cout << endl;
    }

    return 0;
}
