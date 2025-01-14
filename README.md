Copyright (c) 2025 Alex Daniel @ https://github.com/A13xTheITGuy

# Proiect AC Operatia AND 16 biti IS Anul 2

  Acest circuit efectuează operația „ȘI” între două numere de 16 biți fiecare. Circuitul are 4 cicluri de tact, iar operația „ȘI” este finalizată la sfârșitul celor patru tacte. După aceasta, se generează următoarele două numere care vor fi utilizate pentru operația următoare, iar procesul continuă astfel.
  Circuitul este foarte complex, având un număr mare de componente, cum ar fi: registre de memorie, selectoare de date, generatoare de cuvinte (Word Generators), decodificatoare, numărător pe 4 biți etc. De asemenea, circuitul include mai multe switch-uri, precum: MEM Chip Select Mode, MEM ACTIVE, MEM Mode, CLK ACTIVE.

MEM Mode

- Dacă MEM Mode = 0 / LOW, atunci la următoarea operație, primul și al doilea număr vor fi cele generate de generatoarele de cuvinte.
- Dacă MEM Mode = 1 / HIGH, atunci la următoarea operație, primul număr va fi rezultatul operației anterioare (rezultatul setului anterior), iar al doilea număr va fi generat de Word Generator pentru al doilea număr.
