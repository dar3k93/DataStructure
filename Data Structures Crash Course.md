- [Complexity Analysis](#Complexity-Analysis)
- [Memory](#Memory)
- [Big O Notation](#Big-O-Notation)
- [Logarithm](#Logarithm)
- [Arrays](#Arrays)
- [Linked Lists](#Linked-Lists)
- [Hash Tables](#Hash-Tables)
- [Stacks and Queues](#Stacks-and-Queues)
- [Strings](#Strings)
- [Graphs](#Graphs)
- [Trees](#Trees)

____________________________________________________________________________________________________________________________________________________________________________________________________

## Complexity Analysis

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

Czat GPT
Pamięć komputerowa, zwana również pamięcią systemową lub pamięcią operacyjną (RAM - Random Access Memory), to istotny element komputera, który służy do przechowywania danych i programów, nad którymi obecnie pracuje. Pamięć ta jest odczytywalna i zapisywalna, co oznacza, że można w niej przechowywać i modyfikować dane w czasie rzeczywistym. Oto główne cechy i funkcje pamięci komputerowej:

Szybki dostęp: Pamięć RAM zapewnia bardzo szybki dostęp do danych w porównaniu do innych rodzajów pamięci, takich jak dyski twarde. Jest to kluczowe dla wydajności komputera, ponieważ umożliwia szybkie odczytywanie i zapisywanie danych przez procesor.

Ultraniski czas dostępu: Czas dostępu do pamięci RAM jest bardzo krótki, mierzony w nanosekundach, co oznacza, że komputer może natychmiastowo uzyskać dostęp do danych przechowywanych w pamięci RAM.

Przechowywanie danych programów: Aktualnie działające programy i system operacyjny są przechowywane w pamięci RAM. To pozwala na szybkie wykonywanie operacji i umożliwia użytkownikom interakcję z komputerem w czasie rzeczywistym.

Czasowa trwałość: Pamięć RAM jest ulotna, co oznacza, że dane w niej przechowywane są tracone po wyłączeniu komputera lub po zresetowaniu. Dlatego ważne jest regularne zapisywanie danych na trwałym nośniku, takim jak dysk twardy.

Rozmiar i pojemność: Komputery posiadają różne ilości pamięci RAM, zwykle w zakresie od kilku gigabajtów do kilku terabajtów. Rozmiar pamięci RAM ma wpływ na zdolność komputera do obsługi większej liczby programów i większych zestawów danych.

Wirtualna pamięć: Systemy operacyjne mogą tworzyć wirtualną pamięć, korzystając z kombinacji pamięci RAM i dysku twardego. To pozwala na obsługę większych programów i danych, chociaż dostęp do wirtualnej pamięci jest znacznie wolniejszy niż do pamięci RAM.

Typy pamięci RAM: Istnieją różne rodzaje pamięci RAM, w tym DDR (Double Data Rate), SDRAM (Synchronous Dynamic Random Access Memory) i wiele innych. Każdy z tych typów ma swoje własne cechy i prędkości.

Pamięć RAM jest jednym z kluczowych czynników wpływających na ogólną wydajność komputera. Im większa i szybsza pamięć RAM, tym komputer jest w stanie obsłużyć większą ilość zadań i działać z większą wydajnością. Jednakże sama pamięć RAM nie przechowuje danych po wyłączeniu zasilania, dlatego ważne jest regularne zapisywanie danych na dysku twardym lub innych trwałych nośnikach

____________________________________________________________________________________________________________________________________________________________________________________________________

## Big O Notation

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

____________________________________________________________________________________________________________________________________________________________________________________________________

## Graphs

____________________________________________________________________________________________________________________________________________________________________________________________________

## Trees


