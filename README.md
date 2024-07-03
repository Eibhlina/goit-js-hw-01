
https://eibhlina.github.io/goit-js-hw-01/


Zadanie 1: Zamawianie droidów

Stacja sprzedaży droidów naprawczych jest gotowa do pracy, zostało tylko napisać oprogramowanie dla działu sprzedaży.



Zadeklaruj funkcję makeTransaction, która oczekuje dwóch parametrów, których wartości zostaną ustawione po jej wywołaniu: • quantity — pierwszy parametr, liczba zawierająca liczbę zamówionych droidów; • pricePerDroid — drugi parametr, liczba zawierająca cenę jednego droida.



Uzupełnij kod funkcji tak, aby zwracała ciąg znaków z komunikatem o zakupie droidów naprawczych: "You ordered <quantity> droids worth <totalPrice> credits!", gdzie: • <quantity> — to liczba zamówionych droidów; • <totalPrice> — to całkowity koszt zamówienia, tj. koszt wszystkich zamówionych droidów.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Zadanie 2. Dostawa towarów

Zadeklaruj funkcję getShippingMessage, która oczekuje trzech parametrów, których wartości zostaną ustawione po jej wywołaniu: • country — pierwszy parametr, ciąg znaków zawierający kraj dostawy; • price — drugi parametr, liczba zawierająca całkowity koszt towarów; • deliveryFee — trzeci parametr, liczba zawierająca koszt dostawy towaru.



Uzupełnij kod funkcji tak, aby zwracał ciąg znaków z komunikatem o dostawie towaru do kraju użytkownika: "Shipping to <country> will cost <totalPrice> credits", gdzie: • <country> — to kraj dostawy; • <totalPrice> — to całkowity koszt zamówienia, w tym koszt towarów i ich dostawy.



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Zadanie 3: Szerokość elementu

Zadeklaruj funkcję getElementWidth, która oczekuje trzech parametrów, których wartości zostaną ustawione po jej wywołaniu: • content — pierwszy parametr, szerokość treści; • padding — drugi parametr, wartość poziomego wypełnienia dla każdej strony; • border — trzeci parametr, wartość grubości obramowania dla każdej strony. Wartościami wszystkich parametrów będą ciągi znaków w formacie Npx, gdzie N jest dowolną liczbą całkowitą lub ułamkową.



Zmodyfikuj kod funkcji tak, aby zwracała liczbę — całkowitą szerokość elementu. Podczas obliczania całkowitej szerokości pamiętaj, że wartość box-sizing jest równa border-box.



