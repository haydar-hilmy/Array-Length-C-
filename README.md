# Array Length in C++

    #include <iostream>

    using namespace std;

    int main(){

      int angka[] = { 1, 2, 3, 4, 5 };

      cout << "Length: " << sizeof(angka)/sizeof(angka[0]) << endl;

      cout << "PRINT IT: " << endl;
      for(int i = 0; i <= sizeof(angka)/sizeof(angka[0]) - 1; i++){
          cout << "Array: " << angka[i] << " [index: " << i << "]" << endl;
      }

      return 0;
    }
