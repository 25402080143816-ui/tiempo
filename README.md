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


   
}
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



