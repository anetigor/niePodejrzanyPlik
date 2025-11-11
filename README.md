#include <stdio.h>
#include <stdlib.h>
#include <time.h>

/* Zad 4
double obliczOdchylenieStandardowe(int tab[], int n, double srednia) {
    double suma_kwadratow = 0.0;
    for (int i = 0; i < n; i++) {
        suma_kwadratow += pow(tab[i] - srednia, 2);
    }
    return sqrt(suma_kwadratow / n);
}


void przetworzTablice(int n) {
    int tab[n];
    int suma = 0;

    srand(time(NULL));

    printf("Zawartość tablicy:\n");
    for (int i = 0; i < n; i++) {
        tab[i] = rand() % 201 - 100; 
        printf("%4d ", tab[i]);
        suma += tab[i];
    }

    double srednia = (double)suma / n;
    double odchylenie = obliczOdchylenieStandardowe(tab, n, srednia);

    printf("\nŚrednia z liczb w tablicy: %.2f", srednia);
    printf("\nOdchylenie standardowe: %.2f\n", odchylenie);
}
*/
/* zad 3
void przetworzTablice(int n) {
    int tab[n];
    int suma = 0;

    srand(time(NULL)); 

    printf("Zawartość tablicy:\n");

    for (int i = 0; i < n; i++) {
        tab[i] = rand() % 201 - 100; 
        printf("%4d ", tab[i]);
        suma += tab[i];
    
    }

    double srednia = (double)suma / n;
    printf("\nŚrednia z liczb w tablicy: %.2f\n", srednia);
}
*/

/* Zad 2
void wyswietlEnum() {
    enum Kolory {
        CZERWONY,        
        ZIELONY,         
        NIEBIESKI,      
        BIALY = 2,      
        SZARY = 2,       
        FIOLETOWY = 10,  
        POMARANCZOWY = 15,
        ROZOWY = 20
    };

    printf("CZERWONY = %d\n", CZERWONY);
    printf("ZIELONY = %d\n", ZIELONY);
    printf("NIEBIESKI = %d\n", NIEBIESKI);
    printf("BIALY = %d\n", BIALY);
    printf("SZARY = %d\n", SZARY);
    printf("FIOLETOWY = %d\n", FIOLETOWY);
    printf("POMARANCZOWY = %d\n", POMARANCZOWY);
    printf("ROZOWY = %d\n", ROZOWY);
}

*/

int main() {
    wyswietlEnum();
     przetworzTablice(30); 
    return 0;
}
