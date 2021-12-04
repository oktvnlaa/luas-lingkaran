# luas-lingkaran
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    /* Enter your code here. Read input from STDIN. Print output to STDOUT */
    float r;
    float phi = 3.14;
    cin>>r;
    
    if (r>0 && r<=100){
   float l = phi*r*r;
   printf ("%.2f", l);
}
    return 0;
}
