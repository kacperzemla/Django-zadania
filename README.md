# Zadanie 1
Stwórz samodzielnie od zera projekt. Kieruj się wskazówkami z 4  i 5 slajdu.
Po uruchomieniu serwera powinna wyświetlać się następująca strona.
![image](https://user-images.githubusercontent.com/56030578/117650138-a06f7c80-b190-11eb-94ce-16b74fc120b8.png)
Następnie tworzymy plik urls.py w folderze aplikacji i konfigurujemy plik views.py. 
Po poprawnie wykonanym zadaniu strona powinna wyglądać następująco 
![image](https://user-images.githubusercontent.com/56030578/117650277-cf85ee00-b190-11eb-82cc-cbc5d5a1b57a.png)

# Zadanie 2
Celem będzie stworzenie modelu i stworzenie obiektu w bazie danych.
Stwórz model Exercise, który zawiera pola name, weight, reps, date (slajd 8 i projekt może być pomocny). Ograniczenia każdego pola ustaw według swoich preferencji.
Ustaw aby w bazie danych Exercise było widziane po nazwie (funkcja def __str__(self))
Wykonaj migracje i stwórz superusera (slajd 5)
Skonfiguruj plik admin.py (slajd 8)
Przejdź pod adres http://127.0.0.1:8000/admin i zaloguj sie
W bazie danych powinno pojawić się pole Exercise.
Dodaj swoje pierwsze ćwiczenie.
![image](https://user-images.githubusercontent.com/56030578/117650359-e6c4db80-b190-11eb-941a-4ec19034dcdc.png)

# Zadanie 3
W bazie danych stwórz 5 ćwiczeń. Twoim celem będzie wyświetlenie ich na stronie. W tym celu utwórz folder templates w folderze aplikacji i w nim jeszcze jeden folder o tej samej nazwie co aplikacja ( w views  trzeba zaimportować folder template) , a w nim plik html i w odpowiednim pliku stwórz funkcję, która zwróci ten plik html jako widok ( wskazówki znajdują się w prezentacji ). 
Następnie w tej funkcji utwórz zmienną do, której przypiszesz 
wszystkie obiekty Exercise ( screen ze slajdu 9 ). Przekaż do funkcji return render listę obiektów i wyświetl na stronie Twoje zadania. ( Wzoruj się na linii 143 z pliku exercises.html, dane wstaw w znacznik <p> ) 
![image](https://user-images.githubusercontent.com/56030578/117650420-f6442480-b190-11eb-8a91-c4d22d4aaead.png)

