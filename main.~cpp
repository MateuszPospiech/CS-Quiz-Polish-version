#include <iostream>
#include <windows.h> // By dzia³a³a komenda sleep
#include <cstdlib> //Do czyszczenia ekranu system("cls")


using namespace std;

string imie;
char x;
int i, punkty;
int pytanie=1;

int main()
{
    cout << "Czesc, jak sie nazywasz?" << endl;
    cin >> imie;

    menu_glowne:
    system("cls"); // Czyszczenie ekranu
    //********************MENU G£ÓWNE*****************************
    cout << imie << ", witaj w menu glownym, co chcesz zrobic?" << endl;

    cout << "1. Rozpocznij nowa gre" << endl;
    cout << "2. Wyjdz z gry" << endl;
    cin >> x;

    if (x=='1')
    {
        system("cls"); // Czyszczenie ekranu

        for (int i=5; i>=0; i--)
        {

            cout << "Witamy w grze Quiz CS:GO!" << endl;
            cout << "Gra rozpocznie sie za... " << i;
            Sleep(1000);
            system("cls");
        }
//*******************PYTANIA*****************************************
//11111111111111111111111111111111111111111111111111111111
            cout << "Pytanie 1"  << endl;
            cout << "W ktorym roku powstal Counter-Strike 1.6? " << endl;
            cout << "A. 1997 " << endl;
            cout << "B. 1998 " << endl;
            cout << "C. 1999 " << endl;
            cout << "D. 2000 " << endl;
            cin >> x;
            system("cls");

            if ((x=='C') || (x=='c'))
            {
                punkty=punkty+1;

                for (int i=4; i>=0; i--)
                {
                    cout << "Dobra odpowiedz, zdobywasz punkt !" << endl;
                    cout << "Nastepne pyttanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");

                }
            }
            else
            {
                for (int i=4; i>=0; i--)
                {
                    cout << "Zle! I Ty sie nazywasz graczem?" << endl;
                    cout << "Nastepne pyttanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");
                }

            }
//2222222222222222222222222222222222222222222222222222222222222222222222222222
            system("cls");
            cout << "Pytanie 2" << endl;
            cout << "Kogo ze 'zlotej piatki' zastapil Jaroslaw 'pasha' Jarzabkowski " << endl;
            cout << "A. Michu " << endl;
            cout << "B. Loord " << endl;
            cout << "C. LuQ " << endl;
            cout << "D. Kubben " << endl;
            cin >> x;
            system("cls");

            if ((x=='C') || (x=='c'))
            {
                punkty=punkty+1;

                for (int i=4; i>=0; i--)
                {
                    cout << "Dobra odpowiedz, zdobywasz punkt !" << endl;
                    cout << "Nastepne pyttanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");
                }
            }
            else
            {
                for (int i=4; i>=0; i--)
                {
                    cout << "Zle! I Ty sie nazywasz graczem?" << endl;
                    cout << "Nastepne pyttanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");
                }

            }
//33333333333333333333333333333333333333333333333333333333333333333333333333333333
            system("cls");
            cout << "Pytanie 3" << endl;
            cout << "W pojedynku przeciwko jakiej druzynie olofmaister z Fnatic dokona³ nie znanego wczesniej boosta na mapie de_overpass? " << endl;
            cout << "A. Titan " << endl;
            cout << "B. Na'Vi " << endl;
            cout << "C. Virtus.pro " << endl;
            cout << "D. LDLC " << endl;
            cin >> x;
            system("cls");

                if ((x=='D') || (x=='d'))
            {
                punkty=punkty+1;

                for (int i=4; i>=0; i--)
                {
                    cout << "Dobra odpowiedz, zdobywasz punkt !" << endl;
                    cout << "Nastepne pytanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");
                }
            }
            else
            {
                for (int i=4; i>=0; i--)
                {
                    cout << "Zle! I Ty sie nazywasz graczem?" << endl;
                    cout << "Nastepne pytanie pojawi sie za.. " << i << endl;
                    Sleep(1000);
                    system("cls");

                }
            }
//**KONIEC QUIZU****KONIEC QUIZU****KONIEC QUIZU****KONIEC QUIZU****KONIEC QUIZU**
            cout << imie <<", dziekujemy za udzial w grze." << endl;
            cout << "Twoj wynik to " << punkty << "/3" << endl << endl;
            koniec_quiz:
            cout << "Nacisnij 1. by wrocic do menu glownego" << endl;
            cout << "Nacisnij 2. by wyjsc z gry" << endl;
            cin >> x;

            if (x=='1')
            {
                goto menu_glowne;
            }
            else if (x=='2')
            {
                goto koniec;
            }
            else
            {
                system("cls");
                cout << "Naucz sie czytac.." << endl;
                goto koniec_quiz;
            }
    }

    else if (x=='2')
    {
        koniec:
        system("cls"); // Czyszczenie ekranu
        cout << "Do zobaczenia " << imie << "!" << endl;
    }

    else
    {
        system("cls"); // Czyszczenie ekranu
        cout << "yyy?!" << endl;
    }



    return 0;
}
