# ROZDZIAŁ 4: POMIAR I RUCH

!!! quote "Odprawa Taktyczna"
    Pozycjonowanie to podstawa. Kilka cali może stanowić różnicę między zabójczą szarżą z flanki a odsłoniętą **JEDNOSTKĄ** złapaną na otwartym terenie. W tym **ROZDZIALE** przyjrzymy się, jak obliczane są odległości, w jaki sposób **MODELE** poruszają się po polu bitwy oraz poznamy kluczowe zasady dotyczące spójności, związania walką i wysokości.

---

??? info "4.1 Pomiar odległości"
    Wszystkie odległości mierzone są w calach (") przy użyciu miarki lub linijki. Gracze mogą mierzyć dowolną odległość w dowolnym momencie – nie ma żadnych ograniczeń dotyczących mierzenia wstępnego.

    * **Pomiędzy Modelami**: Odległość mierzy się od najbliższego punktu podstawki jednego **MODELU** do najbliższego punktu podstawki drugiego **MODELU**.
    * **Ignorowanie elementów wystających**: Bronie, skrzydła, kończyny oraz elementy dekoracyjne wystające poza krawędź podstawki są ignorowane.
    * **Kontakt Podstawka-do-Podstawki**: Jeśli dwie podstawki fizycznie się dotykają, odległość wynosi 0".
    * **Wysokość**: Obliczając odległość między **MODELAMI** na różnych wysokościach, należy zawsze mierzyć ją poziomo (**Perspektywa Top-Down**). Pionowa różnica wysokości jest ignorowana przy sprawdzaniu zasięgu broni, **ZASIĘGU ZWARCIA** oraz zasięgów zdolności.

    

    !!! example "Przykłady Pomiaru"
        * **Na płaskim terenie**: Odległość mierzona od najbliższych punktów obu podstawek.
        * **Do terenu**: Odległość mierzona od najbliższego punktu podstawki do najbliższej krawędzi elementu terenu.
        * **Różnica wysokości**: Pomiar od **MODELU** na **WYSOKIM TERENIE** do celu na **POZIOMIE GRUNTU** jest wykonywany poziomo, ignorując pionową odległość.

??? info "4.2 W Zasięgu vs. Całkowicie w Zasięgu"
    * **W ZASIĘGU (WITHIN)**: **MODEL** znajduje się **W ZASIĘGU**, jeśli dowolna część jego podstawki dotyka lub wykracza poza tę granicę. **JEDNOSTKA** znajduje się **W ZASIĘGU**, jeśli co najmniej jeden jej **MODEL** spełnia ten warunek.
    * **CAŁKOWICIE W ZASIĘGU (WHOLLY WITHIN)**: **MODEL** znajduje się **CAŁKOWICIE W ZASIĘGU**, tylko jeśli cała jego podstawka mieści się wewnątrz zakresu. **JEDNOSTKA** spełnia ten warunek tylko wtedy, gdy podstawki wszystkich jej **MODELI** znajdują się wewnątrz zakresu.

    

    !!! example "Przykład: Marine i Zerglingi"
        Marine mierzy 3" od swojej podstawki.
        * Zergling A ma całą podstawkę wewnątrz: jest **CAŁKOWICIE W ZASIĘGU**.
        * Zergling B ma tylko krawędź podstawki wewnątrz: jest **W ZASIĘGU**.
        * Zergling C jest poza 3": jest poza zasięgiem.
        * Cała **JEDNOSTKA** Zerglingów jest uważana za będącą **W ZASIĘGU**, ale nie **CAŁKOWICIE W ZASIĘGU**.

??? info "4.3 Model Prowadzący"
    **MODEL PROWADZĄCY (LEADING MODEL)** to tymczasowy punkt odniesienia dla ruchu całej formacji. Jest wyznaczany każdorazowo podczas akcji **RUCHU**, **BIEGU**, **SZARŻY**, **ZERWANIA KONTAKTU** lub **ZACIEŚNIENIA SZEREGÓW**.

    1.  Wybierz jeden **MODEL** jako **PROWADZĄCY**.
    2.  Porusz go, mierząc dokładnie jego ścieżkę.
    3.  Umieść pozostałe **MODELE** w prawidłowej **SPÓJNOŚCI** wokół jego nowej pozycji.
    4.  Status **MODELU PROWADZĄCEGO** wygasa po zakończeniu akcji.

??? warning "4.4 Spójność jednostki"
    **SPÓJNOŚĆ** jest sprawdzana na koniec każdej akcji zmieniającej pozycję (np. **RUCH**, **SZARŻA**, **UMIEŚĆ**, **PRZYWOŁANIE**).

    * **Warunek**: Wszystkie **MODELE** w **JEDNOSTCE** muszą znajdować się **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO** i posiadać prawidłowy **ŁĄCZNIK SPÓJNOŚCI**.
    * **ŁĄCZNIK SPÓJNOŚCI**: To łańcuch wyobrażonych linii od **MODELU** do **MODELU**. Łączniki nie mogą przechodzić przez inne **JEDNOSTKI**, teren nieprzejezdny ani luki zbyt wąskie dla **MODELU PROWADZĄCEGO**.
    * **Konsekwencje**: **MODEL**, który nie może zachować **ŁĄCZNIKA SPÓJNOŚCI**, zostaje usunięty jako **STRATA**. **JEDNOSTKA** **POZA SPÓJNOŚCIĄ** nie może kontrolować ani spierać się o **ZNACZNIKI MISJI**.

    !!! note "Pamiętaj"
        **STRATY** (np. od ostrzału) nigdy nie wyzwalają testu **SPÓJNOŚCI** w trakcie tury. Test następuje dopiero po kolejnej akcji ruchu **JEDNOSTKI**.

??? info "4.5 Bezpośrednio w stronę i Bezpośrednio od"
    Niektóre zdolności wymuszają ruch po linii prostej łączącej środki podstawek dwóch **MODELI**.

    * Jeśli teren blokuje ścieżkę, **MODEL** omija przeszkodę najkrótszą drogą, a następnie kontynuuje ruch w oryginalnym kierunku.
    * **Ruch w stronę**: Nie można zakończyć ruchu dalej od celu, niż się go rozpoczęło.
    * **Ruch od**: Nie można zakończyć ruchu bliżej celu, niż się go rozpoczęło.
    * **Wielomodelowe Jednostki**: **MODELEM PROWADZĄCYM** musi być ten, który ma najkrótszą drogę do celu (przy ruchu "w stronę") lub najdłuższą drogę ucieczki (przy ruchu "od").

    

??? note "4.6 Prześwit i rozmiar modelu"
    Możliwość przejścia przez luki zależy od **ROZMIARU** **JEDNOSTKI**:

    * **ROZMIAR 2 lub mniejszy**: Może przechodzić przez luki o szerokości co najmniej **1 cala**.
    * **ROZMIAR 3 lub większy**: Wymaga luki o szerokości co najmniej **3 cali**.

    Niezależnie od **PRZEŚWITU**, **MODEL** nigdy nie może zakończyć ruchu w miejscu, w którym jego podstawka fizycznie się nie mieści. Przejścia łukowe i drzwi w terenie są traktowane jako luki dla potrzeb tej zasady.
