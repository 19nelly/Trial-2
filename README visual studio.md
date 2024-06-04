#include <iostream>
using namespace std;
int main() {
    int choice;
    cout<<"1 is for add students"<<endl;
    cout<<"2 is for view students"<<endl;
    cout<<"3 is for view clubs or societies"<<endl;
    cout<<" 4 is for view sports"<<endl;
    cout<<"5 is for view grouped students"<<endl;
    cout<<"6 is for save all files"<<endl;
    cout<<"7 is for exit"<<endl;
    cout<<"Enter choice"<<endl;
    cin>>choice;

    switch(choice){
      case 1:
    cout<<"Enter First Name:"<<endl;
    cout<<"Enter Surname:"<<endl;
    cout<<"Enter Age:"<<endl;
    cout<<"Enter Gender:"<<endl;
    cout<<"Enter BBIT group:"<<endl;
    break;
    case 2:
        cout<<"another menu";
    break;
    case 3:
        cout<<"another menu";
    break;
    case 4:
        cout<<"view selection of sports";
    break;
    case 5:
        cout<<" shows the students with the groups";
    break;
    case 6:
        cout<<" save";
    break;
    case 7:
        cout<<"exit";

    default:
        cout<<"Invalid choice";
    break;}

    system("pause");
    return 0;
}



 
