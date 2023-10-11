this is a c++ program to find the simple interest
#include <iostream>
using namespace std;

int main(){
    //Declear variables for principal,rate and time
    double principal , rate, time;

    //Input the principal amount
    cout << "Enter the principal amount :";
    cin >> principal;

    //Input the rate 
    cout << "Enter the rate of interest (in persentage):";
    cin >> rate;

    //Input the time (in years)
    cout << "Enter the time(in years):";
    cin  >> time;

    //Calculate the simple interest
    double simpleInterest = (principal * rate * time) / 100.0;

    //Display the simple interest
    cout << "Simple Interest:" << simpleInterest << endl;
