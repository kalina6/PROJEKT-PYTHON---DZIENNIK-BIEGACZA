# PROJEKT-PYTHON---DZIENNIK-BIEGACZA
##WSTEP


Celem projektu jest przygotowanie programu komputerowego, który jest dziennikiem biegacza. Program ten ma być napisany przy użyciu jezyka Python i dzialać w srodowisku Windows jako program uruchamiany.


#####Definicje:


SQLite- baza danych.


Biblioteka Tkinter - sluży do tworzenia graficznych interfejsów użytkownika.


##OPIS OGÓLNY


1)Interfejs użytkownika (graficzny interfejs użytkownika), program realizowany jako interfejs graficzny przy użyciu biblioteki Tkinter.


2)Interfejs systemowy, aplikacja bedzie korzystala z dostepu do systemu plikow, w celu zapisania stanu programu przy uzyciu wbudowanej bazy danych.


3)Aplikacja korzysta z klawiatury i myszy za posrednictwem dostarczonym poprzez biblioteke Tkinter.


##FUNKCJE:

1)wprowadzanie, odczytywanie oraz modfikacja danych dotyczacych biegu


2)wyswietlanie raportu danych dziennych, tygodniowych oraz miesiecznych


##OGRANICZENIA, ZALOŻENIA,ZALEŻNOSCI:


Zakladam, że program bedzie obslugiwal tylko jeden użtkownik dlatego nie bedzie wymaga logowania przy starcie. Dzialanie programu wymaga wczesniejszego zainstalowania w systemie operacyjnym biblioteki Tkinter oraz bazy danych SQLite.

##WYMAGANIA SZCZEGÓŁOWE:


Program nie korzysta z interfejsów sieciowych.

## FUNKCJONALNOSC I WYDAJNOSC:


Możliwosc zapisu, modyfikacji oraz odczytu ilosci przebiegnietych kilometrów w danym, wybranym przez użytkownika terminie oraz czas pokonanego dystansu, ilosc spalonych kalorii. Na podstawie wprowadzonych danych program automatycznie bedzie wyliczal predkosc biegacza zgodnie ze wzorem: V=s/t. Program bedzie wyswietlal tygodniowy i miesieczny raport aktywnosci (możliwosc przewijania danych w gore i w dol). Aplikacja bedzie miala także opcje do ukladania planu treningowego na tydzien i zapisania go w tabeli.


##WYMAGANE BAZY DANYCH:
Wymagane bedzie użycie bazy danych SQLite.


##CECHY OPROGRAMOWANIA:
Aplikacja powinna być odporna na przypadkowe lub zamierzone bledy użytkownika.
