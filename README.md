# Instrukcja do zaistlowania i uruchumienia aplikacji 
## Potrzebne programy
Najpierw upewniej się że masz na komputerze zaistalowanie programy takie jak : GitBash, Pycharm ,Python(wersja nie niższa niż 3.9).
## Potrzebne pliki
Ściągnij potrzebne pliki(app.py,hello.html,index.html,requirements.txt) możesz je ściągnąć z github. 
## Uruchamianie aplikacji
1.  W GitBash uzyj komendy git clone(link twojego repozytorium z github), a następnie stwórz podkatalog i nazwij go, a w nim powinny znajdować się pilki hello.html,index.html, a pozostałe dwa pliki zostanią w folderze głównym.
2.  Aby na github pokazały się zmiany napierw wpisz git init, a potem git add . ,następnie git commit -m"jaka chcesz nazwę" i na koniec git push. Po wykonaniu tych czyności powinno ci się pojawić zmianny na github.
3.   Stwórz plik Madefile w katalogu głównym, a następnie dodaj w nim dwie komendy(np. za pomocą nano Makefile po wpinanie tej komendy w GitBash powinno się pojawić okno gdzie można przepisać komendy jakie chcesz dodać do pliku.Aby zapisać zmiany wciśnij ctrl+o, a żeby wyjść ctrl+x) pip install –r requirements.txt(odpowiada on za tworzenie bibliotek),flask run lub python –m flask run(mają ta samą fukcje, która jest odpowiedzialna za uruchomienie aplikacji flask).
## Udanie uruchomienie aplikacji
1.Po udaniu się uruchomienia aplikacji w terminalu powinna pokazać się informacja, że serwer jest uruchomiony na porcie 5000.
## Ważność README
README jest ważne w projekcie, ponieważ odpowida on za jasne instrukcje do danego kodu, który dana osoba napisała, aby osoby, które potem chcą korzystać z kodu wiedziały jak działa kod bez żadnych problemów. Ułatwia on też współpracy z innymi osobami oraz daje możliwość innym znajlezieniu projektów innych użytkowników za pomocą wpisania kluczowych słów.
