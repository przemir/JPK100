# JPK100

Program jest przystosowany pod rok 2018.

Dostosowany jest pod mikroprzedsiębiorców.

Działa pod OpenOffice. Makra nie będą działać w Excel'u.

Zawiera:
- Szablon faktury
- Rejestr sprzedaży - gdzie dane wstawiane są bezpośrednio z szablonu faktury
- Rejestr zakupów
- Generator JPK

Program jest udostępniony na licencji LGPL.
Oznacza to, że można go pobrać i dostosować do swoich potrzeb.
Nie ma obowiązku publikowania swoich zmian. Jeżeli jednak takie zmiany zostaną opublikowane/przekazane dalej, to wolno to zrobić tylko na licencji LGPL (lub GPL).
Generowany przez program JPK w postaci pliku csv jest wynikiem programu, a nie jego częścią, zatem nie podlega żadnej licencji.

Makra
W celu przyspieszenia niektórych czynności, arkusz zawiera makra:
* makro generujące kwotę podaną słownie
* makro czyszczące fakturę
* makro drukujące kopię faktury
* makro przepisujące dane z faktury do rejestru sprzedanych faktur
* makro generujące JPK do pliku csv.

Arkusz w domyśle będzie przechowywał w sobie dane sprzedaży, zakupów, towarów, klientów i dostawców. Dobrym pomysłem może być zatem zabezpieczenie pliku.

Liczby przewidzianych faktur kupionych jest ograniczona do 1000 wpisów rejestru zakupu (z przyczyn technicznych - znając działanie OpenOffice można ten limit podnieść na tyle ile dana osoba uważa za stosowne). Nic nie stoi jednak na przeszkodzie, by przechowywać rejestr zakupu i sprzedaży na jeden rok (a kolejne dane w innym pliku programu). Na dłuższy okres niż rok to i tak może nie mieć sensu bo znając życie za rok jakieś kolumny do JPK mogą zostać dodane/usunięte...

Program nie wykona sprawdzenia poprawności danych.

Program jest rozpowszechniony w nadziei, że będzie przydatny, ale bez jakiejkolwiek gwarancji.

