# ROZDZIAŁ 7: POLE BITWY

!!! quote "Odprawa Taktyczna"
    Teren, na którym toczona jest bitwa, jest równie ważny jak walczące armie. Ściany blokują linię wzroku, wysokość zapewnia dominujące pole ostrzału, a wąskie przejścia mogą skierować cały atak w strefę śmierci. Ten **ROZDZIAŁ** opisuje, jak działa **LINIA WZROKU**, jak teren wpływa na modele o różnych rozmiarach oraz jak osłona i wysokość wpływają na przebieg walki.

---

### 7.1 Linia Wzroku

Każdy strzał, każda zdolność i każdy rozkaz wymagający czystego widoku na cel podlega tej samej procedurze. **LINIA WZROKU** określa, co model widzi, a co za tym idzie – do czego może strzelać.



??? info "Zasady Celowania"
    **StarCraft: Gra Figurkowa** korzysta z dwuwymiarowego systemu **LINII WZROKU** (LoS). Wszystkie testy są rozstrzygane z perspektywy rzutu z góry, patrząc bezpośrednio na pole bitwy z wysoka.
    
    * **Procedura**: Należy poprowadzić wyobrażoną linię prostą od dowolnej części podstawki modelu wykonującego akcję do dowolnej części podstawki modelu celu.
    * **Widoczność**: Jeśli linia nie przechodzi przez żaden **TEREN BLOKUJĄCY** (rozmiar 2 lub większy), cel jest **WIDOCZNY**.
    * **Przeszkody**: Jeśli linia przechodzi przez **TEREN BLOKUJĄCY**, należy sprawdzić zasady **OSŁONY**. Luki, okna i otwory drzwiowe nie blokują linii – jedynie solidne sekcje elementu terenu stanowią przeszkodę.

!!! note "NOTKA PROJEKTANTA"
    Nasza gra korzysta z metody **LINII WZROKU** rzutu z góry, a nie rzeczywistego pomiaru z poziomu oczu modelu. Pozwala to uniknąć kłótni o dokładną pozę czy ustawienie broni, gwarantując szybkość i balans rozgrywki.

??? info "7.1.2 Osłona"
    Element terenu zapewnia **OSŁONĘ** na jeden z dwóch sposobów:

    * **PEŁNA OSŁONA**: Teren blokuje widok, jeśli jego **EFEKTYWNY ROZMIAR** jest równy lub większy niż **EFEKTYWNY ROZMIAR** zarówno Atakującego, jak i Celu.
    * **BEZPOŚREDNIA OSŁONA**: Jeśli linia pomiaru przechodzi przez teren, a Atakujący lub Cel znajduje się **W ZASIĘGU** 1 cala od niego, widok jest zablokowany – pod warunkiem, że rozmiar terenu jest równy lub większy niż rozmiar tego modelu.

    !!! warning "Ważne"
        Każdy element terenu jest oceniany niezależnie. Jeśli żaden pojedynczy element nie spełnia wymogów, **LINIA WZROKU** nie jest zablokowana, niezależnie od liczby przeszkód na drodze.

??? note "Sytuacje Specjalne"
    * **MARTWA STREFA WYSOKOŚCI**: Jeśli model na **WYSOKIM TERENIE** (rozmiar 3+) mierzy do celu na **POZIOMIE GRUNTU**, który znajduje się **W ZASIĘGU** 1 cala od podstawy tego terenu, widok jest zablokowany w obu kierunkach.
    * **BLISKI KONTAKT**: Jeśli oba modele są **W ZASIĘGU** 1 cala od tego samego terenu i **W ZASIĘGU** 3 cali od siebie, powyższe blokady nie obowiązują – widzą się normalnie.

### 7.1.4 Pionowość i Efektywny Rozmiar

Gdy model stoi na szczycie elementu terenu, jego **EFEKTYWNY ROZMIAR** jest równy sumie **ROZMIARU** modelu i **ROZMIARU** terenu.



!!! tip "WSKAZÓWKA ABATURA"
    **WYSOKI TEREN** to potęga. Gdy **JEDNOSTKA** znajduje się na wzniesieniu (Rozmiar 3 lub 4), jej **EFEKTYWNY ROZMIAR** drastycznie rośnie, pozwalając zaglądać ponad barierami. Najlepszym miejscem na wykorzystanie wysokości jest wsparcie dystansowe. Pamiętaj jednak: jesteś widoczny dla niemal każdego na stole.

??? info "7.1.5 Osłona Wysokiego Terenu"
    Jeśli wszystkie modele **JEDNOSTKI** znajdują się **CAŁKOWICIE W ZASIĘGU** **WYSOKIEGO TERENU** (rozmiar 3+), zyskują one prawo do wykonania **RZUTU NA UNIK** przeciwko atakom dystansowym z dołu.

---

### 7.2 Związanie Walką i Zasięg Zwarcia

**ZASIĘG ZWARCIA** rozciąga się na 1 cal w poziomie od podstawki modelu. Gdy dwa wrogie modele znajdują się w tej odległości, są **ZWIĄZANE WALKĄ**.

??? warning "Ograniczenia Związania"
    Modele są **ZWIĄZANE WALKĄ** tylko wtedy, gdy:
    * **TAGI BOJOWE** są zgodne: Modele **NAZIEMNE** wiążą tylko **NAZIEMNE**. Modele **LATAJĄCE** nie mogą zostać **ZWIĄZANE WALKĄ**.
    * **Teren nie blokuje**: Teren o rozmiarze 2 lub większym uniemożliwia związanie.
    * **Poziomy są zgodne**: Modele na **WYSOKIM TERENIE** nie wiążą tych na dole (i odwrotnie), chyba że walczą przez **PUNKT DOSTĘPOWY**.

---

### 7.3 Znaczniki i żetony

W grze rozróżniamy dwa typy fizycznych elementów pomocniczych:

* **ŻETONY (TOKENS)**: Namacalne zasoby (np. Guzy Biomasy). Są traktowane jak teren o rozmiarze 0. Modele nie mogą kończyć na nich ruchu.
* **ZNACZNIKI (MARKERS)**: Służą do śledzenia statusów (np. **ZNACZNIKI MISJI**, **AKTYWACJI**). Nie blokują ruchu ani widoku.

!!! note "Znaczniki Kluczowe"
    * **ZNACZNIK PIERWSZEGO GRACZA**: Śledzi inicjatywę.
    * **ZNACZNIKI MISJI**: Określają cele bitwy; mają średnicę 32 mm.

---

### 7.4 Zniszczone jednostki

Gdy padnie ostatni model, **JEDNOSTKA** zostaje **ZNISZCZONA**. Wszystkie efekty, wzmocnienia i osłabienia z nią związane natychmiast wygasają. **ZNISZCZONA JEDNOSTKA** nie może wrócić do gry, chyba że zasada mówi inaczej.
