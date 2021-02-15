# Lab-22.40-
#include <iostream>
using namespace std;
int main() {
  
  int i, temperature [5], max, min;
  double average; int sum = 0;
  cout << "Enter Temperature: " << endl;
  cin >> temperature[0];
  max = temperature [0];
  min = temperature[0];
  for (i = 1; i < 5; i++) {
    cin >> temperature[i];
  if (temperature[i] > max)
    max = temperature [i];
  if (temperature[i] < min)
    min = temperature [i];
  sum += temperature[i];
  }
  average = sum/ 5;
  cout << "The average temperature is " << average << endl;
  cout << "The highest temperature is " << max << endl;
  cout << "The lowest temperature is " << min << endl;
  
}
