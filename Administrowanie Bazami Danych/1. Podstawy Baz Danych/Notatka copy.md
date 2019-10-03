## Własności klucza głównego:

> -   Klucz główny jednoznacznie identyfikuje dany rekord
> -   \-----||----- nie może być NULL
> -   \-----||----- jest niezbędny przy zakładaniu relacji
> -   \-----||----- ma być rzadko zmieniany (lub w ogóle)

## Cechy istotne przy zakładaniu relacji:

> -   pola wspólne w obu tabelach mają mieć ten sam typ danych
> -   rozmiar tego pola musi być taki sam
> -   pole wspolne ze strony tabeli 1 musi byc kluczem podstawowym
> -   pole wspolny ze strony wiele - polem klucza obcego
> -   pola laczone musza byc wzajemnie odpowiadajace
> -   relacje miedzy tabelami pozwalaja na projektowanie kwerend na podst wielu tabel, raportow i formularzy opartych na tabelach, poprzez wymuszanie wiezow integralnosci zapobiegaja powstawaniu rekordow odlaczonych
