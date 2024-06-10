# informatyka_projekt_2
WtyczkaNaZajeciachDialog
  Jest to wtyczka dla programu QGIS, która służy do wykonywaia różnych zadań związanych z analizą danych przestrzennych. Wtyczka ta dostarcza interfejs graficzny(GUI) użytkownika, który pozwala na interakcję z funkcjonalnościami wtyczki.
# INSTALACJA
  Instrukcja intstalacji wtyczki:
  1. Otwórz oprogramowanie QGIS.
  2. Przejdź do menu ''Wtyczki'' i wybierz ''Zarządzaj i instaluj wtyczki''
  3. Nastepnie przejdź do zakładki ''Ustawienia'' i kliknij przycisk       ''Dodaj''   w celu dodania nowego repozytorium.
  4. Wprowadź nazwę repozytorium (dla przykładu.:"WtyczkaNaZajęciah") oraz podaj adres URL: [repository_url].
  5. Zapisz nowe repozytorium.
  6. Wejdź do zakładki ''Wtyczki'' i wyszukaj ''WtyczkaNazajęciah'' w pasku wyszukiwania.
  7. Wybierz wtyczkę, klikając na jej nazwę i zainstaluj.
  8. Po instaalcji dostęp można uzyskać wchodząc w menu ''Wtyczki''.
# OBSŁUGA WTYCZKI 
  Po zainstalowaniu wtyczki w QGIS można korzystać z jej wszelkich funkcji za pomocą interfejsu graficznego tj. GUI. Taki interfejs udostępnia poniższe przyciski:
  1. 'POLICZ\' - przycisk liczy liczbę wybranych obiektów w bieżącej warstwie, a następnie wyświetla liczbę w etykiecie.
  2. 'WSPÓŁRZĘDNE PUNKTÓW\' - przycisk ten wyświetla współrzędne wszytskich zaznaczonych plików, punkty wyświetlane są w układzie zdefiniowanym przez warstwę.
  3. 'RÓŻNICA WYSOKOŚCI\' - przycisk ten oblicza rożnicę wysokości między dwoma wybranymi punktami w bieżącej warstwie i wyświetla wynik w oknie dialogowym. Funkcja ta działa tylko gdy punkt posiada atrybut 'H_PLEVRF20'. Różnica wysokości zwracana jest w metrach.
  4. 'POLE\' - przycisk ten oblicza powierzchnię wielokąta utworzonego przez wybór wielu punktów w bieżącej warstwie za pomocą metody Gaussa. Powierzchnia jest wyświetlana w oknie dialogowym, a jednostką wyświetlanej wartości jest metr kwadratowy.
# WYMAGANIA
  - Python 3.11.5
  - biblioteki math oraz PyQt 5
  - QGIS 3.34.7
# SYSTEM OPERACYJNY
  - Windows 11
