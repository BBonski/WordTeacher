# WordTeacher #


Omówienie projektu
------------------
WordTeacher to aplikacja przeznaczona do nauki słówek w językach obcych, wykorzystując do tego mnemotechnikę "cyfrowych fiszek".

Szczegółowe omówienie działania aplikacji
-----------------------------------------
Jej zasada działania polega na pytaniu użytkownika o odpowiednik wyświetlonego słowa w drugim języku i oczekiwaniu na wpisanie odpowiedzi. Wpisana odpowiedź jest sprawdzana i wyświetlany jest odpowiedni komunikat, informujący czy jest poprawna czy nie. Proces ten wykonywany jest dla każdego słowa wielokrotnie, np. do momentu kiedy zostanie ono wpisanie poprawnie określoną ilość razy z rzędu - wtedy aplikacja uznaje, że użytkownik nauczył się już tego słowa i już o nie nie pyta. Koniec całej procedury nauki następuje, kiedy nie pozostanie już słów do nauki.

Planowana podstawowa funkcjonalność
-----------------------------------
- nauka słówek ww. metodą
- tworzenie nowych zestawów słówek
- test znajomości polegający na jednokrotnym odpytaniu i wyliczeniu procentu poprawnych odpowiedzi

Ewentualna dodatkowa funkcjonalność
-----------------------------------
Jest to ponadprogramowa funkcjonalność, z której znaczna część pewnie znajdzie się w ostatecznej wersji projektu, ale jest to uzależnione od różnych czynników, z których główną rolę gra czynnik czasowy.

- przegląd zawartości zestawu słówek
- szybkie przypomnienie/nauka przyspieszona poprzez test wielokrotnego wyboru
- możliwości konfiguracyjne (np. możliwość ustawienia intensywności nauki)
- 2 tryby nauki: język obcy/natywny, język natywny/obcy
- nauka wymowy

Wymagane oprogramowanie i użyte technologie
-------------------------------------------
- Python 3
- Tkinter
- zapewne kilka innych bibliotek z zakresu bibliotek standardowych
