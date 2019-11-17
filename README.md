## Kodifaj - Tasks and Solutions

Baza open-source zadań webdev wraz z przykładowymi rozwiązaniami.

### Dla kogo?

Jeśli dopiero poznałeś HTML i liznąłeś już nieco CSS a w najbliższej przyszłości zamierzasz nauczyć się JavaScriptu.

Jeśli znasz już podstawy JS-a i chcesz podszlifować swoje umiejętności.

Jeśli czujesz się już całkiem dobrze z JS-em, na tyle aby zabrać się za całkiem skomplikowane zadania lub rozpocząć przygodę z frameworkami.

Jeśli chcesz uczestniczyć jako mentor, reviewer, dobra dusza, nauczyciel etc. i pomagać innym w nauce.

Jeśli chcesz uczestniczyć w projekcie open-source niezależnie od swojego poziomu zaawansowania.

Jeśli chcesz nauczyć się obsługiwać Git-a i GitHuba w praktyce wchodząc w interakcję z innymi użytkownikami.

### Motywacja 

Wielu osobom podczas nauki brakuje:

1) jasno określonej ścieżki i ciekawych zadań na ich poziomie zaawansowania, 
2) wiedzy, które zagadnienia są najbardziej kluczowe z perspektywy pracodawcy,
3) umiejętności korzystania z GITa i GitHuba w praktyce,
4) oceny kodu przez bardziej doświadczonych programistów,


### Jak to działa?

Dzięki aplikacji Kodifaj masz możliwość szukania zadań webdev na swoim poziomie. Publikowania rozwiązań i zapraszania do Code Review innych użytkowników. Stawiamy również na naukę gita w bardzo praktycznej formie. Nauczysz się przy okazji tworzyć branche, dodawać pull requesty. Uczestniczyć w całym procesie Code Review od początku do końca. Jest to szalenie istotna umiejętność, która stanowi podstawę pracy każdego programisty. 

### Podstawowe założenia

1) projekt ten stanowi jedyne source of true,
2) aplikacja Kodifaj bazuje na treści zadań i rozwiązań z tego projektu, dodając swoje miary i wskaźniki, których tu brakuje

### Dodawanie nowych zadań

**dla zaawansowanych**

1) forkujemy projekt
2) kopiujemy folder `000_example`
3) zmieniamy `000` na pierwszą wolną liczbę porządkową (np. `007`)
4) zmieniamy `example` na tytuł zadania (np. `login-form`)
5) usuwamy folder `solutions`
6) umieszczamy treść zadania w folderze `007_login-form/task/` w pliku `README.md` najlepiej zarówno w j.polskim (obowiązkowo) i j.angielskim (nice to have)
7) wszelkie dodatkowe pliki (jeśli istnieją i są niezbędne do rozwiązania zadania) umieszczamy w folderze `007_login-form/task/`
8) wykonujemy Pull Request ze zmianą
9) możemy dodać nowe zadanie do aplikacji Kodifaj

PS. commity powinny być zesquashowane

### Dodawanie rozwiązań 

1) tworzymy nowy projekt w swoim repozytorium GitHub -> instrukcja
2) ściągamy projekt lokalnie na dysk
3) kopiujemy treść zadania wraz z ewentualnymi dodatkowymi folderami i plikami do swojego projektu
4) puszujemy do brancha master
5) tworzymy nowy branch o nazwie `develop`
6) rozwiązujemy zadanie (możemy częściowo)
7) pushujemy zmiany do brancha develop
8) robimy Pull Request brancha `develop` do brancha `master`
9) w aplikacji Kodifaj możemy dodać swoje rozwiązanie do zadania i umożliwić innym Code Review swojej zmiany
