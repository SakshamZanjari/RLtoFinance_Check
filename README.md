# RLtoFinance_Check
This is just a random code added to learn to use Github
This is just to check how to use branch option
#include<simplecpp>
#include<iomanip>

main_program{
int n,i=0;
cin>>n;
float cos,nu=0,a=0,b=0;
repeat(n){
i++;
float a_i,b_i;
cin>>a_i>>b_i;
nu=nu+a_i*b_i;
a=a+a_i*a_i;
b=b+ b_i*b_i;
}
cos=nu/(sqrt(a)*sqrt(b));
cout<<fixed<<setprecision(2)<<cos;
}
