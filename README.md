# egzamin

### W każdym zadaniu można zaznaczyć jedną lub więcej odpowiedzi

[1] Które typy danych należą do podstawowych:
 * x <b>int
 * x boolean //bool a boolean to, to samo ale xD
 * x double
 * x char</b>
 * var

[2] Jaka jest początkowa wartość atrybutu klasy typu int (bez jawnej inicjalizacji)
* atrybut klasy musi zostac jawnie zainicjonowany przed użyciem
* x <b>przypadkowa</b>
* 0

[3] Który fragment programu powinien znaleźć się w bloku <b>try</b>?
* wkaźnik
* x <b>referencja</b>
* x <b>dynamiczna alokacja pamieci</b>
* statyczna alokacja pamięci

[4] Publiczne składowe klasy mogą być używane przez:
 * x <b>a) metody tej klasy</b>
 * x <b>b) funkcje zaprzyjaźnione</b>
 * x <b>c) dowolne funkcje zewnętrzne</b>
 * x <b>d) metody klas pochodnych</b>
 * x <b>e) metody dowolnej klasy </b>

[5] Na ilu bajtach przechowywany jest typ int w C++
* 4 
* 1
* 2
* 8
* x <b>zależy do architektury</b>

[6] Operator alternatywy logicznej (OR) ma postać
* !!
* x <b>||</b> //to
* &&
* !
* &
* x <b>|</b> //to

[7] Ile parametrów powinien operator "/" przeładowany jako metoda składowa klasy
 * x <b>a) 2</b>
 * b) 1
 * c) 0
 * d) 3

[8] Wskaż poprawne definicje funkcji w C++
* int method(int a, int b) {} //wydaje mi sie ze brakuje return
* void method(int a; int b) {}
* x <b>void method() {}
* x void method(int a = 5) {}
* x void method(void) {}</b>
* method() {}
* void method {}

[9] Jakie operacje na wskaźnikach są legalne w C++:
 * a) dodanie do wskaźnika innego wskaźnika
 * b) pomnożenie dwóch wskaźników
 * x <b>c) odjęcie od wskaźnika wartości całkowitej
 * x d) odjęcie od wskaźnika innego wskaźnika
 * x e) porównanie dwóch wskaźników
 * x f) dodanie do wskaźnika wartości całkowitej</b>

[10] Jaka jest początkowa wartość zmiennej lokalnej typu int(bez jawnej inicjalizacji):
 * a) zmienna lokalna musi zostać jawnie zainicjalizowana przed użyciem //i to?
 * x <b>b) przypadkowa</b>
 * c) 0 

[11] Wskaż poprawne deklaracje funkcji main:
 * a) int main(string argv[]);
 * b) int main(char*argv[]);
 * c) int main(int argc,char argv[]);
 * x <b>d) int main(int argc,char*argv[]);
 * x e) int main();</b>
 * f) int main(char*argv[],int argc); 

[12] Przeciązony operator << służący do wypisywania na ekran obiektu klasy K może być zdefiniowany:
 * x <b>a) jako zaprzyjaźniona funkcja składowa klasy B</b>
 * x <b>b) jako zaprzyjaźniona funkcja globalna</b>
 * c) jako funkcja składowa klasy K
 * d) jako funkcja globalna 

[13] Wskaż błędne identyfikatory w C++
 * x <b>a) 1alpha</b>
 * b) _abcd
 * x <b>c) xy+abc
 * x d) account-num</b>
 * e) very_long_name 

[14] Wskaż poprawne definicje tablic
 * a) int arr[4]=new int[4]
 * x <b>b) int*arr=new int[4]</b>
 * c) int arr=new int[4]
 * x <b>d) int arr[4]</b>

[15] Wskaż polecenie pozwalające skompilować kod źródłowy C++ w pliku program.cpp
 * g++ -o program.cpp program
 * x <b>g++ -o program program.cpp</b>
 * x <b>g++ program.cpp</b>
 * gcc program.cpp

[16] Co jest używane przy zmianie kod źródłowego w C++ na kod wykonywalny
 * x <b>preprocesor
 * x linker
 * x kompilator</b>
 * interpreter

