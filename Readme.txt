Za�arovan� les

Ovl�d�n�
F5 - Ulo�en� hry (funk�n� pouze p�i pohybu na map�)
F9 - Na�ten� hry (funk�n� v ka�d� f�zi hry)
Kurzorov� �ipky - Pohyb po map�
My� - LTM na tla��tka

Mapy
Pro hru se daj� vytv��et vlastn� mapy, sta�� vlo�it soubor do slo�ky mapy ve tvaru mapa(x).csv (bez z�vorek, kde x je ��slo mapy)
P�i spu�t�n� nov� hry si hra automaticky projde mapy od mapa1 po mapax. P�i ukl�d�n� hry se data mapy ukl�daj� tak�e i kdy� mapy ve slo�ce zm�n�me hra bude vych�zet z na�ten�ch dat.

Hern� mapy maj� velikost 12x12 pol��ek.
jednotliv� pol��ka odd�l�me st�edn�kem a nebo nov�m ��dkem pokud u� jsme u 12. pol��ka ��dku
Ka�d� mapa by m�la obsahovat po��te�n� pozici hr��e. Hra za��n� na prvn� map� (mapa1.csv)

0 = nic (tr�va)
1 = k�men (pevn� objekt)
2 = strom (pevn� objekt)
3 = hr�� (po��te�n� pozice hr��e na dan� map�)
4 = dve�e do dal�� mapy (mapa(x+1).csv)
5 = dve�e do p�edchoz� mapy (mapa(x-1).csv)
6 = jednoduch� soupe�
7 = st�edn� t�k� soupe�
8 = t�k� soupe�
9 = lahvi�ka zdrav�
10 = lahvi�ka mana
11 = dve�e konec hry (posledn� dve�e, kter� ukon�� hru)

