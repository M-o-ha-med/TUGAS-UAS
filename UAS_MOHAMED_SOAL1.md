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
transpos dari sebuah matriks adalah operator yang membalikkan posisi matriks sepanjang diagonal utamanya
dengan kata lain, operator ini menukar setiap baris dan kolom pada matriks

## Source Code 
					#include<iostream>
					using namespace std;
					int main()
					{
					  cout<<"==============================\n";
					  cout<<"Nama  : Mohamed\nNIM  : 1227050074\n";
					  cout<<"==============================\n";
					  cout<<"\tsoal nomor 1\n";
					  cout<<"==============================\n";
					  int a[2][3] = {{ },{ }};
					  char jawaban;
					  do{
						 for(int i = 0; i<2;i++){
					  	for(int j = 0; j <3;j++){
					  	cout<<"Masukkan angka untuk nilai ke ["<<i<<"]["<<j<<"]";
					  	       
					  	cin>>a[i][j];
					  	}
					 }
					
					 
					 
					  
					  cout<<"==============================\n";
					  cout<<"      sebelum transponse\n";
					  cout<<"==============================\n";
					     
					    for(int i = 0; i<3;i++){
					  	for(int j = 0; j <2;j++)
					  		cout<<a[j][i]<<" ";
					  		cout<<endl;
					    }
					    cout<<endl;
					    cout<<endl;
					    
					     
					  cout<<"==============================\n";
					  cout<<"     setelah transponse\n";
					  cout<<"==============================\n";
					    
					    
					    for(int i = 0; i<2;i++){
					  	for(int j = 0; j <3;j++)
					  		cout<<a[i][j]<<" ";
					  		cout<<endl;
					    }
					    	
					  
					
					  	cout<<"Lanjut ? (Y/N) : ";
						cin>> jawaban;
						if(jawaban == 'n')
						break;
						if(jawaban != 'y'  || jawaban != 'Y')
						break;
						
					}
					
					while(jawaban != 'N'  );
					}

       

## Output
==============================
Nama  : Mohamed
NIM  : 1227050074
==============================
        soal nomor 1
==============================
Masukkan angka untuk nilai ke [0][0]1
Masukkan angka untuk nilai ke [0][1]2
Masukkan angka untuk nilai ke [0][2]3
Masukkan angka untuk nilai ke [1][0]4
Masukkan angka untuk nilai ke [1][1]5
Masukkan angka untuk nilai ke [1][2]6
==============================
      sebelum transponse
==============================
1 4
2 5
3 6


==============================
     setelah transponse
==============================
1 2 3
4 5 6
Lanjut ? (Y/N) :


