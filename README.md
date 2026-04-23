# tiempo
#include <iostream>
using namespace std;

int main()
{
 
 float dias,segundos,horas,minutos,semanas;
 int opcion;
 
 cout<<"escribe el numro de la  opcion de que necesitas:   "<<endl;
 
 cout<<"1.semanas a dias"  <<endl;
 cout<<"2.dias a horas" <<endl;
 cout<<"3.horas a minutos" <<endl;
 cout<<"4.minutos a segundos" <<endl;
 cin>>opcion;
 if (opcion==1){
     
     cout<<"ingresa las semanas:";
     cin>>semanas;
     dias=semanas*7;
     cout<<"dias:"<<dias;

 else if(opcion==2){
     cout<<"ingresa dias: ";
     cin>>dias;
     horas=dias*24;
     cout<<"resultado de horas es :  "<<horas;
     
#includ
e <iostream>
using namespace std;

int main()
{
 
 float días,segundos,horas,minutos,semanas;
 int opcion;
 
 cout<<"escribe el número de la  opción de que necesitas:   "<<endl;
 
 cout<<"1.semanas a días"  <<endl;
 cout<<"2.días a horas" <<endl;
 cout<<"3.horas a minutos" <<endl;
 cout<<"4.minutos a segundos" <<endl;
 cin>>opcion;
 if (opcion==1){
     
     cout<<"ingresa las semanas:";
     cin>>semanas;
     días=semanas*7;
     cout<<"dias:"<<dias;
    
 }
 else if(opcion==2){
     cout<<"ingresa días: ";
     cin>>días;
     horas=días*24;
     cout<<"resultado de horas es :  "<<horas;
     
     
     
    
     
 }
else if(opcion==3){
    cout<<"ingresa la cantidad de horas:";
    cin>>horas;
    minutos=horas*60;
    cout<<"los minutos son :"<<minutos;
    
    
}
else if(opcion==4){
    cout<<"ingresa los minutos:";
    cin>>minutos;
    segundos=minutos*60;
    cout<<"equivale a:"<<segundos;
}
else{
    cout<<"opcion no valida";
}
    return 0;
}


















   return 0;
}
