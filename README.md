# jMeterDatabaseTest

Przygotuj zestaw testów które umożliwiają:(3 punkty)
1) Potwierdzenie ze baza danych jest uruchomiona i działa. W wybranym pliku zewnętrzym zapisze się potwierdzenie: DB_UP_AND_RUNNING. Przeciwnym razie: DB_FAILED. Simple data Writer.
2) odczytanie z pliku CSV wartości i zapytanie o nie bazę danych.
3) zgłosznie alarmu w pliku db_performance_Alert.txt jako "1" w przypadku gdy któreś zapytanie wykona się krócej niż X (określony w parametrze aplikacji). W przeciwnym razie wartośc w pliku wynosi "0".
4) Na podstawie pliku CSV przygotuje i wykona operację INSERT/UPDATE na bazie danych danych.
5) Odpali ten test cyklicznie co 2 minuty przez 10 minut każdego dnia.
