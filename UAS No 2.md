
# Ujian Akhir Semester 
<br>Mata Kuliah  : Dasar Pemprograman
<br> Nama  : Marleni Sukarya
<br> NIM  : 1227050069
<br>Jurusan  :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
    2. PROGRAM ELEMEN MATRIKS YANG BISA DI BAGI 3,5 ATAU 7

## Source Code

```
#include <iostream>
using namespace std;
int main(){
	
	cout<<endl;
	cout<<" Nama	: Marleni Sukarya"<<endl;
	cout<<" NIM	: 1227050069"<<endl;
	cout<<" ================================ "<<endl<<endl;
    
		int arr[100][100], jumlahBaris, jumlahKolom, i, j, baris, kolom;
	
	    cout<<" Input jumlah baris: "; cin>>jumlahBaris;
	    cout<<" Input jumlah kolom: "; cin>>jumlahKolom;
	    cout << endl;
	
	    for(i = 0; i < jumlahBaris; i++){
	        for(j = 0; j < jumlahKolom; j++){
	            cout << " Baris " <<i+1<<", kolom "<<j+1<< " = ";
	            cin >> arr[i][j];
	        }
	        cout << endl;
	    }
	
	    cout << " Hasil input nilai : " << endl;
	
	    for(i = 0; i < jumlahBaris ; i++){
	    for(j = 0; j < jumlahKolom; j++){
	        cout << setw(3) << arr[i][j] << " ";
	    }
	    cout << endl;
	    }
	
	    cout << "\n Hasil bilangan yang bisa dibagi 3,5 atau 7 : " << endl;
	
	    for(i = 0; i < jumlahBaris ; i++){
	    for(j = 0; j < jumlahKolom; j++){
	        if(arr[i][j] % 3 == 0 || arr[i][j] % 5 == 0 || arr[i][j] % 7 == 0){
	        cout << setw(3) << arr[i][j] << " ";
	        }
	    }
	    cout << endl;
	    }

    
    cout << endl;
    return 0;
}
```


## Output


