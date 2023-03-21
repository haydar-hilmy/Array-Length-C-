# Array Length in C++

disini akan membuat array dari tipe data integer
lalu menghitung panjang dari array menggunakan sizeof()

    #include <iostream>

    using namespace std;

    int main(){

        int angka[] = {1, 2, 3, 4, 5};

        cout << "Length: " << sizeof(angka)/sizeof(angka[0]) << endl;
        cout << "sizeof(angka[0]): " << sizeof(angka[2]) << endl;
        cout << "sizeof(angka): " << sizeof(angka) << endl;

        cout << "PRINT IT: " << endl;
        for(int i = 0; i < sizeof(angka)/sizeof(angka[0]); i++){
            cout << "Array: " << angka[i] << " [index: " << i << "]" << endl;
        }

        return 0;
    }


## Output

![App Screenshot](https://raw.githubusercontent.com/haydar-hilmy/Array-Length-Cpp/main/Output.png)

