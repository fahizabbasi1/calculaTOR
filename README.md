Task NO 1
#include <iostream>
using namespace std;
int main() {
    int lines = 6;
    for (int i = 1; i <= lines; ++i) {
     
        for (int j = 1; j <= i; ++j) {
            std::cout << "*";
        }
       
        std::cout << std::endl;
    }

    return 0;
}
    Task No 2
#include <iostream>
using namespace std;
int main() {
    int rows = 5;
    for (int i = 1; i <= rows; i++) {
        for (int j = 1; j <= i; j++) {
            std::cout << j ;
        }

        std::cout << std::endl;
    }

    return 0;
}
         Task No 3
#include <iostream>
using namespace std;
int main() {
    int rows;
    std::cout << "Enter the number of rows: ";
    std::cin >> rows;
    for (int i = 1; i <= rows; ++i) {
        for (int j = 1; j <= i; ++j) {
            std::cout << i << " ";
        }
        std::cout << std::endl;
    }

    return 0;
}
   Task NO 4
#include <iostream>
using namespace std;
int main() {
    int weeks;
    std::cout << "Enter the number of weeks: ";
    std::cin >> weeks;
    const std::string days[] = {"Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"};
    for (int i = 1; i <= weeks; ++i) {
        std::cout << "Week " << i << ":" << std::endl;
        for (int j = 0; j < 7; ++j) {
            std::cout << days[j] << std::endl;
        }
        std::cout << std::endl;
    }

    return 0;
}
     Task NO 5
#include <iostream>

int main() {
    const int rows = 5; 
    const int seats = 10;
    
    for (int i = 1; i <= rows; ++i) {
        std::cout << "Row " << i << ": ";

       
        for (int j = 1; j <= seats; ++j) {
           
            std::cout << (i - 1) * seats + j << " ";
        }

        
        std::cout << std::endl;
    }

    return 0;
}
