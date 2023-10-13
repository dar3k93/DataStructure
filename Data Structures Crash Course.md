- [Complexity Analysis](#Complexity-Analysis)
- [Memory](#Memory)
- [Big O Notation](#Big-O-Notation)
- [Logarithm](#Logarithm)
- [Arrays](#Arrays) - TODO
- [Linked Lists](#Linked-Lists) - TODO
- [Hash Tables](#Hash-Tables) - TODO
- [Stacks and Queues](#Stacks-and-Queues) - TODO
- [Strings](#Strings) - TODO
- [Graphs](#Graphs) - TODO
- [Trees](#Trees) - TODO

____________________________________________________________________________________________________________________________________________________________________________________________________

## Complexity Analysis

```
Analiza złożoności (ang. Complexity Analysis) w kontekście programowania to proces oceny i pomiaru złożoności algorytmów lub fragmentów kodu komputerowego. Jest to istotny aspekt w tworzeniu oprogramowania, ponieważ pomaga programistom zrozumieć, jakie zasoby (takie jak czas i pamięć) są potrzebne do wykonywania danego zadania lub algorytmu. Analiza złożoności ma na celu określenie, jak szybko lub efektywnie program będzie działać w zależności od rozmiaru danych wejściowych.

Istnieją dwie główne kategorie analizy złożoności:

1. Złożoność czasowa: Określa, ile czasu potrzebuje program lub algorytm do zakończenia działania w zależności od rozmiaru danych wejściowych. Pomaga to programistom ocenić, czy program działa wystarczająco szybko dla danych o różnych rozmiarach i czy potrzebne są optymalizacje. Często oznacza się to jako O-notation (np. O(n), O(n log n), O(1)), co pozwala na porównywanie efektywności różnych algorytmów.

2. Złożoność przestrzenna: Określa, ile pamięci jest potrzebnych do przechowywania danych lub wyników w trakcie działania programu. Analiza złożoności przestrzennej jest istotna, zwłaszcza na urządzeniach z ograniczonymi zasobami pamięci. Oznacza się to jako O-notation podobnie jak w przypadku złożoności czasowej.

Analiza złożoności pomaga programistom dokonywać wyborów między różnymi algorytmami i strukturami danych w zależności od potrzeb projektu. Warto dążyć do algorytmów o jak najniższej złożoności czasowej i przestrzennej, ale czasami kompromisy muszą być dokonane, ponieważ nie zawsze jest możliwe osiągnięcie optymalnych wyników w obu kategoriach jednocześnie.

Przykłady analizy złożoności to:

- Obliczanie złożoności czasowej dla sortowania danych (np. algorytm sortowania bąbelkowego, quicksort, mergesort).
- Ocena złożoności przestrzennej dla struktur danych (np. tablice, listy, drzewa).
- Analiza złożoności algorytmów wyszukiwania (np. wyszukiwanie liniowe, wyszukiwanie binarne).
- Ocena złożoności algorytmów grafowych (np. algorytmy przeszukiwania grafów).

Analiza złożoności jest kluczowym narzędziem w projektowaniu wydajnych i skalowalnych programów oraz umożliwia programistom podejmowanie informowanych decyzji dotyczących optymalizacji kodu.
```
____________________________________________________________________________________________________________________________________________________________________________________________________

## Memory

#### Bit
Short for binary digit, a bit is a fundamental unit of information in Computer Science that represents a state with one of two values, typically 0 and 1.
Any data stored in a computer is, at the most basic level, represented in bits

#### Byte
A group of eight bits. For example 01101000 is a byte. A single byte can represent up to 256 data vales (2 to 8)
Since a binary number is a number expressed with only two symbols, like 0 and 1,a byte can effectively represent all of the numbers between 0 and 255, inclusive, in binary format.

#### Memory
Broadly speaking memory is the foundational layer of computing where all data is stored. In the contex of coding interviews, it is important to note the following points:
- Data stored in memory is stored in bytes and, by extension, bits
- Bytes in memory can 'point' to other bytes in memory, so as to store references to other data.
- The amount of memory that a machine has is bounded, making it valuable to limit how much memory an algorithm takes up
- Accessing a byte of a fixed number of bytes (like 4 bytes or 8 bytes in the case of 32-bit and 64-bit integers) is an elementary operation, which can be looselt treated as a singlee unit of operational work

#### Czat GPT
```
Pamięć komputerowa, zwana również pamięcią systemową lub pamięcią operacyjną (RAM - Random Access Memory), to istotny element komputera, który służy do przechowywania danych i programów, nad którymi obecnie pracuje. Pamięć ta jest odczytywalna i zapisywalna, co oznacza, że można w niej przechowywać i modyfikować dane w czasie rzeczywistym. Oto główne cechy i funkcje pamięci komputerowej:

Szybki dostęp: Pamięć RAM zapewnia bardzo szybki dostęp do danych w porównaniu do innych rodzajów pamięci, takich jak dyski twarde. Jest to kluczowe dla wydajności komputera, ponieważ umożliwia szybkie odczytywanie i zapisywanie danych przez procesor.

Ultraniski czas dostępu: Czas dostępu do pamięci RAM jest bardzo krótki, mierzony w nanosekundach, co oznacza, że komputer może natychmiastowo uzyskać dostęp do danych przechowywanych w pamięci RAM.

Przechowywanie danych programów: Aktualnie działające programy i system operacyjny są przechowywane w pamięci RAM. To pozwala na szybkie wykonywanie operacji i umożliwia użytkownikom interakcję z komputerem w czasie rzeczywistym.

Czasowa trwałość: Pamięć RAM jest ulotna, co oznacza, że dane w niej przechowywane są tracone po wyłączeniu komputera lub po zresetowaniu. Dlatego ważne jest regularne zapisywanie danych na trwałym nośniku, takim jak dysk twardy.

Rozmiar i pojemność: Komputery posiadają różne ilości pamięci RAM, zwykle w zakresie od kilku gigabajtów do kilku terabajtów. Rozmiar pamięci RAM ma wpływ na zdolność komputera do obsługi większej liczby programów i większych zestawów danych.

Wirtualna pamięć: Systemy operacyjne mogą tworzyć wirtualną pamięć, korzystając z kombinacji pamięci RAM i dysku twardego. To pozwala na obsługę większych programów i danych, chociaż dostęp do wirtualnej pamięci jest znacznie wolniejszy niż do pamięci RAM.

Typy pamięci RAM: Istnieją różne rodzaje pamięci RAM, w tym DDR (Double Data Rate), SDRAM (Synchronous Dynamic Random Access Memory) i wiele innych. Każdy z tych typów ma swoje własne cechy i prędkości.

Pamięć RAM jest jednym z kluczowych czynników wpływających na ogólną wydajność komputera. Im większa i szybsza pamięć RAM, tym komputer jest w stanie obsłużyć większą ilość zadań i działać z większą wydajnością. Jednakże sama pamięć RAM nie przechowuje danych po wyłączeniu zasilania, dlatego ważne jest regularne zapisywanie danych na dysku twardym lub innych trwałych nośnikach
```
___________________________________________________________________________________________________________________________________________________________________________________________________

## Big O Notation

The notation used to describe the time complexity and space compexity of algorithms.
Variables used in Big O notation denote the sizes of inputs to algorithms. For example, O(n) might be the time complexity of an algorithm that traverses through an array of length n; similarly, O(n + m) might be the time complexity of an algorithm that traverses through an array of length n and through a string of length m
The following are examples of common complexities and their Big O notations, ordered from fastest to slowest:
+ Constant: O(1)
+ Logarithmic: O(log(x))
+ Linear: O(n)
+ Log-linear: O(nlog(n))
+ Quadratic: O(n^2)
+ Cubic: O(n^3)
+ Exponential: O(2^n)
+ Factorial: O(n!)

Note that in the context of coding interviews, Big O notation is usually understood to describe the worst-case complexity of an algorithm, even though the worst-case complexity might differ from the average-case complexity. For example, some sorting algorithms have different time complexities depending on the layout of elements in their input array. In rare cases, their
time complexity will be much worse than in more common cases. Similarly, an algorithm that takes in a string and performs special operations on uppercase characters might have a different time complexity when run on an input string of only uppercase characters vs. on an input string with just a few uppercase characters.
Thus, when describing the time complexity of an algorithm, it can sometimes be helpful to specify whether the time complexity refers to the average case or to the worst case (e.g., "this algorithm runs in O(nlog(n)) time on average and in O(n^2) time in the worse case").

**Chat GPT**
```
Notacja Big O (Big O Notation) jest ważnym pojęciem w kontekście rozmów kwalifikacyjnych na stanowiska programistyczne i analizy algorytmów. Jest to matematyczny sposób określania efektywności czasowej (czas działania) lub przestrzennej (użycie pamięci) algorytmów. Oto kilka kluczowych aspektów notacji Big O w kontekście kodów źródłowych i rozmów kwalifikacyjnych:

1. **Co to jest Notacja Big O?**
   - Notacja Big O to sposób opisywania tempa wzrostu czasu lub pamięci potrzebnego do wykonania algorytmu w zależności od rozmiaru danych wejściowych. Ostateczny cel to zrozumienie, jak algorytm skaluje się w miarę wzrostu danych.

2. **Ograniczenia Górne:**
   - Notacja Big O określa górne ograniczenie na czas lub pamięć, co oznacza, że podaje, jak algorytm będzie działać w najgorszym przypadku. Jest to przydatne do analizy wydajności algorytmów, gdy dane wejściowe stają się bardzo duże.

3. **Przykłady Notacji Big O:**
   - Przykłady często spotykanych notacji Big O to:
     - O(1): Stała złożoność czasowa lub pamięciowa, co oznacza, że czas lub pamięć jest niezależny od rozmiaru danych wejściowych.
     - O(n): Liniowa złożoność, gdzie czas lub pamięć rośnie wprost proporcjonalnie do rozmiaru danych wejściowych.
     - O(log n): Logarytmiczna złożoność, charakteryzująca algorytmy, które są wydajne nawet dla dużych zestawów danych.
     - O(n^2): Kwadratowa złożoność, która rośnie kwadratowo w stosunku do rozmiaru danych i jest zazwyczaj bardziej kosztowna w przypadku dużych zestawów danych.

4. **Użycie Notacji Big O w Rozmowach Kwalifikacyjnych:**
   - W rozmowach kwalifikacyjnych notacja Big O jest często używana do oceny zdolności kandydata do analizy i optymalizacji algorytmów.
   - Kandydat może zostać poproszony o oszacowanie notacji Big O dla danego algorytmu lub napisanie bardziej efektywnego algorytmu do rozwiązania danego problemu.

5. **Znaczenie Optymalizacji:**
   - Zrozumienie notacji Big O jest kluczowe dla projektantów i programistów, ponieważ pozwala na tworzenie bardziej efektywnych i wydajnych programów oraz unikanie algorytmów o dużym czasie wykonywania lub zużyciu pamięci.

W skrócie, notacja Big O jest narzędziem służącym do analizy i porównywania wydajności algorytmów w zależności od rozmiaru danych wejściowych. Jest ważnym zagadnieniem w rozmowach kwalifikacyjnych i pracy programisty, ponieważ pozwala na tworzenie bardziej wydajnych i skalowalnych rozwiązań.
```
____________________________________________________________________________________________________________________________________________________________________________________________________

## Logarithm
A mathematical concept that is widely used in Computer Science and that is definced by the following equation:

![image](https://github.com/dar3k93/DataStructure/assets/49185097/f68c24d0-8416-48d9-ac78-2370af157679)

In the context of coding interviews, the logarithm is used to describe the compelxity analysis of algorithms,a nd its usage always implies a logarithm of base 2. In orther words, the logarithm used in the context of coding interviews is defined by the following equation: 

![image](https://github.com/dar3k93/DataStructure/assets/49185097/5972efdc-a8e0-4c14-a505-f622f37ad75e)

In plain English, if an algorithm has a logarithmic time complexity (O(log(n)), where n is te size of the input)., then whenever the algorithm's input doubles in size (I.e., whenever n doubles), the number of operations ned to complete the algorithm only increases by one unit. Conversely, an algorithm with a linear time complexity would see its number of operations double if its input size doubles.

As an example, a linear-time-complexity algorithm ith an input of size 1,000 might take roughly 1.000 operations to complete, whereas a logarithmi-time-compexity algorithm with the same input would take roughly 10 operations to complete, since 2^10 ~= 1,0000.

**Chat GPT**
```
W kontekście struktur danych i algorytmów, logarytm często odnosi się do operacji logarytmicznych, które są wykorzystywane do analizy złożoności obliczeniowej i efektywności algorytmów. Logarytmy są szczególnie istotne w analizie czasu działania i wydajności algorytmów.

Oto kilka ważnych koncepcji związanych z logarytmami w kontekście struktur danych i algorytmów:

1. **Logarytm czasu działania (czasu trwania)**: Logarytm jest używany do mierzenia i analizy złożoności czasowej algorytmów. Algorytmy o czasie trwania logarytmicznym są uważane za bardzo wydajne. Oznacza to, że czas potrzebny na przetworzenie danych wzrasta w sposób logarytmiczny wraz ze wzrostem ilości danych. Przykładem może być algorytm wyszukiwania w posortowanej liście, taki jak wyszukiwanie binarne, który działa w czasie logarytmicznym.

2. **Drzewa i grafy**: Logarytmy są często używane do analizy złożoności struktur danych, takich jak drzewa i grafy. Na przykład, wysokość drzewa binarnego jest związana z logarytmem liczby wierzchołków w drzewie. Logarytmiczna złożoność występuje również w algorytmach przeszukiwania drzew, takich jak AVL drzewa czy drzewa czerwono-czarne.

3. **Równoważenie struktur danych**: Logarytmy są kluczowe w zrozumieniu równoważenia struktur danych, takich jak drzewa AVL i drzewa czerwono-czarne. Dzięki właściwemu równoważeniu, operacje na tych strukturach danych są wykonywane w czasie logarytmicznym.

4. **Algorytmy dziel i zwyciężaj**: Algorytmy, które wykorzystują technikę dziel i zwyciężaj, często wykazują logarytmiczną złożoność czasową. W tego typu algorytmach dane są podzielone na mniejsze części, co pozwala na efektywne przeszukiwanie i rozwiązywanie problemu.

W skrócie, logarytmy są ważnym narzędziem do analizy i porównywania wydajności różnych algorytmów i struktur danych w kontekście obliczeń i złożoności czasowej. Oceniają, jak dany algorytm lub struktura danych skaluje się w zależności od ilości danych lub innych czynników. Algorytmy o logarytmicznej złożoności czasowej są szczególnie pożądane ze względu na ich efektywność i wydajność w analizie i przetwarzaniu dużych zbiorów danych.
```

___________________________________________________________________________________________________________________________________________________________________________________________________

## Arrays
A linear collection of data values tht are accessible at numbered indices, starting at index 0.
The following are an array's standard operations and their corresponding time complexities:

![image](https://github.com/dar3k93/DataStructure/assets/49185097/b3557ee4-a561-4d40-8173-f775b78f70b1)

A tstaic array is an implementation of an array that llocates a ixed amount of memory to be used for storing the array's values. Appending vlues to the array therefore involves copyinmg the entire array and allocating new memory for it, accountin for the extra space needed for te newly appended value. This is a linear-time operation

A dynamic array is an implementation of an array that preemptively allocates double the amount of memory needed to store the array's values. Appendig values to the array is a constant-time operation until the allocated memory is filled up, at which point the array is copied and double the memory is once again allocated fo it. This implementation leads to an amortized constant-time insertion-at-end operation

**Chat GPT**
```
W kontekście struktur danych, tablica (ang. array) jest podstawową strukturą, która służy do przechowywania elementów o jednakowym typie danych w formie sekwencji lub listy. Tablice są szeroko wykorzystywane w programowaniu do organizowania i przechowywania danych, zwłaszcza w językach programowania, gdzie dostęp do elementów tablicy odbywa się poprzez indeksy.

Oto kilka kluczowych cech tablic w kontekście struktur danych:

1. **Jednorodność**: W tablicy przechowywane są elementy tego samego typu danych. Na przykład, można mieć tablicę liczb całkowitych, łańcuchów znaków lub dowolnego innego typu danych. Jednak wszystkie elementy w tablicy są tego samego typu.

2. **Indeksowanie**: Każdy element w tablicy jest indeksowany, co oznacza, że można uzyskać dostęp do elementu, podając numer indeksu. Indeksy zazwyczaj zaczynają się od zera lub od jedynki, w zależności od konwencji języka programowania.

3. **Statyczna lub dynamiczna wielkość**: Tablice mogą mieć stałą, określoną wielkość na etapie tworzenia (statyczne tablice), lub mogą zmieniać swoją wielkość w trakcie działania programu (dynamiczne tablice). W językach programowania takich jak C/C++, statyczne tablice mają stałą liczbę elementów, podczas gdy w językach takich jak Python, dynamiczne tablice (listy) mogą dynamicznie zmieniać rozmiar.

4. **O(1) dostęp do elementu**: Dostęp do elementu w tablicy jest zazwyczaj bardzo szybki i ma złożoność czasową O(1), ponieważ indeksowanie tablicy odbywa się w sposób bezpośredni, bez konieczności przeszukiwania. Jest to jedna z głównych zalet tablic w porównaniu do innych struktur danych.

5. **Operacje na tablicach**: Tablice pozwalają na różnego rodzaju operacje, takie jak dodawanie nowych elementów, usuwanie istniejących elementów, sortowanie, przeszukiwanie, modyfikację, kopiowanie i wiele innych.

6. **Tablice wielowymiarowe**: Tablice mogą być wielowymiarowe, co oznacza, że można tworzyć tablice, które mają więcej niż jeden wymiar. Na przykład, tablica dwuwymiarowa jest organizowana jako siatka, która ma wiersze i kolumny.

Tablice są fundamentalnym elementem struktur danych i są używane w wielu algorytmach i programach do przechowywania i zarządzania danymi. Są prostym, ale potężnym narzędziem w programowaniu, które umożliwiają efektywne operacje na danych o stałym typie.
```

____________________________________________________________________________________________________________________________________________________________________________________________________

## Linked Lists

![image](https://github.com/dar3k93/DataStructure/assets/49185097/e66db100-04e7-4549-b06d-c61c161079df)

**Chat GPT**
```

Lista jednokierunkowa (ang. Linked List) to jedna z podstawowych struktur danych w informatyce, używana do przechowywania i organizacji danych w sposób dynamiczny. Lista jednokierunkowa składa się z węzłów, z których każdy zawiera pewną wartość (dane) oraz wskaźnik (lub referencję) do następnego węzła. Struktura ta jest bardzo elastyczna i umożliwia skonstruowanie sekwencji danych o zmiennej długości. Oto główne cechy listy jednokierunkowej:

1. **Węzły**: Węzły stanowią podstawowe elementy listy jednokierunkowej. Każdy węzeł zawiera dane (często nazywane "elementem" lub "wartością") oraz wskaźnik do następnego węzła w liście.

2. **Wskaźnik do następnego węzła**: Wskaźnik (lub referencja) do następnego węzła pozwala na przechodzenie od jednego węzła do kolejnego w całej liście. Dzięki temu listy jednokierunkowe są skonstruowane w sposób liniowy, umożliwiający efektywne przeglądanie i modyfikację danych.

3. **Brak wskaźnika do poprzedniego węzła**: W odróżnieniu od listy dwukierunkowej (ang. doubly linked list), lista jednokierunkowa nie posiada wskaźników do poprzednich węzłów. Oznacza to, że można poruszać się tylko w jednym kierunku, od początku listy do jej końca.

4. **Punkt początkowy (head)**: Lista jednokierunkowa ma jeden węzeł, który stanowi punkt początkowy lub "głowicę" listy. To od niego rozpoczyna się przegląd i operacje na całej liście.

5. **Zakończenie listy**: Ostatni węzeł w liście jednokierunkowej ma wskaźnik, który wskazuje na NULL (lub None w niektórych językach programowania), co oznacza, że jest to koniec listy.

Główne operacje wykonywane na listach jednokierunkowych to:
- Dodawanie elementu na koniec listy (append).
- Dodawanie elementu na początek listy (prepend).
- Wyszukiwanie elementu w liście.
- Usuwanie elementu z listy.
- Przeglądanie listy (od początku do końca).
- Inne operacje w zależności od potrzeb, takie jak odwracanie listy czy scalanie dwóch list.

Listy jednokierunkowe są szczególnie przydatne, gdy trzeba dynamicznie zarządzać danymi o zmiennej ilości elementów, bez konieczności alokowania dużego bloku pamięci na stałe. Są często wykorzystywane w implementacjach struktur danych takich jak stosy, kolejki i wiele innych.
```


____________________________________________________________________________________________________________________________________________________________________________________________________

## Hash Tables
A data structure that provides fast insertion, deletion, and lookup of key/value

Under teh hood, a hash uses a dynamic array of linked lists to efficiently store key/value paris. When inserting a key/value pair., a hash function first maps the key, which is typically a string (or any datya that can be hashed, depending on the implementation of the hash table), to an integer value and by extension, to an index in the underlying dynamic array. Then, the value associated with key is added to the linked lis storeed at that index in the dynamic array, and referece to the key is also stored with value.

Hash tables rely on highly optimized hash function to minimize the number of collisions that occur when storing values: cases where two keys mpa to the same index.

Below is an example of what a hash table might look like under the hoodL
```
[
  0: (value1, key1) -> null
  1: (value2, key2) -> (value3, key3) -> (value4, key4)
  2: (value5, key5) -> null
  3: (value6, key6) -> null
  4: null
  5: (value7, key7) -> (value8, key8)
  6: (value9, key9) -> null
]
```

In the hash table above the keys key2, kay3 and key4 collidad by all being hashed to 1, andthe keys key7 and key8 collided by both being hash to 5.
The following are a hash table's standard operations and their corresponding time complexities:
- Inserting a key/value pair: o(1) on average; O(n) in the worse case
- Rmoving a key/value pair: O(1) on average; O(n) in the wore case
- Looking up a key: O(1) on average; O(n) in the worse case

The worst-case linear-time operations occur when a hash table experiences a lot ofcollisions, leading to long linked lists internally which take O(n) time to reaverse.
However, in practice and especially in coding interviews, we typically assume that hash functions employed by hash tyables are so optimized that collisionms are extremey rare and constant-time operartions are all but guaranteed

**Chat gpt**
```
HashTable (zwana również tabelą haszową) to struktura danych używana do przechowywania danych w postaci par klucz-wartość, gdzie każdy klucz jest mapowany na określoną wartość. HashTable jest implementowana jako tablica, w której indeksy (klucze) są przekształcane za pomocą funkcji haszującej na indeksy tablicy, w której przechowywane są odpowiadające wartości. Jest to bardzo efektywna struktura danych, jeśli chodzi o szybki dostęp do elementów, o ile funkcja haszująca jest odpowiednio dobrana i unikatowa.

Kluczowe cechy struktury danych HashTable:

1. **Funkcja haszująca**: Funkcja haszująca przyjmuje klucz jako wejście i generuje indeks w tablicy haszowej. Dobrze zaprojektowana funkcja haszująca ma na celu minimalizowanie kolizji, czyli sytuacji, w której dwa różne klucze mapują się na ten sam indeks. 

2. **Tablica**: HashTable składa się z tablicy, w której przechowywane są wartości. Indeksy tej tablicy generowane są za pomocą funkcji haszującej.

3. **Szybki dostęp**: Jedną z najważniejszych zalet HashTable jest możliwość szybkiego dostępu do elementów. Jeśli funkcja haszująca jest dobrze zaprojektowana i kolizje są minimalizowane, dostęp do elementu odbywa się w stałym czasie (średnio O(1)).

4. **Wstawianie i usuwanie**: Wstawianie i usuwanie elementów również jest efektywne, o ile nie występują częste kolizje.

5. **Kolizje**: Kolizje mogą występować, gdy dwie różne wartości mapują się na ten sam indeks tablicy. W takim przypadku konieczne jest rozwiązanie kolizji za pomocą technik takich jak rozpraszanie liniowe, wiązanie łańcuchowe (lista wiązana w przypadku kolizji) lub podwójne haszowanie.

6. **Rozmiar tablicy**: Rozmiar tablicy haszowej jest ważnym czynnikiem. Zbyt mała tablica może prowadzić do częstych kolizji, podczas gdy zbyt duża tablica może prowadzić do marnowania zasobów. Optymalny rozmiar zależy od konkretnego zastosowania.

Przykłady zastosowań HashTable obejmują przechowywanie informacji o słownikach, katalogach, przechowywanie sesji w aplikacjach internetowych, implementację słowników (map) w językach programowania, itp.

Ważne jest, aby wybierać odpowiednie funkcje haszujące i rozmiary tablicy, aby zapewnić efektywną pracę struktury HashTable i minimalizować ryzyko kolizji. Odpowiednie zaprojektowanie i optymalizacja tej struktury danych jest kluczowa dla wydajności wielu aplikacji.
```
____________________________________________________________________________________________________________________________________________________________________________________________________

## Stacks and Queues

![image](https://github.com/dar3k93/DataStructure/assets/49185097/000f7d33-c58b-4f5f-9fae-b7153ed5075c)

**Chat GPT**
```
Stacks (stosy) i Queues (kolejki) to dwie podstawowe struktury danych, które są często wykorzystywane w programowaniu do rozwiązywania różnych problemów. Oto opis tych struktur w kontekście struktur danych:

**1. Stos (Stack):**
- Stos to struktura danych, w której elementy są przechowywane w taki sposób, że ostatnio dodany element jest pierwszy do usunięcia - zasada "last-in, first-out" (LIFO). 
- Główne operacje stosu to `push` (dodawanie elementu na wierzch stosu) i `pop` (usuwanie elementu z wierzchu stosu).
- Stosy są często wykorzystywane do śledzenia kontekstu wywołania funkcji (zasobów, które zostaną zwolnione, kiedy funkcja zakończy swoje działanie) lub do implementacji algorytmów rekurencyjnych.

Przykład użycia stosu w języku programowania Python:
```python
stack = []
stack.append(1)  # push(1)
stack.append(2)  # push(2)
stack.append(3)  # push(3)
top = stack.pop()  # pop(), top = 3
```

**2. Kolejka (Queue):**
- Kolejka to struktura danych, w której elementy są przechowywane w taki sposób, że pierwszy dodany element jest pierwszy do usunięcia - zasada "first-in, first-out" (FIFO).
- Główne operacje kolejki to `enqueue` (dodawanie elementu na końcu kolejki) i `dequeue` (usuwanie elementu z początku kolejki).
- Kolejki są używane do modelowania procesów obsługi zadań, takich jak algorytmy planowania zadań, obsługi zapytań w serwerach, itp.

Przykład użycia kolejki w języku programowania Python (wykorzystując moduł `collections`):
```python
from collections import deque

queue = deque()
queue.append(1)  # enqueue(1)
queue.append(2)  # enqueue(2)
queue.append(3)  # enqueue(3)
front = queue.popleft()  # dequeue(), front = 1
```

Ogólnie rzecz biorąc, stosy i kolejki są przykładami struktur danych, które pozwalają na kontrolowane zarządzanie elementami danych w kontekście LIFO (stos) lub FIFO (kolejka). Wybór między nimi zależy od konkretnej sytuacji i potrzeb projektu. Stosy są często używane do śledzenia stanu lub wykonywania działań związanych z rekurencją, podczas gdy kolejki są bardziej odpowiednie do obsługi procesów i zadań w porządku ich przyjścia.
```
____________________________________________________________________________________________________________________________________________________________________________________________________

## Strings

One of the fundamenta data types in CS, strings are stored in memory as arrays of integers, where each character in a given string is mapped to an integer via some character-encoding standard like ASCII.

Strings bahave much like normal arrays with the main distinction being that, in most programming languages (C++ is notable exeption), strings are **immutable**, meaning thay they can not be edited after creation. This also menas that simple operations like appending a character to a string are more expensive than might appear.

The canonical example of an operation that is deceptively expensive due to string immutability is the following:
```
string = "This is a string"
newString = ""

for character in string:
  newString += character
```

The opration above has a time complexity of O(n^2) where n is the length of string, because each addition of a character to newString creates an entirely new string and is itself an O(n) operation. Therefore, n O(n) operations are performed, leading to an O(n^2) time-complexity operation overall.

#### Czat GPT
```
W kontekście struktur danych, "Strings" (ciągi znaków) są jednym z podstawowych i powszechnie używanych typów danych. Stringi reprezentują sekwencję znaków, takich jak litery, cyfry, znaki specjalne itp. Są wykorzystywane do przechowywania i manipulowania tekstem w różnych językach programowania. Oto kilka kluczowych cech i operacji związanych z ciągami znaków:

1. **Niemutowalność**: W wielu językach programowania, ciągi znaków są niemutowalne, co oznacza, że nie można ich zmieniać po ich utworzeniu. Jeśli chcesz zmienić zawartość ciągu znaków, musisz stworzyć nowy ciąg.

2. **Indeksowanie**: Każdy znak w ciągu znaków ma przypisany indeks, który pozwala na dostęp do poszczególnych znaków w ciągu. Indeksowanie jest często oparte na zerowym indeksie, co oznacza, że pierwszy znak ma indeks 0, drugi znak ma indeks 1, itd.

3. **Operacje na stringach**:
   - **Konkatenacja**: Łączenie dwóch lub więcej ciągów znaków w jeden.
   - **Porównywanie**: Porównywanie dwóch ciągów znaków, aby sprawdzić, czy są identyczne.
   - **Podciągi**: Wyodrębnianie fragmentów ciągów znaków, tworzenie podciągów.
   - **Zamiana na małe/duże litery**: Zmiana wielkości liter w ciągu (np. zamiana na małe litery, wielkie litery).
   - **Szukanie**: Wyszukiwanie określonych znaków lub podciągów w ciągu.
   - **Zamiana znaków**: Zamiana określonych znaków lub podciągów na inne.

4. **Długość ciągu**: Można sprawdzić długość (ilość znaków) ciągu za pomocą odpowiedniej funkcji lub metody.

5. **Escape sequences**: W stringach można używać sekwencji ucieczki (escape sequences) do reprezentowania specjalnych znaków, takich jak znaki nowej linii (\n) czy znaki tabulacji (\t).

6. **Formatowanie**: W wielu językach programowania istnieją narzędzia do formatowania ciągów znaków, co pozwala na tworzenie dynamicznych wiadomości zawierających zmienne wartości.

Stringi są nieodłącznym elementem większości programów, ponieważ tekst jest powszechnie używaną formą komunikacji i przechowywania danych. W językach programowania istnieją różne implementacje i operacje związane z ciągami znaków, dlatego ważne jest, aby zrozumieć sposób pracy z nimi w konkretnym języku, którym się posługujesz.
```

____________________________________________________________________________________________________________________________________________________________________________________________________

## Graphs

![image](https://github.com/dar3k93/DataStructure/assets/49185097/5c8ff536-f16c-4dc7-9811-21f3e67af261)

**Chat GPT**
```
Graf to jedna z podstawowych struktur danych używanych w informatyce do modelowania i analizy relacji między różnymi elementami. Grafy są wykorzystywane w szerokim zakresie zastosowań, od analizy sieci społecznych i tras w nawigacji, po optymalizację tras w dostawie towarów i wiele innych dziedzin. W kontekście struktury danych, grafy mają następujące cechy i elementy:

1. **Węzły (wierzchołki)**: Węzły reprezentują elementy, miasta, osoby, punkty danych itp., które są połączone w grafie. Każdy węzeł jest unikalnie identyfikowany w grafie.

2. **Krawędzie**: Krawędzie reprezentują relacje lub połączenia między węzłami. Krawędzie mogą mieć różne właściwości, takie jak wagi (koszty), kierunek (w grafach skierowanych) lub etykiety.

3. **Wierzchołek początkowy i końcowy**: W grafach skierowanych (z kierunkiem), każda krawędź ma wierzchołek początkowy (źródło) i wierzchołek końcowy (cel). W grafach nieskierowanych, krawędź łączy dwa wierzchołki i nie ma znaczenia, który jest początkowym, a który końcowym.

4. **Cykl**: Cykl to zamknięta sekwencja krawędzi, która zaczyna się i kończy w tym samym wierzchołku. Cykle mogą być problematyczne w niektórych rodzajach grafów, zwłaszcza w kontekście wyszukiwania ścieżek, ponieważ mogą prowadzić do nieskończonych pętli.

5. **Graf skierowany vs. graf nieskierowany**: W grafach skierowanych, krawędzie mają określony kierunek, podczas gdy w grafach nieskierowanych, krawędzie nie mają określonego kierunku. Na przykład, w sieci społecznej, relacje przyjacielskie są nieskierowane, ponieważ przyjaźń działa w obie strony, ale w sieci przewozowej (np. dróg) kierunek ruchu ma znaczenie, więc graf jest skierowany.

6. **Waga krawędzi**: Niektóre grafy mają wagi na krawędziach, które reprezentują różne koszty lub odległości między węzłami. Grafy z wagami są często wykorzystywane w problemach optymalizacyjnych, takich jak znalezienie najkrótszej ścieżki.

7. **Grafy spójne i niespójne**: Graf spójny to taki, w którym istnieje co najmniej jedna ścieżka między dowolnymi dwoma wierzchołkami. Graf niespójny to taki, który składa się z kilku oddzielnych składowych grafów spójnych.

8. **Reprezentacja**: Grafy mogą być reprezentowane na różne sposoby, takie jak lista sąsiedztwa (adjacency list), macierz sąsiedztwa (adjacency matrix), czy reprezentacje hybrydowe, w zależności od konkretnego zastosowania i wymagań wydajnościowych.

Grafy są używane do rozwiązywania wielu problemów, takich jak znajdowanie najkrótszych ścieżek, wyszukiwanie w głąb, algorytmy minimalnego drzewa rozpinającego (MST), analiza sieci społecznych, planowanie tras i wiele innych. Ich elastyczność i możliwość reprezentowania złożonych relacji między danymi czyni je kluczowymi w dziedzinie algorytmów i analizy danych.
```

____________________________________________________________________________________________________________________________________________________________________________________________________

## Trees

![image](https://github.com/dar3k93/DataStructure/assets/49185097/785eeead-e5c5-459b-8f16-16161ae3d4f4)

**Chat GPT**
```
Drzewo (ang. tree) to jedna z fundamentalnych struktur danych w informatyce, która jest używana do organizacji i hierarchicznego reprezentowania danych. Drzewa są skonstruowane z węzłów połączonych krawędziami i posiadają korzeń (root) oraz węzły wewnętrzne i liście (ang. leaves). Drzewa są wykorzystywane w wielu dziedzinach informatyki, w tym w bazach danych, systemach operacyjnych, analizie języków naturalnych, grafice komputerowej i wielu innych. Oto główne cechy drzew w kontekście struktur danych:

1. **Korzeń (root)**: Korzeń drzewa to węzeł, który jest na samym szczycie hierarchii. Każdy inny węzeł drzewa jest osiągalny z korzenia za pomocą ścieżki.

2. **Węzły wewnętrzne**: Węzły wewnętrzne to węzły, które posiadają co najmniej jedno dziecko. Są one pośrednimi węzłami na drodze od korzenia do liści.

3. **Liście (leaves)**: Liście to węzły, które nie posiadają dzieci. Są to końcowe punkty drzewa, które nie mają podwęzłów.

4. **Krawędzie**: Krawędzie łączą węzły w drzewie. Każda krawędź łączy węzeł nadrzędny z jednym z jego węzłów potomnych.

5. **Poziomy (levels)**: Poziomy drzewa to poziome warstwy w hierarchii drzewa. Poziom 0 to korzeń, poziom 1 to dzieci korzenia, poziom 2 to wnuki korzenia, itp.

6. **Wysokość (height)**: Wysokość drzewa to maksymalny poziom w drzewie, czyli najdłuższa ścieżka od korzenia do dowolnego liścia.

7. **Poddrzewo (subtree)**: Poddrzewo to część drzewa, która jest również drzewem. Może być izolowanym poddrzewem lub częścią większego drzewa.

8. **Drzewo binarne**: Drzewo binarne to szczególny rodzaj drzewa, w którym każdy węzeł może mieć co najwyżej dwóch potomków: lewego i prawego. Drzewa binarne są często wykorzystywane w algorytmach sortowania, przeszukiwania, itp.

9. **Inne rodzaje drzew**: Oprócz drzew binarnych istnieją również inne rodzaje drzew, takie jak drzewa AVL (samo-wyważające się drzewa binarne), drzewa czerwono-czarne, drzewa B-drzew, drzewa Trie, drzewa Quadtree (używane w grafice komputerowej) i wiele innych.

Drzewa są szeroko stosowane w programowaniu i informatyce ze względu na ich zdolność do hierarchicznego organizowania danych. Mogą być wykorzystywane do skomplikowanych operacji wyszukiwania, sortowania, organizacji danych i grafiki komputerowej, a także w strukturach danych takich jak drzewa BST (Binary Search Tree), drzewa XML w analizie języków naturalnych, i wiele innych. Ich zrozumienie i umiejętność obsługi drzew są kluczowe dla każdego programisty i inżyniera oprogramowania.
```






