# Wype³nianie danych o prowadzonej firmie:

1. W zak³adce "Orygina³" (od faktury) wprowadŸ (patrz obramowane na czerwono miejsca na za³¹czonym obrazku):
- Dane o prowadzonej firmie: nazwa, adres, NIP
- Nazwa miejscowoœci, w której wype³niono fakturê
- Nr rachunku bankowego

![init_1](/ZrzutyEkranu/inicjalizacja_orygina³.jpg 'Inicjalizacja w zak³adce "Orygina³"')

2. W zak³adce "Kreator JPK" wype³ni³ pola (patrz obramowane na czerwono miejsca na za³¹czonym obrazku):
- NIP
- Pe³na nazwa
- Email
- Domyœlny katalog, w którym maj¹ byæ zapisywane wygenerowane pliki JPK

![init_2](/ZrzutyEkranu/inicjalizacja_kreator_jpk.jpg 'Inicjalizacja w zak³adce "Kreator_JPK"')

# W³¹czenie makr:



# Dodawanie nowych klientów:

* NIP nale¿y wpisaæ jako liczba (bez znaków "-")

# Dodawanie nowych dostawców:

* NIP nale¿y wpisaæ jako liczba (bez znaków "-")

# Dodawanie nowych towarów:


# Nowa faktura sprzeda¿y:

* Na jasno-szaro zaznaczone s¹ pola do wype³nienia
* Pod faktur¹ znajduj¹ siê przyciski:
- "Dodaj fakturê do rejestru sprzeda¿y" - przepisuje aktualnie wype³nione pola z faktury do rejestru sprzeda¿y
- "Drukuj kopiê" - przeskakuje do arkusza z kopi¹, otwiera okno drukowania, a po wszystkim wraca z powrotem do zak³adki orygina³u faktury
- "Wyczyœæ fakturê" - czyœci wyszarzone pola (przywraca do domyœlnych ustawieñ np. datê faktury). Pamiêtaj, by przed wyczyszczeniem faktury dodaæ j¹ do rejestru sprzeda¿y!
* Mo¿na obejrzeæ zarejestrowane faktury sprzeda¿y w zak³adce "Sprzeda¿". Niepoprawnie dodan¹ fakturê mo¿na usun¹æ, klikaj¹c prawym przyciskiem myszy po lewej stronie na z³y wiersz i klikaj¹c "Usuñ wiersze".


# Nowy wpis do rejestru zakupu:

* Przewidziano ok. 1000 miejsc
* Na bia³o s¹ zaznaczone pola do wype³nienia. Na szaro s¹ zaznaczone pola, które wype³ni¹ siê automatycznie.

# Generowanie JPK:

1. PrzejdŸ do zak³adki "Kreator_JPK"
2. WprowadŸ datê w wyszarzonym polu pod polem "DataOd". Pole "DataDo" wype³ni siê automatycznie.
Pole "DataWytworzeniaJPK" wype³nia siê aktualn¹ dat¹ (data ostatniego otworzenia dokumentu).
3. Pole pod polem "CelZlozenia" wype³nij we w³asnym zakresie: 0 jest dla pierwotnego dokumentu (w roku 2018).
4. Kliknij w przycisk "Wygeneruj JPK"
5. Wska¿ docelowy folder gdzie ma zostaæ zapisany plik csv.
6. W tym momencie funkcjonalnoœæ tego programu siê koñczy. Wygenerowany plik CSV pos³u¿y do przes³ania JPK aplikacj¹ "Klient JPK 2.0" - udostêpnion¹ przez Ministerstwo Finansów.

# Dane sprzeda¿y/zakupu miesiêczne:

* Dane nie zaktualizuj¹ siê automatycznie po dodaniu faktury sprzeda¿y/zakupu. Nale¿y klikn¹æ przycisk "Odœwie¿" znajduj¹cy siê w zak³adce "Sprzedaz_mies"/"Zakup_mies".
