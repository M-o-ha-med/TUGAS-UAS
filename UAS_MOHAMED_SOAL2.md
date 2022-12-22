# TUGAS-UAS
Ujian Akhir Semester 
<br>Mata Kuliah : Dasar pemrograman 
<br>Nama : Mohamed
<br>NIM : 1227050074
<br>Jurusan :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum 

matriks adalah susunan bilangan, simbol, atau ekspresi yang disusun dalam baris dan kolom sehingga membentuk suatu bangun persegi.
Array adalah larik yang berisi kumpulan data dengan tipe serupa 
Multi-dimensional Array adalah array yang menyimpan array lain pada setiap indeks,
bukan elemen tunggal. Dengan kata lain, kita dapat mendefinisikan array multi dimensi sebagai array dari suatu array.
operasi modulus adalah sebuah operasi yang menghasilkan sisa pembagian dari suatu bilangan terhadap bilangan lainnya.
Dalam bahasa pemrograman operasi ini umumnya dilambangkan dengan simbol %, mod atau modulo, tergantung bahasa pemrograman yang digunakan.
## Source Code 
			#include <iostream>
			using namespace std;
			int main()
		{
			
		cout << "==============================\n";
		cout << "Nama  : Mohamed\nNIM  : 1227050074\n";
		cout << "==============================\n";
		cout<<"\tsoal nomor 2\n";
		cout<<"==============================\n";
		char jawaban;
		int data[100][100] = {};
		
		do{
			for (int i = 0; i < 3; i++)
			{
				for (int j = 0; j < 2; j++)
				{
					cout << "Masukkan Nilai  [" << i << "][" << j << "] :";
					cin >> data[i][j];
					
				}
			}
		
			for (int i = 0; i < 3; i++)
			{
				for (int j = 0; j < 2; j++)
					if (data[i][j] % 3 == 0 || data[i][j] % 5 == 0 || data[i][j] % 7 == 0){
							cout << data[i][j] << " ";
							cout << endl;
						
					}
					
					else{
						cout<<" tidak ada input yang habis dibagi dengan 3,5,dan 7"<<endl;
						break;
						
					}
			}	cout<<"==============================\n";
			
			cout<<"Lanjut ? (Y/N) : ";
			cin>> jawaban;
			if(jawaban == 'n')
		
			break;
			if(jawaban != 'y'  || jawaban != 'Y')
			continue;
			
		}
		
		while(jawaban != 'N'  );
		}
  
## Output

![Screenshot 2022-12-22 173719](https://user-images.githubusercontent.com/120997421/209116686-67d599ab-9ddb-4907-ae73-63f579f54a85.png)

























































