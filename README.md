# egzamin

### W każdym zadaniu można zaznaczyć jedną lub więcej odpowiedzi

[1] Które typy danych należą do podstawowych:
 * <b>int
 * boolean //bool a boolean to, to samo ale xD
 * double
 * char</b>
 * var

[2] Jaka jest początkowa wartość atrybutu klasy typu int (bez jawnej inicjalizacji)
* atrybut klasy musi zostac jawnie zainicjonowany przed użyciem
* <b>przypadkowa</b>
* 0

[3] Który fragment programu powinien znaleźć się w bloku <b>try</b>?
* wkaźnik
* <b>referencja</b>
* <b>dynamiczna alokacja pamieci</b>
* statyczna alokacja pamięci

[4] Publiczne składowe klasy mogą być używane przez:
 * <b>a) metody tej klasy</b>
 * <b>b) funkcje zaprzyjaźnione</b>
 * <b>c) dowolne funkcje zewnętrzne</b>
 * <b>d) metody klas pochodnych</b>
 * <b>e) metody dowolnej klasy </b>

[5] Na ilu bajtach przechowywany jest typ int w C++
* 4 
* 1
* 2
* 8
* <b>zależy do architektury</b>

[6] Operator alternatywy logicznej (OR) ma postać
* !!
* <b>||</b> //to
* &&
* !
* &
* <b>|</b> //to

[7] Ile parametrów powinien operator "/" przeładowany jako metoda składowa klasy
 * <b>a) 2</b>
 * b) 1
 * c) 0
 * d) 3

[8] Wskaż poprawne definicje funkcji w C++
* int method(int a, int b) {}
* void method(int a; int b) {}
* <b>void method() {}
* void method(int a = 5) {}
* void method(void) {}</b>
* method() {}
* void method {}

[9] Jakie operacje na wskaźnikach są legalne w C++:
 * a) dodanie do wskaźnika innego wskaźnika
 * b) pomnożenie dwóch wskaźników
 * <b>c) odjęcie od wskaźnika wartości całkowitej
 * d) odjęcie od wskaźnika innego wskaźnika
 * e) porównanie dwóch wskaźników
 * f) dodanie do wskaźnika wartości całkowitej</b>

[10] Jaka jest początkowa wartość zmiennej lokalnej typu int(bez jawnej inicjalizacji):
 * a) zmienna lokalna musi zostać jawnie zainicjalizowana przed użyciem //i to?
 * <b>b) przypadkowa</b>
 * c) 0 

[11] Wskaż poprawne deklaracje funkcji main:
 * a) int main(string argv[]);
 * b) int main(char*argv[]);
 * c) int main(int argc,char argv[]);
 * <b>d) int main(int argc,char*argv[]);
 * e) int main();</b>
 * f) int main(char*argv[],int argc); 

[12] Przeciązony operator << służący do wypisywania na ekran obiektu klasy K może być zdefiniowany:
 * <b>a) Jako zaprzyjaźniona funkcja składowa klasy B</b>
 * b) jako zaprzyjaźniona funkcja globalna
 * <b>c) jako funkcja składowa klasy K</b>
 * d) jako funkcja globalna 

[13] Wskaż błędne identyfikatory w C++
 * <b>a) 1alpha</b>
 * b) _abcd
 * <b>c) xy+abc
 * d) account-num</b>
 * e) very_long_name 

[14] Wskaż poprawne definicje tablic
 * a) int arr[4]=new int[4]
 * <b>b) int*arr=new int[4]</b>
 * c) int arr=new int[4]
 * <b>d) int arr[4]</b>

[15] Wskaż polecenie pozwalające skompilować kod źródłowy C++ w pliku program.cpp
 * g++ -o program.cpp program
 * <b>g++ -o program program.cpp</b>
 * <b>g++ program.cpp</b>
 * gcc program.cpp

[16] Co jest używane przy zmianie kod źródłowego w C++ na kod wykonywalny
 * <b>preprocesor
 * linker
 * kompilator</b>
 * interpreter

