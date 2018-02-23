# Wype�nianie danych o prowadzonej firmie:

1. W zak�adce "Orygina�" (od faktury) wprowad� (patrz obramowane na czerwono miejsca na za��czonym obrazku):
- Dane o prowadzonej firmie: nazwa, adres, NIP
- Nazwa miejscowo�ci, w kt�rej wype�niono faktur�
- Nr rachunku bankowego

![init_1](/ZrzutyEkranu/inicjalizacja_orygina�.jpg 'Inicjalizacja w zak�adce "Orygina�"')

2. W zak�adce "Kreator JPK" wype�ni� pola (patrz obramowane na czerwono miejsca na za��czonym obrazku):
- NIP
- Pe�na nazwa
- Email
- Domy�lny katalog, w kt�rym maj� by� zapisywane wygenerowane pliki JPK

![init_2](/ZrzutyEkranu/inicjalizacja_kreator_jpk.jpg 'Inicjalizacja w zak�adce "Kreator_JPK"')

# W��czenie makr:



# Dodawanie nowych klient�w:

* NIP nale�y wpisa� jako liczba (bez znak�w "-")

# Dodawanie nowych dostawc�w:

* NIP nale�y wpisa� jako liczba (bez znak�w "-")

# Dodawanie nowych towar�w:


# Nowa faktura sprzeda�y:

* Na jasno-szaro zaznaczone s� pola do wype�nienia
* Pod faktur� znajduj� si� przyciski:
- "Dodaj faktur� do rejestru sprzeda�y" - przepisuje aktualnie wype�nione pola z faktury do rejestru sprzeda�y
- "Drukuj kopi�" - przeskakuje do arkusza z kopi�, otwiera okno drukowania, a po wszystkim wraca z powrotem do zak�adki orygina�u faktury
- "Wyczy�� faktur�" - czy�ci wyszarzone pola (przywraca do domy�lnych ustawie� np. dat� faktury). Pami�taj, by przed wyczyszczeniem faktury doda� j� do rejestru sprzeda�y!
* Mo�na obejrze� zarejestrowane faktury sprzeda�y w zak�adce "Sprzeda�". Niepoprawnie dodan� faktur� mo�na usun��, klikaj�c prawym przyciskiem myszy po lewej stronie na z�y wiersz i klikaj�c "Usu� wiersze".


# Nowy wpis do rejestru zakupu:

* Przewidziano ok. 1000 miejsc
* Na bia�o s� zaznaczone pola do wype�nienia. Na szaro s� zaznaczone pola, kt�re wype�ni� si� automatycznie.

# Generowanie JPK:

1. Przejd� do zak�adki "Kreator_JPK"
2. Wprowad� dat� w wyszarzonym polu pod polem "DataOd". Pole "DataDo" wype�ni si� automatycznie.
Pole "DataWytworzeniaJPK" wype�nia si� aktualn� dat� (data ostatniego otworzenia dokumentu).
3. Pole pod polem "CelZlozenia" wype�nij we w�asnym zakresie: 0 jest dla pierwotnego dokumentu (w roku 2018).
4. Kliknij w przycisk "Wygeneruj JPK"
5. Wska� docelowy folder gdzie ma zosta� zapisany plik csv.
6. W tym momencie funkcjonalno�� tego programu si� ko�czy. Wygenerowany plik CSV pos�u�y do przes�ania JPK aplikacj� "Klient JPK 2.0" - udost�pnion� przez Ministerstwo Finans�w.

# Dane sprzeda�y/zakupu miesi�czne:

* Dane nie zaktualizuj� si� automatycznie po dodaniu faktury sprzeda�y/zakupu. Nale�y klikn�� przycisk "Od�wie�" znajduj�cy si� w zak�adce "Sprzedaz_mies"/"Zakup_mies".
