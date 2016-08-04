#include<iostream>
#include<conio.h>
using namespace std;
class rekrusif{
      private :
              int a,b;
      public:
             long pangkat(int x,int y);
             int proses(){
   cout<<" Nilai untuk memangkatkan dengan menggunakan rekrusif"<<endl;


   cout<<"a : ";
   cin>>a;
   cout<<"b : ";
   cin>>b;
   cout<<a<<" ^ "<<b<<" = "
       <<pangkat(a,b)<<endl;
       system("pause");
   }};
   long rekrusif::pangkat(int a,int n)
   {
       if (n==1)
          return(a);
         else
         return(a * pangkat(a,n-1));
   }
int main(){
    rekrusif z;
    z.proses();
return 0;
}
