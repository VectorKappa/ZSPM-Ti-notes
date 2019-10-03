# Aby utworzyć relacje między tabelami, muszą byc spełnione warunki:

-   pola wspólne muszą mieć ten sam typ danych
-   jeśli klucz podstawowy tworzy pole "autonumerowanie", pole klucza obcego musi być polem typu liczba, ale rozmiar pola musi być taki sam
-   pole wspólne tabeli ze strony 1 musi być polem klucza podstawowego
-   pola łączone _muszą_ zawierać pola wzajemnie sobie odpowiadające

# Typy sprzężeń

-   po włączeniu _"wymuszaj więzy integralności"_ stosowane są następujące reguły:
-   nie można wprowadzić wartości w polu klucza obcego tabeli połączonej jeśli ta wartość nie istnieje w polu klucza podstawowego tabeli podstawowej (powstaną odłączone rekordy).
-   nie można usunąć rekordu w tabeli podstawowej, jeśli w tabeli połączonej istnieją rekordy pasujące do niego
-   nie można zmienić wartości klucza podstawowego w tabeli połączonej, jeśli spowodowałoby to powstanie rekordów odłączonych
