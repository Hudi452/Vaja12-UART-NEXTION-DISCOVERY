# Vaja12-UART-NEXTION-DISCOVERY

ODGOVORI NA VPRAŠANJA:\
2. d) objectname = z0\
g) objectname = b0\
3. b) zelena LED: PD12\
modra LED: PD15\
c) RX: PA10\
TX: PA9\
RX pin na STM-u moramo povezati s TX pinom na Nextion zaslonu in obratno. RX pin namreč sprejema podatke, medtem ko TX pin pošilja podatke.\
d) PC0: kanal IN10\
4. e) Gre za enojno/single ADC pretvorbo.\
Tabela ASCII:\
ASCII znak:  Dvojiško:  Šestnajstiško:  Desetiško:\
    0        0011 0000        30            48\
    1        0011 0001        31            49\
    2        0011 0010        32            50\
    3        0011 0011        33            51\
    4        0011 0100        34            52\
    5        0011 0101        35            53\
    6        0011 0110        36            54\
    7        0011 0111	      37            55\
    8        0011 1000        38            56\
    9        0011 1001        39            57\

PINOUT KONFIGURACIJA:\
![konfig](https://github.com/Hudi452/Vaja12-UART-NEXTION-DISCOVERY/blob/main/Pinout_konfiguracija.PNG)
