#include <iostream>
using namespace std;
int main()
{
float eleman,sayi;
float toplam = 0;
cout << "girmek istediğiniz eleman sayısını giriniz :\n";
cin >> sayi;
for (int i = 0; i < sayi; i++) {
		cin >> eleman;
		toplam += eleman;
	
}
cout << "girilen sayıların ortalaması : " << toplam/ sayi;
return 0;
}
