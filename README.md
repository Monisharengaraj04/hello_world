# hello_world
just another repository
//
//  main.cpp
//  lineararray
//
//  Created by Monisha on 7/22/20.
//  Copyright © 2020 Monisha. All rights reserved.
//

#include <iostream>
using namespace std;
class linearsearch
{
    public : int a[5], i, key, n;
    inline void search(int a[5])
    {
        cout << "enter the size of the array";
        cin >> n;
        cout << "enter the elements";
        for (i=0;i<5;i++)
        {
            cin >> a[i];
        }
        cout << "enter the key";
        cin >>key;
        for (i=0;i<=5;i++)
        {
            if(a[i] == key)
           {
               cout << "element found";
            }
            else
            {
                cout << " not found";
            }
        }
    }
};
int main()
{   int a[5];
    linearsearch ls;
    ls.search(a);
}
