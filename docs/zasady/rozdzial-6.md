# ROZDZIAŁ 6: SYSTEM ZAOPATRZENIA

!!! quote "Odprawa Taktyczna"
    Armie w **StarCraft: Figurkowa Gra Bitewna** nie są rozstawiane natychmiastowo w pełnej sile. Posiłki przybywają falami, a w miarę jak **JEDNOSTKI** odnoszą obrażenia, ich efektywna wielkość rozstawienia maleje. System **ZAOPATRZENIA** zarządza tym procesem, określając, kiedy i w jakiej liczbie gracz może wprowadzać swoje siły do gry.

---

**ZAOPATRZENIE** reprezentuje obecność **JEDNOSTKI** na polu bitwy – jej liczebność, impet oraz zasoby dowodzenia wymagane do podtrzymania jej zdolności bojowej. W przeciwieństwie do stałych cech, **ZAOPATRZENIE** jest dynamiczne: w miarę jak **JEDNOSTKA** ponosi **STRATY**, jej wartość **ZAOPATRZENIA** spada.

??? info "6.1 Profil Zaopatrzenia"
    Każda **KARTA JEDNOSTKI** zawiera w prawym górnym rogu **PROFIL ZAOPATRZENIA**. Łączy on liczbę pozostałych **MODELI** z **AKTUALNĄ WARTOŚCIĄ ZAOPATRZENIA**. 
    
    Gdy tylko **STRATY** spowodują spadek liczby **MODELI** do niższego progu, należy natychmiast zaktualizować **AKTUALNĄ WARTOŚĆ ZAOPATRZENIA**.

    !!! example "Przykład"
        Oddział 9 **MARINE’ÓW** posiada **ZAOPATRZENIE** o wartości 2. Oddział 6 **MARINE’ÓW** posiada **ZAOPATRZENIE** o wartości 1. Po zredukowaniu oddziału do 3 **MODELI**, jego **ZAOPATRZENIE** spada do 0.

!!! note "NOTKA PROJEKTANTA"
    **ZAOPATRZENIE** jest sercem warstwy strategicznej gry. Bezpośrednie powiązanie obecności bojowej **JEDNOSTKI** z liczbą pozostałych **MODELI** oznacza, że każdy utracony **MODEL** niesie ze sobą konsekwencje wykraczające poza zwykłe obrażenia. Jest to wybór taktyczny: czy zachować **JEDNOSTKĘ** dla jej siły ognia, czy poświęcić ją, aby zwolnić **ZAOPATRZENIE** dla nowej **JEDNOSTKI** z **REZERW**?

??? info "6.2 Zastosowanie Zaopatrzenia"

    ### ROZSTAWIENIE
    Każda misja określa **PULĘ ZAOPATRZENIA**, czyli maksymalną wartość **ZAOPATRZENIA**, jaka może znajdować się na polu bitwy w danym momencie. 

    * **PULA ZAOPATRZENIA** zaczyna się od wartości podanej na **KARCIE MISJI** i zwiększa się o wartość **ESKALACJI ZAOPATRZENIA** na początku każdej kolejnej Rundy.
    * Gracz może wprowadzić **JEDNOSTKĘ** do gry z **REZERW** tylko wtedy, gdy jej koszt mieści się w granicach **DOSTĘPNEGO ZAOPATRZENIA**. 
    * **DOSTĘPNE ZAOPATRZENIE** to aktualna wartość **PULI ZAOPATRZENIA** minus całkowite **ZAOPATRZENIE** wszystkich przyjaznych **JEDNOSTEK** znajdujących się już na polu bitwy.
    * W ostatniej Rundzie gry **PULA ZAOPATRZENIA** jest nieograniczona.

    ### KONTROLA ZNACZNIKÓW MISJI
    **ZAOPATRZENIE** określa, kto kontroluje dany teren. Aby ustalić kontrolę nad **ZNACZNIKIEM MISJI**, każdy gracz oblicza **AKTUALNĄ WARTOŚĆ ZAOPATRZENIA** wszystkich swoich uprawnionych **JEDNOSTEK** spierających się o ten znacznik. 
    
    * Pod uwagę bierze się sumę ich **ZAOPATRZENIA**, a nie liczbę **MODELI**. 
    * **ZNACZNIK** kontroluje gracz z najwyższą sumą.
    * **JEDNOSTKA**, która jest **POZA SPÓJNOŚCIĄ**, nigdy nie może kontrolować ani spierać się o **ZNACZNIK MISJI**.

    ### MASA TAKTYCZNA
    **JEDNOSTKA**, która wykonuje **ZERWANIE KONTAKTU**, otrzymuje surową karę: nie może strzelać ani wykonywać **SZARŻY** w następnej **FAZIE NATARCIA**. 

    Jeśli jednak **AKTUALNE ZAOPATRZENIE** **JEDNOSTKI** wykonującej **ZERWANIE KONTAKTU** przewyższa połączone **ZAOPATRZENIE** wszystkich wrogów, z którymi była ona **ZWIĄZANA WALKĄ**, kara ta jest ignorowana. Przeważająca siła posiada masę pozwalającą na czyste wycofanie się.

    ### POCZĄTKOWE ZAOPATRZENIE JEDNOSTKI
    Niektóre **KARTY MISJI** przyznają **PUNKTY ZWYCIĘSTWA** równe wartości wrogiego **ZAOPATRZENIA** zniszczonego w danej Rundzie. Wartość ta jest dodawana do wyniku podczas Fazy Punktacji.
