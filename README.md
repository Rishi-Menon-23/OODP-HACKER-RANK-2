# OODP-HACKER-RANK-2

BASIC DATA TYPES

#include <iostream>
#include <cstdio>
using namespace std;
int main() {
    // Complete the code.
    int a;
    long b;
    char c;
    float d;
    double e;
    scanf("%d %ld %c %f %lf", &a, &b, &c, &d, &e);
    printf("%d\n%ld\n%c\n%f\n%lf", a, b,c, d, e);
    return 0;
}
  
  
  
CONDITIONAL STATEMENTS
  
[4:16 PM, 9/11/2022] Akshay: #include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    if(n == 1)
    {
        printf("one");
    }
    else if(n==2)
    {
        printf("two");
    }
    else if(n==3)
    {
        printf("three");
    }
    else if(n==4)
    {
        printf("four");
    }
    else if(n==5)
    {
        printf("five");
    }
    else if(n==6)
    {
        printf("six");
    }
    else if(n==7)
    {
        printf("seven");
    }
    else if(n==8)
    {
        printf("eight");
    }
    else if(n==9)
    {
        printf("nine");
    }
    else
    {
        printf("Greater than 9");
    }
return 0;
}
[4:16 PM, 9/11/2022] Akshay: class Student 
{
    private:
    int scores[5];
    public:
    void input()
    {
        for (int i = 0; i < 5; i++) 
        {
            cin >> scores[i];
        }
    }
    int calculateTotalScore() 
    {
        int count = 0;
        for (int i = 0; i < 5; i++) 
        {
            count += scores[i];
        }
        return count;
    }
};
                              
CLASS OF OBJETCS
                              
class Student 
{
    private:
    int scores[5];
    public:
    void input()
    {
        for (int i = 0; i < 5; i++) 
        {
            cin >> scores[i];
        }
    }
    int calculateTotalScore() 
    {
        int count = 0;
        for (int i = 0; i < 5; i++) 
        {
            count += scores[i];
        }
        return count;
    }
};
                              
                              
STRUCTS
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;

struct Student
{
    int age, standard;
    string first_name, last_name;
};

int main() 
{
    Student st;
    
    cin >> st.age >> st.first_name >> st.last_name >> st.standard;
    cout << st.age << " " << st.first_name << " " << st.last_name << " " << st.standard;
    
    return 0;
} 
  
ARRAY OF N( DONE USING SCALA AS C++ IS NOT PRESENT)
  #include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;

struct Student
{
    int age, standard;
    string first_name, last_name;
};

int main() 
{
    Student st;
    
    cin >> st.age >> st.first_name >> st.last_name >> st.standard;
    cout << st.age << " " << st.first_name << " " << st.last_name << " " << st.standard;
    
    return 0;
}
   
