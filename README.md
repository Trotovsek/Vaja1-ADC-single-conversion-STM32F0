# Vaja1-ADC-single-conversion-STM32F0
Posamična A/D pretvortba




b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni
analogni vhod. Kateri pin je to? Pc0

c) V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? 1

d) Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni?
Pin je zaseden

Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite.
Pin ki je zaseden postavimo na reset state. potem pa na zavihku ADC obkljukamo IN10. sedaj imamo pin pc0, uporabljen kot adc pretvornik.

e) Razširite razdelek ADC. Koliko je vseh vhodnih kanalov?
16

f) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora
usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC_IN10

h) V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej
je območje vrednosti od 0 ÷ 255. Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
a. 12-bitno, od 0 do 4095,
b. 10-bitno, od 0 do 1023,
c. 6-bitno, od 0 do 63.
