# 12-Arrays
#include 
using namespace std; 
int main(){ 
	int i; int user[5]; 
	int result=0; 
	cout << "subject mark for 5 subjects" << endl;
	for (i = 0; i < 5; i++) { cout << "Enter your subject's mark: ";
	cin >> user[i];
	if (cin.fail()|| user[i]>100||user[i]<0) { 
		system("cls");
	cout << "Error"; return 0; } result += user[i]; } 
	cout << "Average is: " << result / 5; return 0;

using namespace std;
int main(){
	string month[] = {"january","february","march","april","may","june","july","august","september","october","november","december"};
	int i; int arrsize = sizeof(month) / sizeof(month[0]);
	for (i = 0; i <arrsize; i++) { 
		cout << month[i] << endl; } 
	return 0;
}
