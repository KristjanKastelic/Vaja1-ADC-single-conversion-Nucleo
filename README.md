# Vaja1-ADC-single-conversion-Nucleo

Odgovori:

Izbrani ADC pretvornik(i) ima(jo) oznako s trikotnikom. Kaj to pomeni?_da je pin v konfliktu._
Kaj morate storiti, da razrešite to omejitev? Opišite in jo odpravite.
_Odstranimo pine, ki so v konfliktu._


⦁	Razširite (kliknite) razdelek ADC3. Koliko je vseh vhodnih kanalov (seštejte oznake INxx) ?
_4_


⦁	Izberite (obkljukajte) poljuben prosti analogni kanal oz.vhod, ki ga boste porabili za branje vrednosti iz potenciometra. Izbrati morate Single-ended princip zajemanja analogne vrednosti. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? _ADC1_IN3_ .Kateri pin je to? _PC2_


⦁	Pod Configuration  ADC enote gumb v Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
⦁	6, od 0 do 63,
⦁	10, od 0 do 1023,
⦁	12, od 0 do 4095.


Komentar: Velikoproblemovsem imel z kodo. Vkodi sem moral tudi posebaj spremeniti ločlivost pretvorbe na 8 bitno, saj jo je prej zaznavalo kot 12 bitno kljub temu da je bil pod ADC zavihkom nastavljen na 8 bit.
