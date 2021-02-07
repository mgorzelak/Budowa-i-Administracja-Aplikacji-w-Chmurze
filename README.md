# Budowa-i-Administracja-Aplikacji-w-Chmurze

Prosty rssSender na zajecia z Budowa i Administracja Aplikacji w Chmurze

Zadaniem aplikacji jest ściąganie zawartości RSS z podanych przez użytkowników linków.


Aplikacja składaa się z klienta (tzw frontend), serwera (tzw. backend) i bazy danych
Frontend to prosta strona, na której użytkownik może zapisywać linki RSS przez serwer do bazy danych.
Backend oprócz tego, że komunikuje się z bazą danych ma za zadanie stworzyć maila,
który będzie zawierał wszystkie artykuły, które znajdują się pod podanymi linkami przez użytkownika.

1. Frontend zawierający kontrolki:
Textbox z możliwością wpisania urla do RSS
Przycisk Save zapisujący urla do bazy danych
Frame, który będzie pokazywał zbudowanego maila przez backend
Przycisk Preview który będzie requestował do backendu o zbudowanie takiego maila

2. Backend
moduł do zapisywania linków do bazy
moduł, który buduje maile w formie html'a
