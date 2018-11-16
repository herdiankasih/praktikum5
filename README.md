# praktikum5

Latihan1 : program menggunakan do while

=>> Menginputkan bilangan sebanyak - banyaknya, sampai kondisi bilangan yang dimasukkan adalah angka nol


=>> Alur algoritma :

1. membuat inisialisasi "int a, max=0;"
2. membuat perulangan dengan menggunakan Do While,

	a. di dalam body Do terdapat aksi sebagai berikut :
		- memasukan nilai a "cin >> a;"
		- membuat if statement dengan kondisi a lebih besar dari max "a>max"
		- jika a lebih besar dari max maka max sama dengan a "max=a"

	b. di dalam while terdapat kondisi a tidak sama dengan nol "a!=0"
3. mencetakan nilai terbesar yang di inputkan tersebut ke consol "cout << max;"


=>> Flowchart latihan1 :

![flowchart_latihan1](https://user-images.githubusercontent.com/43899109/48644047-0b9ec480-ea14-11e8-92f7-e0fd2ab564ca.jpg)


==> Kode C++ :

#include <iostream>

using namespace std;

int main()
{
	int a,max=0;

	do{
		cout << "masukan bilangan : ";
	cin >> a;

	if (a>max)
		max=a;
	}
	while (a!=0);

	cout << max;

	return 0;
}


=>> Hasil screenshoot latihan1 :

![hasil_latihan1](https://user-images.githubusercontent.com/43899109/48644126-47d22500-ea14-11e8-89a2-749ce23b2e67.jpg)


Latihan2 : program menggunakan operator logika or

menginputkan tiga buah bilangan, cetak "benar" bila salah satu bilangan merupakan jumlah dari dua buah bilangan yang lain, jika tidak

(selain itu) cetak "salah"

=>> Alur algoritma :

1. membuat inisialisasi a,b,c "int a,b,c;"
2. menginputkan nilai a,b,c "cin >> a" "cin >> b;" "cin >> c;"
3. membuat if statement dengan menuliskan 3 kondisi yang di pisahkan oleh Or
	1. (a+b==c) or
	2. (a+c==b) or
	3. (b+c==a)
4. jika nilai kondisi di atas bernilai true maka cetak "Benar" jika false maka cetak "Salah"

==>> Flowchart latihan2 :

![flowchart_latihan2](https://user-images.githubusercontent.com/43899109/48644390-ff673700-ea14-11e8-87ff-435ef8f1ec55.jpg)


=>> Kode C++ program :

#include <iostream>

using namespace std;

int main()
{
	int a,b,c;

	cout << "masukan nilai a : ";
	cin >> a;
	cout << "masukan nilai b : ";
	cin >> b;
	cout << "masukan nilai c : ";
	cin >> c;

	if ((a+b==c) or (a+c==b) or (b+c==a))
		cout << "benar";
	else
		cout << "salah";

	return 0;
}


=>> Hasil screenshoot latihan2 :

![hasil_latihan2_01](https://user-images.githubusercontent.com/43899109/48644453-30e00280-ea15-11e8-9ef3-863a5782da36.jpg)

![hasil_latihan2_02](https://user-images.githubusercontent.com/43899109/48644454-30e00280-ea15-11e8-8383-65d362d0a446.jpg)

![hasil_latihan2_03](https://user-images.githubusercontent.com/43899109/48644456-30e00280-ea15-11e8-878a-36632e3646c7.jpg)

![hasil_latihan2_04](https://user-images.githubusercontent.com/43899109/48644457-31789900-ea15-11e8-82ec-52a611958d6d.jpg)
