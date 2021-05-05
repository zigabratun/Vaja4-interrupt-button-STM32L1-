2b) V Pinout % Configuraton pogledu glede na vašo razvojno ploščico ugotovite, ali lahko uporabite modro tipko za digitalni vhod kot interrupt (GPIO_EXT…). Če da, kateri pin je to?: PA0 (GPIO EXIT0) 

2c) Zapišite naslov izhodnih pinov za zeleno in modro LED: ZELENA LED: LD3 (PC9) in MODRA LED: LD4 (PC8)__

4a)Kaj se zgodi, ko pritisnemo na modro tipko na STM32L1? Ob pritisku modre tipko se prižiga in ugaša zelena LED dioda. Modra led dioda pa vedno utripa s frekvenco 1 Hz. 

4b)Ali pritisk na modro tipko vpliva na utripanje modre LED in zakaj?Pritisk na modro tipko ne vpliva na utripanje modre LED, ker smo nastavili interrupt na tipko.
