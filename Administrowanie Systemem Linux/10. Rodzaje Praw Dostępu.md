# Rodzaje Praw Dostępu

### Występują trzy rodzaje praw dostępu:
> r - read (odczyt)\
> w - write (zapis)\
> x - execute (uruchomienie)

### Istnieją 3 grupy użytkowników, dla których definiowane są oddzielne zestawy praw dostępu. Są to:
> - właściciel pliku
> - grupa użytkowników, do których należy właściciel
> - pozostali użytkownicy i grupy

### Linux nie rozróżnia plików na podstawie rozszerzenia, a na podstawie uprawnień:

|   d   |        rwx        |            rwx            |      rwx      |
| :---: | :---------------: | :-----------------------: | :-----------: |
|       |         u         |             g             |       o       |
|       | user - właściciel | group - grupa właściciela | others - inni |

_(Katalog o wszystkich uprawnieniach **(drwxrwxrwx)**)_

### W przypadku katalogów:

> r - przeszukiwanie zawartości\
> w - zmiana zawartości\
> x - wejście do katalogu

|   d   |           rwx            |                     r-x                     |  r-x  |
| :---: | :----------------------: | :-----------------------------------------: | :---: |
|       | właściciel może wszystko | grupa i inni mogą  tylko przeszukać i wejść |

### W przypadku plików:

> r - czytanie, odtwarzanie\
> w - modyfikacja, edycja\
> x - uruchamianie

|   -   |                     rw-                     |  rw-  |          r--           |
| :---: | :-----------------------------------------: | :---: | :--------------------: |
|       | właściciel i grupa mogą czytać i nadpisywać |       | inni mogą tylko czytać |