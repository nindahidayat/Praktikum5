# Praktikum5
  # latihan1
  ## cara menyusun algoritma untuk menginput bilangan sebanyak-banyaknya sampai kondisi apabila yang di inputkan adalah angka 0. dengan menggunakan do while

  ## berikut kode nya

#include <iostream>

using namespace std;

int main()
{
	int a,max=0;

	do {
		cout << "masukan bilangan :";
	cin >> a;

	if (a>max)
		max=a;
	}

	while (a!=0);
	cout << max;

	return 0;

	
}

  ## ini adalah cara dimana mencari bilangan sebanyak-banyaknya dengan inputan terahir angka 0. maka angka yang dimasukan akan menemukan bilang terberbesar.
contoh
masukan bilangan = 45
masukan bilangan = 40
masukan bilangan = 37
masukan bilangan = 32
masukan bilangan = 0
hasil nya = 45
#maka hasil mencari bilangan terbesar adalah 45


##SOAL2
