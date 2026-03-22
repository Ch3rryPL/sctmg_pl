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
    **SPÓJNOŚĆ** jest sprawdzana na koniec każdej akcji, która zmienia pozycję modeli – obejmuje to **RUCH**, **ROZSTAWIENIE**, **SZARŻĘ**, **ZERWANIE WALKI**, **ZACIEŚNIENIE SZEREGÓW**, **BIEG**, **UMIEŚĆ** oraz **PRZYWOŁANIE**.
    
    Na koniec takiej akcji wszystkie modele w **JEDNOSTCE** muszą znajdować się **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO** i być w stanie wyznaczyć do niego prawidłowy **ŁĄCZNIK SPÓJNOŚCI**. Jeśli ten warunek jest spełniony, **JEDNOSTKA** znajduje się w stanie **SPÓJNOŚCI**.
    
    Pole bitwy rzadko bywa tak łaskawe. Teren i zatłoczone pozycje mogą uniemożliwić modelowi zajęcie legalnej pozycji **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO**. Gdy tak się stanie, należy umieścić dany model tak blisko **MODELU PROWADZĄCEGO**, jak pozwala na to sytuacja. Model musi nadal zachować prawidłowy **ŁĄCZNIK SPÓJNOŚCI**. **JEDNOSTKA** z jednym lub kilkoma modelami umieszczonymi powyżej 3" jest **POZA SPÓJNOŚCIĄ**.
    
    Jeśli model nie może zostać umieszczony w żadnej legalnej pozycji przy jednoczesnym zachowaniu prawidłowego **ŁĄCZNIKA SPÓJNOŚCI**, zostaje on natychmiast usunięty jako **STRATA**.
    
    **JEDNOSTKA**, która znajduje się w **SPÓJNOŚCI**, pozostaje w niej aż do kolejnej akcji zmieniającej pozycję. **STRATY** z dowolnego źródła nigdy nie wyzwalają testu **SPÓJNOŚCI** i nigdy nie powodują, że **JEDNOSTKA** znajdzie się **POZA SPÓJNOŚCIĄ**.
    
    **JEDNOSTKA** jest **POZA SPÓJNOŚCIĄ** tylko wtedy, gdy warunek ten nie został spełniony na koniec jej ostatniej akcji zmiany pozycji. Będąc w **SPÓJNOŚCI**, **JEDNOSTKA** może normalnie kontrolować i spierać się o **ZNACZNIKI MISJI** (zobacz **ROZDZIAŁ** 8.9.1).

    ??? info "ŁĄCZNIK SPÓJNOŚCI"
        Podczas rozmieszczania modeli po ruchu, najpierw należy umieścić **MODEL PROWADZĄCY**. Następnie należy umieszczać pozostałe modele jeden po drugim, **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO**, tak aby mogły wyznaczyć do niego **ŁĄCZNIK SPÓJNOŚCI**.
        
        **ŁĄCZNIK SPÓJNOŚCI** to łańcuch wyobrażonych linii rysowanych od modelu do modelu w ramach tej samej **JEDNOSTKI**. Łączniki nie mogą przechodzić przez modele z innych **JEDNOSTEK**, teren ani luki, przez które sam **MODEL PROWADZĄCY** nie mógłby przejść (zobacz: **PRZEŚWIT**). Łącznik może przechodzić przez wrogie modele, z którymi **JEDNOSTKA** jest aktualnie **ZWIĄZANA WALKĄ**. Każdy model, który nie może znaleźć legalnej pozycji zachowującej **ŁĄCZNIK SPÓJNOŚCI**, zostaje natychast usunięty jako **STRATA**.

    !!! example "Przykład A5: Prawidłowa Spójność"
        W tym przykładzie: **JEDNOSTKA** Marine’ów w stanie **SPÓJNOŚCI**. Wszystkie jej modele znajdują się **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO** (oznaczonego na niebiesko) wraz z **ŁĄCZNIKAMI SPÓJNOŚCI** (oznaczonymi na czerwono) poprowadzonymi od pozostałych modeli do **MODELU PROWADZĄCEGO**. Model Marine’a po lewej łączy się z **MODELEM PROWADZĄCYM** poprzez inny model ze swojej **JEDNOSTKI**, aby ominąć teren blokujący.
    
    !!! failure "Przykład A5: Nielegalne Rozmieszczenie"
        W tym przykładzie: **JEDNOSTKA** Marine’ów z nielegalnym rozmieszczeniem. Wszystkie modele w **JEDNOSTCE** znajdują się **CAŁKOWICIE W ZASIĘGU** 3" od jej **MODELU PROWADZĄCEGO**, ale model za ścianą (oznaczony na czerwono) nie może wyznaczyć **ŁĄCZNIKA SPÓJNOŚCI** do innego modelu ze swojej **JEDNOSTKI** bez przechodzenia przez pokazany teren. Ponieważ model nie może wyznaczyć łącznika bez przechodzenia przez teren zastrzeżony, gracz nie może umieścić modelu w tym miejscu.
    
    ??? info "POZA SPÓJNOŚCIĄ"
        Jeśli jakikolwiek model nie znajduje się **CAŁKOWICIE W ZASIĘGU** 3" od **MODELU PROWADZĄCEGO**, **JEDNOSTKA** jest **POZA SPÓJNOŚCIĄ**. **JEDNOSTKI POZA SPÓJNOŚCIĄ** nie mogą kontrolować ani spierać się o **ZNACZNIKI MISJI** (**ROZDZIAŁ** 8.9.1).

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
