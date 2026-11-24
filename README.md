# Giełda korepetycji szkolnych

**Celem projektu jest stworzenie platformy, która ułatwi uczniom wzajemną pomoc w nauce.**

Aplikacja internetowa skierowana do uczniów, umożliwiająca wzajemną pomoc w nauce. Użytkownicy mogą publikować oferty korepetycji, wyszukiwać pomoc z wybranych przedmiotów szkolnych, umawiać terminy zajęć oraz rezerwować spotkania. Platforma oferuje również system wiadomości umożliwiający kontakt między uczniami oraz system ocen i opinii pozwalający ocenić jakość udzielonej pomocy.

## Funkcje Aplikacji
- **Rejestracja i logowanie użytkowników**
- **Dodawanie i przeglądanie ofert korepetycji z przedmiotów szkolnych**
- **Ustalanie dostępnych terminów**
- **Rezerwowanie i odwoływanie spotkań**
- **Wiadomości między uczniami**
- **Opinie po zajęciach**

## Plan rozbudowy
- **Wideorozmowy w czasie rzeczywistym:** integracja z WebRTC lub zewnętrznym API (np. Jitsi / Agora) w celu prowadzenia lekcji bezpośrednio w aplikacji.
- **Interaktywna tablica (Whiteboard):** udostępnienie wspólnej, cyfrowej przestrzeni do rysowania i rozwiązywania zadań z matematyki czy fizyki.
- **System powiadomień:** powiadomienia e-mail oraz push (np. przez Firebase Cloud Messaging) przypominające o zbliżających się lekcjach lub nowatorskich wiadomościach.
- **Gamifikacja i osiągnięcia:** wprowadzenie odznak dla aktywnych korepetytorów oraz systemu punktów za pomaganie innym.

## Stack
### 1. Frontend
- **JavaScript**
### 2. Backend
- **Node.js**
- **React.js**
### 3. Bazy danych
- **PostgreSQL** - relacyjna baza danych przechowująca:
  - użytkownicy
  - przedmioty
  - terminy
  - rezerwacje
- **MongoDB** - nierelacyjna baza danych przechowująca:
  - opinie
  - wiadomości

