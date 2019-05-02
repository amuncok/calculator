# calculator
try to make calculator
<html>

#include <iostream>



using namespace std;



int main()

{
  
	float a,b,hasil;

	char aritmatika;


	cout << "slamat datang di program calculator \n\n";

  
  
	// memasukkan input dari user
 
	cout << "masukkan nilai pertama: ";

  cin >> a;

  cout << "pilih operator +,-,/,*: ";

  cin >> aritmatika;
  cout << "masukkan nilai kedua: ";

  cin >> b;
  
  cout << "\nhasil perhitungan: ";

  cout << a << aritmatika << b;


  
  if (aritmatika == '+' ){

      hasil = a + b;

  } else if (aritmatika == '-' ){
      hasil = a - b;

  } else if (aritmatika == '/' ){
      hasil = a / b;

  } else if (aritmatika == '*' ){
      hasil = a * b;

  } else {
      cout << "operator anda salah" << endl;

  }


  
  <cout> << " = " << hasil << endl


  
  cin.get();

  return 0;
}
