#include <iostream>

using namespace std;

int wiek;

int main() 
{
	cout << "Witaj w programiem, ktory na podstawie wieku powie Ci na jakim etapie edukacji jestes." << endl;
	cout << "Istnieje jednak jedno zalozenie mowiace, iz nie kiblowales :)" << endl << endl;
	cout << "Podaj ile masz lat: ";
	
	cin>>wiek; cout << endl;
	
	if (wiek<=5)
	{
		cout << "Mozesz lecz nie musisz uczeszczac do przedszkola.";
	}
	else if (wiek<=13)
	{
		cout << "Uczeszczas do szkoly podstawowej.";
	}
	else if (wiek<=17)
	{
		cout << "Uczeszczas do szkoly sredniej(liceum lub technikum).";
	}
	else if (wiek<=18)
	{
		cout << "Uczeszczas do technkium lub jestes absolwentem liceum." << endl << "Jezeli jestes absolwentem liceum to mozesz lecz nie musisz uczeszczac do szkoly wyzszej.";
	}
	if (wiek>=19)
	{
		cout << "Jestes absolwentem szkoly sredniej(liceum lub technikum)." << endl << "Mozesz lecz nie musisz uczeszczac do szkoly wyzszej.";
	}
	
	return 0;
}
