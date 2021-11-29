# Nov-28

#include <iostream>
#include <array>
using namespace std;

int main()
{
    array <string, 4> arr = { "Mars bar","Snickers","Bounty","Whispa" };
    cout << arr.at(1) << endl;
    cout << arr[1] << endl;

    cout << arr.front() << endl;
    cout << arr.back() << endl;

    for (int i = 0; i < arr.size(); i++) {
        cout << arr.at(i) << ",";
    }
    cout << endl;
                
                
 ------------------------------------------------------------------------------------------------------------------------------------------------------------
                
                
                 int main()
    {
     
        array<int, 5> numbers = { 33, 5, 7, 99, 83, };
        reverse(numbers.begin(), numbers.end());
        for (int num : numbers) {
            cout << num << " ";
        }
    }
  --------------------------------------------------------------------------------------------------------------------------------------------------------------
  
  #include <iostream>
#include <algorithm>
    using namespace std;
    
    int main()
    {
        int randomArry[10];
        for (int i = 0; i < 10; i++)
        {
            //rand is use ro generate a random  variable
            //using 50% to make sure number aren't too big
            randomArray[i] = rand() % 50;
            cout << randomArray[i] << endl;

        }
        int n[1000];
        for (int i = 0; i < 1000; i++)
        {
            n[i] = rand() % 100;
            cout << n[i] << endl;
        }
        int counter = 0;
        for (int i = 0; i < 1000; i++)
        {
            if (n[i] == 6)
            {
                counter++;
            }
        }
        cout << "The  number 6 appeared" << counter << "times" << endl;
        return 0;
    }
          ------------------------------------------------------------------------------------------------------------------------------------------------------
          
          #include <iostream>
#include <array>
#include <algorithm>
    using namespace std;
    int main(){

        int user[10];
        int i;
        int max = user[0];
        for (i = 0; i < 10; i++) {
            cin >> user[i];
            if (user[i] > max) {
                max = user[i];
            }
        }
        cout << "Largest number inserted" << max;
        return 0;
--------------------------------------------------------------------------------------------------------------------------------------------------------------
