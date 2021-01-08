# Vaja6-ADC-scan-mode-conversion-Nucleo
Določil sva tri analogne vhode za kanale IN1, IN2, IN3 za zunanje potenciometre kot Single-ended vhod. To so pini PC0, PC1 in PC2.
Poleg pinov se izpiše ADC_IN1, ADC_IN2 in ADC_IN3.
Clock Prescaler sva nastavila tako, da je izračunana frekvenca vzorčenja 4 MHz. Izbrana vrednost parametra je Asynchronous clock mode divided by 4.
Privzeta vrednost paramtera Number of Conversion je 1.
Čas vzorčenja v mikrosekundah je 26,153 μs.
Kratica DMA pomeni Direct Memory Access.
Vaja nam omogoča branje ADC pretvorbe na več kanalih sočasno v scan mode načinu. Za tak prikaz ADC pretvorbe sva uporabila tri potenciometre in NUCLEO-L476RG. Najprej sva v STM32CubeIDE brala potenciometre v debug načinu. V tem načinu branja nisva bila čisto zadovolna s prikazom podatkov saj niso bili čisto natančni, zato sva podatke vnesela v STM32CubeMonitor, kjer so bili podatki pregledni in natančno prikazani. Hitrost branja podatkov pa je bila za naju dobra tako v STM32CubeID kot v STM32CubeMonitor.
