Witaj! :)

Projekt Guru99 Bank obraca się wokół bankowej aplikacji webowej o tej samej nazwie, która powstała z myślą o testerach oprogramowania, aby mogli oni ćwiczyć swój warsztat w praktyce. Na potrzeby mojej pracy założyłam, że aplikacja jest rzeczywistym produktem, który ma zostać wdrożony na produkcję i wraz z zespołem developerskim jestem odpowiedzialna za budowanie jego jakości.

Aplikacja według specyfikacji biznesowej daje możliwość założenia dwóch typów kont : Manager & Customer. Jednak znajdujemy się w momencie wytwarzania oprogramowania, w którym jeszcze nie dodano możliwości stworzenia konta z uprawnieniami Customera. Dlatego też moja uwaga w testach funkcjnalnych skupia się na 14 istniejących modułach dostępnych dla Managera.


Pracę podzieliłam na dwa etapy:

Etap I odbył się w momencie, kiedy dysponowałam tylko i wyłącznie specyfikacją biznesową.
Obejmuje on więc szczegółową analizę statyczną dokumentacji, której produktami pracy są historyjki użytkownika, przypadki testowe oraz zgłoszenia defektów w JIRA. Na tym etapie zidentyfikowałam również ryzyka produktowe i projektowe, które zostaną uzupełnione o kolejne ryzyka na etapie II.

Etap II odbył się w chwili kiedy oprócz specyfikacji miałam już dostęp do samego produktu czyli aplikacji webowej, na której mogłam wykonać sesję eksploracyjną. Na tym etapie zidentyfikowałam kolejną listę ryzyk a produktami testów były: karta sesji eksploracyjnej, przypadki testowe, zgłoszenia bugów, nagrania testów w Selenium IDE oraz scenariusze testów w metodyce BDD, które przygotowują moje testy pod automatyzację. 

Kolejność artefaktów w repozytorium odzwierciedla kolejność wykonywanych czynności testowych w procesie testowania, z jednym wyjątkiem: ryzyka projektowe i produktowe zidentyfikowane na obu etapach pracy zostały scalone w jedną tabelę.

Enjoy!

