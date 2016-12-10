# treinoc++
exercicio simples

1)Solicitar duas notas para o cálculo da média , mostrar a média e se a média for Maior ou igual a 6, mostrar “Aprovado”, caso contrário mostrar “Reprovado”.

#include <iostream>

using namespace std;

int main()
{
    float x,y;
    x = 0;
    y = 0;

    cout<<" \nMedia de notas\n";
    cout<<"\nInsira a primeira nota\n";
    cin >> x;
    cout << "\nInsira a segunda nota\n";
    cin >> y;
    x = (x+y)/2;
    if(x>=6)
        {
            cout << "Aprovado: \n"<< x<<endl;
            cout << "\n\bPARABENS\n\b";
        }
    else
    {
        cout << "Reprovado: \n"<< x;
        cout << "\nESTUDE MAIS NA PROXIMA\n";
    }

    return 0;
}
