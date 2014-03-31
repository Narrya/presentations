1. Cześć jestem Kamila Kupidura i witam Was na prezentacji o BDD.

2. Poznajmy się!

3. Kamila to najlepsze imie dla Karotki ;).

4. Baba z Radomia (ale nie ta chytra!).

5. Na śląsk przywędrowała na studia.

6. Skończyłam inżynierię biomedyczną.

7. I założyłam się po szalonej imprezie, że skończę drugi kierunek.

8. Tak skończyłam elektronikę i telekomunikację.

9. Kawałów o kobietach elektronikach jest mniej więcej tyle samo co o kobietach w informatyce.

10. Obecnie pracuje jako QA Engineer, testując i automatyzując aplikacje webowe i mobilne.

11. Tester oprogramowania odpowiada za pewien ustalony poziom jakości dostarczanej aplikacji.

12. Tester często uznawany jest za małpkę-klikacza, ze zdolnościami manualnymi. Powinien jednak być pomysłowym Dobromirem.

13. W klasycznym kaskadowym modelu tworzenia oprogramowania tester otrzymuje gotową aplikację na końcu. Małe pole do manewru, błąd odkryty na końcu kosztuje najwięcej!

14. W podejściu zwinnym, dostarczamy iteracyjnie produkt, kawałek po kawałku klient otrzymuje coraz więcej.

15. Głównym problemem w obu podejściach jest decyzja o rozpoczęciu testów.

16. Oczywiście, jak najwcześniej - tylko w przypadku waterfalla nie ma czego i małpka musi czekać.

17. W podejściu zwinnym, ponieważ dostarczamy produkt kawałek po kawałku i ściśle współpracujemy jako zespół, w każdej iteracji mamy co testować.

18. UCD - projektowanie zorientowane na użytkownika. W pierwszej fazie rozwoju produktu Designer UX pracuje z użytkownikami, tworzy makiety, analizuje żeby przekazać zespołowi rozwijającemu produkt jak najwięcej informacji o odbiorcach, zespół Agile w tym czasie przygotowuje środowisko i sprawdza różne podejścia, narzędzia tworząc np proof of concept. W drugiej fazie można uznąć ze zarówno UX jak i Agile team pracują w równej mierze na sukces projektu. Faza trzecia to wyciszenie pracy UX i mocne rozwijanie produktu od strony implementacyjnej. W ramach tych trzech faz produkt rozwijany jest iteracyjnie i kawałek po kawałku dostarczany jest do odbiorcy.

19. Jednym produktów, który otrzymujemy na wyjściu z UCD jest User Story, czyli historyjka użytkownika.

20. Agata wspominała o przeprowadzonych badaniach użytkowników i wnioskach, że nie chcemy przygotowywać wielkiego przyjęcia, ale tylko kawę dla przyjaciół. W związku z tym, przygotujemy historyjkę dla Kasi, która jest "kawoszem". Historyjki powinny być jak najkrótsze - bardzo często zapisujemy je na małych karteczkach aby zawrzeć tylko esencję. Każda historia zawiera trzy sekcje, które mówią KTO, JAKI MA CEL i PO CO to robi.

21. Każde user story posiada własne kryteria akceptacji, które mówią kiedy dana funkcjonalność zostaje uznana za poprawnie zaimplementowaną. W przypadku kawy wnioski nasuwają się same.

22. Gdy posiadamy historyjkę i kryteria akceptacji możemy automatyzować.

23. Mostem łączącym user story z faktyczną aplikacją jest zautomatyzowany test akceptacyjny. Jedną z form jego zapisu i przygotowania jest Behavior-Driven Development. Jest to przede wszystkim pętla sprzężenia zwrotnego między odbiorcami a zespołem wytwarzającym oprogramowanie, zapisana w języku zrozumiałym dla obu grup. Każdy scenariusz nawiązuje do historyjki użytkownika, jest jednak przygotowany na dużo większym poziomie szczegółowości.

24. Każdy test akceptacyjny jest zapisany w formie kroków, które dzielimy na trzy rodzaje: GIVEN które mówią o ustawianiu stanu wejściowego, występującego przed faktycznym testem, WHEN które definiuje listę operacji niezbędnych do wykonania aby osiągnąć cel zapisany w historyjce, THEN który jest weryfikacją czy dane kryteria akceptacji zostały spełnione.

25. Ale jak to wygląda pod spodem?

26. Każdy z kroków zostaje przechwycony przez framework za pomocą tzw. hooków do odpowiednich słów kluczowych i frazy następującej po nim. I tak dla przykładu widzimy jeden z kroków ustawiających, który został sparametryzowany - opisuje on pewną generyczną akcję, która może zostać wykonana w zależności od parametrów wejściowych.

27. Podobna sytuacja występuje w przypadku frazy WHEN, gdzie również wykonujemy pewną generyczną akcję, tym razem dla dwóch parametrów.

28. Ostatni krok posiada zaimplementowaną pewną logikę, która w tym przypadku weryfikuje odpowiednie kryterium akceptacji związane z jakością przygotowanej kawy, satysfakcjonującą Naszą persone "kawosza".


29. Oczywistym zyskiem z automatyzacji jest przygotowanie siatki testów i inwestycja na przyszłość, gdy system się rozrośnie. W systemie który jest mały, stopień rozbudowania frameworka będzie niewielki i będzie mógł on ewoluować w czasie wraz z iteracyjnie budowaną aplikacją. Zautomatyzowany test możemy nakarmić danymi przygotowanymi w postaci arkusza, minimalizujemy także w ten sposób żmudną i ręczną pracę, oraz mamy możliwość szybkiej weryfikacji i jeśli siatka testów jest odpowiednio rozbudowana pytanie "czy jesteśmy gotowi do wdrożenia" opiera się tylko na zielonym wyniku po odpaleniu testów.


30. Jeśli BDD oraz tematyka kulinarna Was zaciekawiła zapraszam na bloga - znajdziecie tam przepis na sałatkę zapisany w postaci testu akceptacyjnego i pseudokodu.

31. Zainteresowanych praktyką, zapraszam 31 maja na warsztat dot. piramidy testów (skupimy się głównie na BDD i testach akceptacyjnych) który odbedzie się na Quality Excites. Zapisy ruszają lada dzień, zapisy na "call for papers" są również otwarte - do 31 marca.

32. Dziękuję za uwagę!