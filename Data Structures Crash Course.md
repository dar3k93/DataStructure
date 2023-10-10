- [Complexity Analysis](#Complexity-Analysis)
- [Memory](#Memory)
- [Big O Notation](#Big-O-Notation)
- [Logarithm](#Logarithm) - TODO
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

____________________________________________________________________________________________________________________________________________________________________________________________________

## Arrays

____________________________________________________________________________________________________________________________________________________________________________________________________

## Linked Lists

____________________________________________________________________________________________________________________________________________________________________________________________________

## Hash Tables

____________________________________________________________________________________________________________________________________________________________________________________________________

## Stacks and Queues

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

____________________________________________________________________________________________________________________________________________________________________________________________________

## Trees


