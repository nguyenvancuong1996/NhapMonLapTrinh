#include<iostream>
using namespace std;
main(){
	int a, b, c;
	float dtb;
	
	string t;
	
	cout << " tensv : " << endl;
	cin>>t;
	cout << " nhap diem 3 mon: " << endl;
	cin>>a>>b>>c;
	dtb = float(a + b +c )/3;
	
	if ( dtb >=8 ){
		cout << "  xep loai xuat sac "<< dtb << endl;
	}
	
	if  ( 7<=dtb&&dtb<8){
		cout <<" xep loai gioi"<< dtb<< endl;
	}
		
	if ( 6 <= dtb&&dtb <7){
		cout <<" xep loai kha " << dtb<<endl;
	}
	
	if (5 <= dtb&&dtb < 6)
	{
		cout << " xep loai trung binh "<<dtb<< endl;
	}
	
	if  ( dtb < 5)
	{
		cout <<" xep loai yeu " << dtb<<endl;
	}

}