[17] Jaki jest wynik wyrażenia 7/9*9
 * 0.08642
 * 1
 * x <b>0</b> //to

[18] Wybierz poprawną odpowiedź, gdy: int tab[2][2] = {4,5,6,7}
 * tab[2][2] //zwroci 7
 * x <b>*(tab[0]+2) //zworci 6</b>
 * tab[0] //zwroci 4
 * x <b>*tab[0] //zwroci 4</b>

[19] Konstruktor kopiujacy jest automatycznie wywoływany przy:
 * x <b>inicjalizacji obiektu innym obiektem tego samego typu</b>
 * przekazywanie obiektu do funkcji przez referencje
 * x <b>przekazywanie obiektu do funkcji przez wartość</b>

[20] Która instrukcja jest używana do wyłapywania wszystkich typów wyjątków?
 * catch(Test t)
 * catch(Test)
 * catch()
 * x <b>catch(...)</b>

[21] Aby móc skorzystać z obiektu cout należy dołączyć plik nagłówkowy
 * cstdlib
 * x <b>iostream</b>
 * stdio.h
 * math.c

[22] Chronione składowe klasy mogą być używane przez 
 * metody dowolnej klasy
 * dowolne funkcje zewnetrzne
 * x <b>metody klas pochodnych
 * x metody tej klasy
 * x funkcje zaprzyjaźnione</b>

[23] Wskaż poprawne nagłówki konstruktora kopiujacego dla klasy Test
 * Test()
 * void Test(Test& t)
 * x <b>Test(const Test& t)
 * x Test(Test& t)</b>
 * void Test(const Test& t)
 * void Test(Test t)
 * Test(Test t)

[24] Do zwalniania zaalokowanej pamięci służy
 * destroy
 * x <b>delete</b>
 * return
 * release

[25] Wskaż poprawny sposób (lub sposoby) stworzenia nowego obiektu typu Punkt z użyciem konstruktora bezparametrowego
 * Punkt p();
 * Punkt p = new Punkt;
 * x <b>Punkt p;
 * x Punkt* p = new Punkt();
 * x Punkt* p = new Punkt;</b>
 * Punkt p = new Punkt()

[26] Lista inicjalizacji konstruktora rozpoczyna się znakiem
 * ::
 * ;
 * =
 * x <b>:</b>

[27] Można zdefiniować w klasie dwie metody o tej samej nazwie, jeśli
 * różnią się modyfikatorem dostępu
 * x <b>różnią się liczbą argumentów
 * x różnią się typami argumentów</b>
 * różnią się typem zwracaniem

[28] Wskaż poprawne konstrukcje pętli w C++
 * repeat a++; while(a != 0)
 * while (a != 0) do a++;
 * for (i = 0, i < 10, i++) cout << i;
 * x <b>do a++; while(a != 0);</b>
 * for (i = 0; i < 10; i++) cout << i; //wydaje mi sie ze brakuje int przed i
 * x <b>while(a != 0) a++;</b>

[29] Wskaż prawdziwe stwierdzenie
 * Klasa może dziedziczyć co najwyżej z jednej klasy
 * x <b>Klasa może dziedziczyć z jednej lub więcej klas</b>
 * Klasa może zawierać tylko jeden konsturktor
 * x <b>Klasa może zawierać tylko jeden destruktor</b>

[30] Relacje: klasa B dziedziczy z klasy A możemy zapisać jako: 
 * class B extends A
 * class B super A
 * x <b>class B : A
 * x class B : public A</b>

[31] Funkcję o deklaracji <b>double x (int &a, int b)</b> można wywoływać następujący sposób:
 * cout << x(4,5);
 * x <b>int a = 5; cout << x(a,a);</b>
 * x <b>int a = 5; cout << x(a,5);</b>
 * x(5,6);

[32] Prywatne składowe klasy mogą być używane przez
 * dowolną funkcje zewnetrzna
 * x <b>funkcje zaprzyjaźnione</b>
 * x <b>metody tej klasy</b>
 * metody dowolnej klasy
 * metody klas pochodnich

[33] Jaki znak oznacza koniec napisu
 * '0'
 * x <b>'\0'</b>
 * '\n'
 * '.'

