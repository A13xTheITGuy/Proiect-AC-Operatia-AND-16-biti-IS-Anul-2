Copyright (c) 2024 Alex Daniel @ https://github.com/A13xTheITGuy

# Proiect-AC-Operatia-AND-16-biti-IS-Anul-2

  Acest circuit face operatia de "si" intre doua numere de 16 biti fiecare. Circuitul are 4 cicluri de tact, operatia "si" fiind finalizata la finalul celor patru tacte, iar ulterior se genereaza urmatoarele doua numere pe care le vom folosi pentru urmatoarea operatie, si tot asa.
  Circuitul este foarte complex, avand un numar mare de componente folosite (Registre de memorie, Selectori de date, Word Generator-uri, Decodificator, Numarator pe 4 biti etc.).
  De asemenea, circuitul are mai multe switch-uri precum: MEM Chip Select Mode, MEM ACTIVE, MEM Mode, CLK ACTIVE.
    
  MEM Mode
  - Daca avem MEM Mode = 0 / LOW , atunci la urmatoarea operatie primul si al doilea numar vor fi cele generate de Word Generate-uri.
  - Daca avem MEM Mode = 1 / HIGH , atunci la urmatoarea operatie primul numar va fi rezultatul operatiei initiale ( rezultatul operatiei setului anterior ) si al doilea numar va fi numarul generat de Word Generater-ul pentru al doilea numar.
