#include <iostream>
#include <iomanip>
using namespace std;

// function for centered text
void text(string txt) {
  // Get the console width (assuming a default width of 80 characters)
  int consoleWidth = 80;
  int padding = (consoleWidth - txt.length()) / 2;
  cout << setw(padding + txt.length()) << txt << endl;
}

void willkommen(int n) {
  int i=0;
  while (i<=n) {
    cout << "=";
    i++;
  }
  cout << endl;
  
	text("Welcome");
  cout << endl;
  text("text");
  cout << endl;
  
  string text1 = "How Many Players? ";
  int consoleWidth = 80;
  int padding = (consoleWidth - text1.length()) / 2;
  cout << setw(padding + text1.length()) << text1;
}

void ready () {
  text("READY?");
  text("(Press Enter)");
  
  cin.ignore();
  for (int i = 3; i >= 1; --i) {
    int consoleWidth = 80; // Assuming default console width as 80 characters
    int padding = (consoleWidth - 1) / 2;
		cin.ignore(); // Wait for Enter key
    cout << setw(padding) << "" << i << endl; // Padding with spaces
    cin.ignore(); // Wait for Enter key
  }
  
  text("START");
  cout << endl;
}

struct players {
  string playerName;
  int scores;
};
players play[10];
string q1, q2, q3, q4, q5;

void question(int a) {
  for (int i=0; i<a; i++) {
    // player name
    cout << "Player " << i+1 << ": "; cin >> play[i].playerName;
    //questions
    cout << "A or B? "; cin >> q1;
    cout << "A or B? "; cin >> q2;
    cout << "A or B? "; cin >> q3;
    cout << "A or B? "; cin >> q4;
    cout << "A or B? "; cin >> q5;
    cout << endl;
  }
}

// main function
int main () {
  // BLOK 1
  willkommen(80);
  int jumlahPemain;
  cin >> jumlahPemain;
  
  int i=0;
  while (i<=80) {
    cout << "=";
    i++;
  }
  cout << endl;
  
  // BLOK 2 : countdown
  ready();
  cout << endl;
  
  // BLOK 3 : pertanyaan
  
  // input pemain : name and answers
	question(jumlahPemain);
  // akumulasi skor
  // 
  
  
  return 0;
}
