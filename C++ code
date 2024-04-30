#include<iostream>

using namespace std;

class BasicInfo
{
public:
char name[25];
int age;
char sex[10];
int emp_id;
void getdata()
{

cout<<"Enter Employee Details\n";

cout<<"Name-:";

cin>>name;

cout<<"Age-:";

cin>>age;

cout<<"Sex-:";

cin>>sex;

cout<<"Employee ID-:";

cin>>emp_id;

}

};

class DepartmentInfo

{

public:

char dept[25];

void getdata()

{

cout<<"Department Name-:";

 

 

cin>>dept;

}

 

};

class Employee:public BasicInfo,public DepartmentInfo

{

 

public:

int salary;

void getdata()

{

BasicInfo::getdata();

DepartmentInfo::getdata();

cout<<"Salary-:";

cin>>salary;

}

void display()

{

 

cout<<"\n**EMPLOYEE DETAILS**";

cout<<"\nName-:"<<name;

cout<<"\nAge-:"<<age;

cout<<"\nSex-:"<<sex;

cout<<"\nEmployee ID-:"<<emp_id;

cout<<"\nDepartment Name-:"<<dept;

cout<<"\nSalary-:"<<salary;

}

 

};

int main()

{

Employee obj;

obj.getdata();

obj.display(); }

