# Text k bakalářské práci

V tomto repozitáři se nachází text k bakalářské práci "Metoda pohyblivých vážených čtverců v jazyce Julia".

## Návod ke čtení zdrojáků

Ve složce `src` nás zajímají soubory `*.tex`. Hlavním rozcestníkem je soubor `bakalarska-prace.tex`, ve kterém jsou přiincludované styly a jednotlivé kapitoly. Kapitoly jsou zpravidla includované příkazem `\input nazev-souboru.tex`. Své styly mám v souboru `src/tungstyl.tex`.

## Návod ke kompilaci
Ve složce `src` stačí zavolat příkaz `make`. Výsledné pdf se bude jmenovat `bakalarska-prace.pdf` a bude se nacházet ve složce `build`.
