## Zadanie 1 
Rozwiązać test wiedzy w postaci quizu na platformie UPEL. W każdym pytaniu tylko jedna odpowiedź jest
poprawna. Pytania są uporządkowane chronologicznie zgodnie z porządkiem prezentacji.

## Zadanie 2 
Utwórz klasę testującą dla klasy IP_Calculator (w trakcie prezentacji zostanie pokazane jak to zrobić).
Wzorując się na slajdzie nr 18 stwórz dwa własne testy dla metody isAddressCorrect. 
Jeden z testów powinien wykorzystywać asercję assertTrue, a drugi assertFalse. <br />
Przykładowy poprawny adres: 192.168.1.0 <br />
Przykładowy niepoprawny adres: 123..0.8 <br />
W odpowiedzi umieść plik tekstowy zawierający oba testy (nie trzeba wysyłać całej klasy).

## Zadanie 3 
Utwórz klasę testującą dla klasy Network. Wzorując się na slajdzie nr 19:
- Zadeklaruj obiekt klasy Network.
- Utwórz pole @BeforeAll i zainicjalizuj tam wcześniej stworzony obiekt klasy Network.
- Utwórz pole @AfterAll, w którym wyczyścisz pamięć po obiekcie klasy Network.
- Napisz dwa własne testy dla metody getNetworkMaskDecimal() wywoływanej na utworzonym
przez Ciebie obiekcie klasy Network. Jeden z testów powinien wykorzystywać asercję assertEquals, a 
drugi assertNotEquals. <br />

Przykładowa poprawna zamiana maski: 20 -> 255.255.240.0 <br />
Przykładowa błędna zamiana maski: 24 -> 192.192.0.0 <br />
W odpowiedzi umieść plik (z rozszerzeniem .java) zawierający stworzoną przez Ciebie klasę.

## Zadanie 4 
Wzorując się na slajdzie nr 20 utwórz pole @Nested (w stworzonej w zadaniu trzecim klasie testowej
klasy Network). Analogicznie:
- Dodaj linijkę @TestInstance(TestInstance.Lifecycle.PER_CLASS)
- Utwórz nową klasę dla testowania specifycznego zachowania programu.
- Utwórz obiekt klasy ArrayList
- Utwórz pole @BeforeAll i dodaj kilka podsieci (list.add(int)) o różnych liczbach hostów.
- Utwórz pole @AfterAll, w którym wyczyścisz pamięć po obiekcie klasy ArrayList.
- Przetestuj metodę klasy Network isNumberOfHostsCorrect(). Jeśli liczba dostępnych w 
uwtorzonej przez ciebie sieci adresów jest wystarczająca wykorzystaj metodę assertTrue
(tak jak na slajdzie). W przeciwnym razie powinieneś wykorzystać metodę assertFalse. <br />

W odpowiedzi umieść plik (z rozszerzeniem .java) zawierający stworzoną przez Ciebie klasę.
