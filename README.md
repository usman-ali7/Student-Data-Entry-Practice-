# Student-Data-Entry-Practice-
//This program is written for practice purpose and its very basic and easy to learn Structure from this program.Asso This program is Wriiten in C++ language.
#include<iostream>
#include<string>
using namespace std;
struct Student
{
	int rollnum,class_of_student;
	string name;

	char grade;
	
};


int main()
{
	float percentage;
	float eng_marks,math_marks,urdu_marks,sum;
int	Total =500;
		Student s[3];
	for(int i=0;i<3;i++)
	{
		cout<<"~~~~~~~~ Data Entry of Student no"<<" "<<i+1 <<" ~~~~~~~"<<endl;
		cout<<"Enter your name:";
		cin>>s[i].name;
		cout<<"Enter your Roll Number :";
		cin>>s[i].rollnum;
		cout<<"Enter your class :";
		cin>>s[i].class_of_student;
		cout<<"Enter your English marks:";
		cin>>eng_marks;
		cout<<"Enter your Urdu Marks:";
		cin>>urdu_marks;
		cout<<"Enter your Math Marks:";
		cin>>math_marks;
		sum=eng_marks+urdu_marks+math_marks;
	percentage=sum/Total*100;	
		
		cout<<"Enter your grade:";
		cin>>s[i].grade;
	cout<<"Data Saved Succesfully:"<<endl;	
	}
	
	
	for(int i=0;i<3;i++)
	{
	cout<<"Data Saved Succesfully:"<<endl;	
	cout<<"Your Name is:"<<s[i].name<<endl;
	cout<<"Your Roll Num is:"<<s[i].rollnum<<endl;
	cout<<"Your Class is:"<<s[i].class_of_student<<endl;
	cout<<"Your English Marks is:"<<eng_marks<<endl;
	cout<<"Your Urdu Marks is:"<<urdu_marks<<endl;
	cout<<"Your Maths marks is:"<<math_marks<<endl;
       cout<< "Your Total Marks is:"<<sum<<endl;
       cout<<"Your Percentage is:"<<percentage<<endl;
	cout<<"Your Grade is:"<<s[i].grade<<endl;
	cout<<"*------------Thank You ---------------*\n\n";
	 	
	
	}
	return 0;
}
