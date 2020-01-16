#include <iostream>
#include <stdlib.h>

int main()
{
    int computer = rand() % 3 + 1;
    int user = 0;
    
    std::string roc = "1) Rock\n";
    std::string pap = "2) Paper\n";
    std::string sci = "3) Scissors\n";

    std::cout << "Rock Paper Scissors!\n";
    std::cout << "It's you againts the computer!\n";
    std::cout << "Choose: \n1) Rock\n2) Paper\n3)Scissors\n";
    
    std::cin >> user;

    std::cout << "\nYou choose: ";

    switch(user)
    {
        case 1 :
            std::cout << roc;
            break;
        case 2 :
            std::cout << pap;
            break;
        case 3 :
            std::cout << sci;
            break;
        default :
            std::cout << "Invaild Option\n";
    }

    std::cout << "Computer choose: ";

    switch(computer)
    {
        case 1 :
            std::cout << roc;
            break;
        case 2 :
            std::cout << pap;
            break;
        case 3 :
            std::cout << sci;
            break;
        default :
            std::cout << "Invalid Option\n";
    }
    
    if(user==computer)
        {
        std::cout << "Draw!\n";
        }
        else if(user == 1 && computer == 3)
        {
        std::cout << "You Win!\n";
        }
        else if(user == 3 && computer == 2)
        {
        std::cout << "You Lose!\n";
        }
        else
        std::cout << "Computer Wins!\n";
        }
