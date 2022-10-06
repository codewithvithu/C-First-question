/*
    First semester - June/July 2017
    Question No : 01
*/

#include<iostream>
using namespace std;

int main(){
    cout << endl;
    string stname; //student name
    cout << "Enter Your Name : ";
    cin >> stname;
    int numofsub; //number of subjects
    int totalsub=0; // total subjects
    cout << "Mention the number of subjects you have taken : ";
    cin >> numofsub;
    double marks;
    double total;
    while (numofsub>0){
        cout << "Enter The Subject Mark :  ";
        cin >> marks;
        total = total+marks;
        totalsub++;
        numofsub--;      
    }
    double avg; // avera«ge
    avg = total/totalsub;
    cout << endl;
    cout << "Name: " << stname << endl;
    cout << "Number of subjects: " << totalsub << endl;
    cout << "Total marks: " << total << endl;
    cout << "Average marks: " << avg << endl;
    if(avg>=75){
        cout << "Grade: A" << endl;
    }
    else if(avg<75 && avg>=60){
        cout << "Grade: B " << endl;
    }
    else if(avg<60 && avg>=50){
        cout << "Grade: C " << endl;
    }
    else if(avg<50 && avg>=40){
        cout << "Grade: S " << endl;
    }
    else{
        cout << "Grade: F" << endl;
    }
    cout << endl << endl;

    return 0;
}
