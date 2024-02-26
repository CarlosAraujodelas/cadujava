#include <iostream>
using namespace std;

struct refei {
     char ingredientes[500];
     int horario;
     struct refei *pProx;
} 

int fez(){
   int question = 0;
   while(question<1 || question>2){
    cout<<"\nfez refeicoes ?\n1-sim\n2-nao";
    cin>>question;
   }
    return question;
}

int quant_ref(){
int quant_r;
    cout<<"\nQuantas refeicoes fez?";
    cin>>quant_r;
    return quant_r;
}


int main()
{
   
   
}