[17] Jaki jest wynik wyrażenia 7/9*9
 * 0.08642
 * 1
 * <b>0</b> //to

[18] Wybierz poprawną odpowiedź, gdy: int tab[2][2] = {4,5,6,7}
 * tab[2][2] //zwroci 7
 * <b>*(tab[0]+2) //zworci 6</b>
 * tab[0] //zwroci 4
 * <b>*tab[0] //zwroci 4</b>

[19] Konstruktor kopiujacy jest automatycznie wywoływany przy:
 * <b>inicjalizacji obiektu innym obiektem tego samego typu</b>
 * przekazywanie obiektu do funkcji przez referencje
 * <b>przekazywanie obiektu do funkcji przez wartość</b>

[20] Która instrukcja jest używana do wyłapywania wszystkich typów wyjątków?
 * catch(Test t)
 * catch(Test)
 * catch()
 * <b>catch(...)</b>

[21] Aby móc skorzystać z obiektu cout należy dołączyć plik nagłówkowy
 * cstdlib
 * <b>iostream</b>
 * stdio.h
 * math.c

[22] Chronione składowe klasy mogą być używane przez 
 * metody dowolnej klasy
 * dowolne funkcje zewnetrzne
 * <b>metody klas pochodnych
 * metody tej klasy
 * funkcje zaprzyjaźnione</b>

[23] Wskaż poprawne nagłówki konstruktora kopiujacego dla klasy Test
 * Test()
 * void Test(Test& t)
 * <b>Test(const Test& t)
 * Test(Test& t)</b>
 * void Test(const Test& t)
 * void Test(Test t)
 * Test(Test t)

[24] Do zwalniania zaalokowanej pamięci służy
 * destroy
 * <b>delete</b>
 * return
 * release

[25] Wskaż poprawny sposób (lub sposoby) stworzenia nowego obiektu typu Punkt z użyciem konstruktora bezparametrowego
 * Punkt p();
 * Punkt p = new Punkt;
 * <b>Punkt p;
 * Punkt* p = new Punkt();
 * Punkt* p = new Punkt;</b>
 * Punkt p = new Punkt()

[26] Lista inicjalizacji konstruktora rozpoczyna się znakiem
 * ::
 * ;
 * =
 * <b>:</b>

[27] Można zdefiniować w klasie dwie metody o tej samej nazwie, jeśli
 * różnią się modyfikatorem dostępu
 * <b>różnią się liczbą argumentów
 * różnią się typami argumentów</b>
 * różnią się typem zwracaniem

[28] Wskaż poprawne konstrukcje pętli w C++
 * repeat a++; while(a != 0)
 * while (a != 0) do a++;
 * for (i = 0, i < 10, i++) cout << i;
 * <b>do a++; while(a != 0);</b>
 * for (i = 0; i < 10; i++) cout << i; 
 * <b>while(a != 0) a++;</b>

[29] Wskaż prawdziwe stwierdzenie
 * Klasa może dziedziczyć co najwyżej z jednej klasy
 * <b>Klasa może dziedziczyć z jednej lub więcej klas</b>
 * Klasa może zawierać tylko jeden konsturktor
 * <b>Klasa może zawierać tylko jeden destruktor</b>

[30] Relacje: klasa B dziedziczy z klasy A możemy zapisać jako: 
 * class B extends A
 * class B super A
 * <b>class B : A
 * class B : public A</b>

[31] Funkcję o deklaracji <b>double x (int &a, int b)</b> można wywoływać następujący sposób:
 * cout << x(4,5);
 * <b>int a = 5; cout << x(a,a);</b>
 * <b>int a = 5; cout << x(a,5);</b>
 * x(5,6);

[32] Prywatne składowe klasy mogą być używane przez
 * dowolną funkcje zewnetrzna
 * <b>funkcje zaprzyjaźnione</b>
 * <b>metody tej klasy</b>
 * metody dowolnej klasy
 * metody klas pochodnich

[33] Jaki znak oznacza koniec napisu
 * '0'
 * <b>'\0'</b>
 * '\n'
 * '.'

