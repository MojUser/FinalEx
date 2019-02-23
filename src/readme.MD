##Projekt
Celem projektu jest napisanie gry w Hanoi:
https://pl.wikipedia.org/wiki/Wie%C5%BCe_Hanoi
##Zadania

1. Stwórz aplikację, która będzie tworzyła 3 stosy. Jeden z nich będzie wypełniony cyframi `5 4 3 2 1`. Cyfry te reprezentują rozmiary krążków. Cyfry są podane w kolejności dodawania ich na stos to znaczy cyfra 5 musi być na spodzie stosu itd.Stosy są numerowane od 1 do 3.

2. Dodaj metodę, która będzie wypisywała stosy

3. Użytkownik powinien mieć możliwość podania 2 cyfr, pierwsza to stos z którego zostanie zabrany krążek a drugi to stos na który zostanie położony krążek.

4. Jeżeli stos z którego użytkownik chce zabrać krążek jest pusty, należy wypisać wiadomość `
Wybrany stos jest pusty`.

5. Jeżeli ruch, który chce wykonać użytkownik jest nielegalny(jeżeli użytkownik próbuje przenieść większy krążek na mniejszy) należy wypisać wiadmość `Ruch Nielegalny!`

6. Dodaj metodę, która po pobraniu od użytkownika dwóch liczb zabierze krążek(inta) z pierwszego stosu i przeniesie do drugiego stosu. Należy tutaj spełnić zalożenia gry patrz punkty 4. i 5.

8. Aplikacja powinna działać w pętli, która będzie się wykonywała w nieskończoność. Każde wykonanie pętli to przyjęcie od użytkownika dwóch liczb i wykonanie ruchu (patrz punkt 6.) a następnie wypisanie stanu stosów po ruchu.

7. Po każdym ruchu należy sprawdzić czy gra jest zakończona. Jeżeli tak, to należy wypisać użytkownikowi informacje: `Gratulacje Użytkowniku! Udało ci się rozwiązać łamigłówkę!` i przerwać pętlę.

8. Dodaj możliwość, aby przed grą użytkownik podał nick. Po zakończeniu gry w wiadomości końcowej należy wyświetlić nick, który podał użytkownik.

9. Dodaj do aplikacji licznik ruchów, który będzie liczył ile operacji potrzebował użytkownik na zakończenie gry. W wiadomości końcowej, powinna się również znaleźć informacja o ilości wykonanych ruchów.

11. Dodaj możliwość zdefiniowania ilości krążków (intów), które będą brały udział w grze. Dopuszczalna ilość krążków to od 3 do 10.

13. Po zakończeniu rozgrywki, aplikacja powinna zapytać użytkownika czy chce zapisać swój wynik do pliku.Jeżeli użytkownik odpisze twierdząco to do pliku powinna zostać dodana nazwa użytkownika i ilość ruchów, która była mu potrzebna do zakończenia gry.

14. Jeżeli użytkownik jest już tabeli wyników, jego wynik:
- jeżeli jest lepszy, powinien zostać zaktualizowany
- jeżeli jest gorszy, powinien pozostać bez zmian.

15. Przed rozpoczęciem gry, użytkownik powinien mieć możliwość zobaczenia tabeli wyników.

14. Gra powinna dawać możliwość wypisania określonej liczby najlepszych lub najgorszych wyników. (Użytkownik powinien podać czy chce najlepsze czy najgorsze wyniki a potem liczbę, która będzie oznaczała ile wyników zostanie pokazane.)

16.* Gra powinna dawać możliwość zdefiniowania ilości stosów, które biorą udział w grze.

17.* Gra powinna dawać możliwość cofnięcia ostatniego ruchu.

18. Dodaj możliwość zresetowania gry. Zaczyna się wtedy ona od początku. Włącznie z liczbą ruchów.
