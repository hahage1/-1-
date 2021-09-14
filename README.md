# -1-
靓仔专用
#include<iostream>
#include<string>
using namespace std;
class person
{
    public:
    person(string name="xiaoming",int salary=40000, string tel="110",int age=18);
    void display();

    private:
    string m_name;
    int m_salary;
    string m_tel;
    int m_age;
};
 person::person(string name,int salary, string tel,int age)
{
    m_name=name;
    m_salary=salary;
    m_tel=tel;
    m_age=age;
}
void person::display()
{
    cout<<m_name<<endl;
    cout<<m_salary<<endl;
    cout<<m_tel<<endl;
    cout<<m_age<<endl;
}
int main()
{
    person p1;
    p1.display();
    return 0;
}
