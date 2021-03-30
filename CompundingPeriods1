#include <iostream>
#include <cmath>
#include <iomanip>
#include <fstream>
using namespace std;

int main()
{
    double principalA, interestRateA, finalBalanceA;
    double principalB, interestRateB, finalBalanceB;
    double principalC, interestRateC, finalBalanceC;
    int yearsA, cperiodsA, yearsB, cperiodsB, yearsC, cperiodsC;

// First Compounding Period
    ifstream inData;
    inData.open("invest1.txt");
// Round to 2 decimal places
cout << fixed << showpoint << setprecision(2);
    //Display totals
    inData >> principalA >> yearsA >> interestRateA;
    cout << "Enter the number of compounding periods for investment of $" << principalA << ": ";
    cin >> cperiodsA;
 finalBalanceA = principalA * pow((1 + ((interestRateA/100)/cperiodsA)), cperiodsA*yearsA);
    cout << "Principal Amount" << setfill ('.') << setw (50) << "$" << principalA << endl;
    cout << "Interest Rate" << setfill ('.') << setw (56) << interestRateA << "%" << endl;
    cout << "Years Invested" << setfill ('.') << setw (51) << "" << yearsA << endl;
    cout << "Compounding Periods" << setfill ('.') << setw (46) << "" << cperiodsA << endl;
    cout << "FINAL BALANCE" << setfill ('.') << setw (2) << "$" << finalBalanceA << endl << endl;
inData.close();

//Second Compound Period
ifstream inData2;
    inData2.open("invest2.txt");
    //Display totals
    inData2 >> principalB >> yearsB >> interestRateB;
    cout << "Enter the number of compounding periods for investment of $" << principalB << ": ";
    cin >> cperiodsB;
 finalBalanceB = principalB * pow((1 + ((interestRateB/100)/cperiodsB)), cperiodsB*yearsB);
    cout << "Principal Amount" << setfill ('.') << setw (50) << "$" << principalB << endl;
    cout << "Interest Rate" << setfill ('.') << setw (56) << interestRateB << "%" << endl;
    cout << "Years Invested" << setfill ('.') << setw (51) << "" << yearsB << endl;
    cout << "Compounding Periods" << setfill ('.') << setw (46) << "" << cperiodsB << endl;
    cout << "FINAL BALANCE" << setfill ('.') << setw (53) << "$" << finalBalanceB << endl << endl;
inData2.close();

//Third Compound Period
ifstream inData3;
    inData3.open("invest3.txt");
    //Display totals
    inData3 >> principalC >> yearsC >> interestRateC;
    cout << "Enter the number of compounding periods for investment of $" << principalC << ": ";
    cin >> cperiodsC;
 finalBalanceC = principalC * pow((1 + ((interestRateC/100)/cperiodsC)), cperiodsC*yearsC);
    cout << "Principal Amount" << setfill ('.') << setw (50) << "$" << principalC << endl;
    cout << "Interest Rate" << setfill ('.') << setw (56) << interestRateC << "%" << endl;
    cout << "Years Invested" << setfill ('.') << setw (51) << "" << yearsC << endl;
    cout << "Compounding Periods" << setfill ('.') << setw (46) << "" << cperiodsC << endl;
    cout << "FINAL BALANCE" << setfill ('.') << setw (53) << "$" << finalBalanceC << endl;
inData3.close();

    return 0;
}
