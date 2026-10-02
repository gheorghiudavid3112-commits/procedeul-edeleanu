# Procedeul Edeleanu 2.0

Consumul unui campus școlar, separat după timp, fără niciun senzor montat.

**[Deschide aplicația](https://gheorghiudavid3112-commits.github.io/procedeul-edeleanu/)**: rulează în browser, fără cont și fără instalare.

Proiect pentru TeChallenge 2026, tema 3, „Energia inteligentă”.
Autor: Gheorghiu David-Alexandru, clasa a XI-a J, Liceul Tehnologic „Lazăr Edeleanu”, Ploiești.
Coordonator: prof. Dumitru Cristian-Adelin.

## Ideea

În 1908, Lazăr Edeleanu a inventat un procedeu prin care componentele țițeiului se separă fără să fie distruse. Proiectul face același lucru cu energia liceului care îi poartă numele.

Pe campus sunt școala, cu laboratoarele și sala de sport, căminul, cantina și atelierele, adică patru ritmuri de consum diferite, plus iluminatul exterior. Toate trec printr-un singur contor. Factura spune cât s-a consumat, dar nu și ce. Contorul inteligent înregistrează însă consumul oră cu oră, iar aplicația separă această curbă în componentele care o formează. Nu o face după semnătura electrică a aparatelor, imposibil de citit din valori orare, ci după timp: orarul, tipul zilei, vacanțele, răsăritul și apusul.

## Ce se poate încerca în aplicație

- **Separarea curbei**: cele șase componente și cele trei tipuri de zi, la aceeași scară.
- **Iluminatul pe un an**: programul fix al lămpilor, comparat zi cu zi cu apusul și răsăritul.
- **Costuri și amortizare**: schimbi prețul energiei, iar tabelul măsurilor se recalculează.
- **Validarea**: exemplul numeric și lista cu ce ar infirma proiectul.
- **Testul algoritmului**: un an generat, cu o anomalie ascunsă, nou la fiecare apăsare. Merge și cu un fișier CSV real, care nu pleacă din browser.
- **Planul de 30 de zile**: pașii, cine îi face și ce se verifică la fiecare.

## Cifrele

Datele sunt modelate, nu măsurate. Curba de sarcină reală a liceului nu a putut fi obținută, așa că profilul a fost construit din datele reale ale campusului. Pe acest model, campusul consumă 421 MWh pe an. Patru măsuri ar economisi 50,0 MWh (11,9%), adică 64.848 lei pe an la 1,30 lei/kWh, pentru o investiție de 5.200 lei recuperată în 29 de zile. Metoda rulează fără modificări pe curba reală a oricărei școli.
