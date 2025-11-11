# MHD
Webový informační systém určený pro správu jízdních řádů, spojů, vozidel a řidičů městské hromadné dopravy v Brně. 
Umožňuje efektivní plánování provozu, sledování spojů a poskytování aktuálních informací cestujícím.

## Cíl systému a cílová skupina

Cílem systému je zefektivnit řízení a organizaci městské dopravy v Brně a zlepšit informovanost cestujících.
Systém je určen pro tři hlavní skupiny uživatelů:

Dispečeři dopravního podniku – plánování jízd, přidělování vozidel a řidičů, sledování aktuálního provozu.

Řidiči – přehled svých směn, vozidel a tras.

Cestující veřejnost – online přístup k jízdním řádům, aktuálním zpožděním a výlukám.

Problémy, které systém řeší:

složité plánování spojů a směn,

špatná komunikace při změnách provozu,

zpožděné nebo nepřesné informace pro cestující.

## Základní funkce (Role a oprávnění)

Administrátor (Dopravní podnik Brno)

Spravuje seznam vozidel (typ, kapacita, stav, SPZ).

Přidává a aktualizuje linky a trasy.

Spravuje seznam zaměstnanců (řidiči, dispečeři).

Nastavuje jízdní řády a plán směn.

### Dispečer

Sleduje aktuální stav spojů (v provozu / zpožděn / mimo provoz).

Přiděluje řidiče k vozidlům a trasám.

Zaznamenává mimořádnosti (porucha, výluka, dopravní nehoda).

Může dočasně měnit jízdní řády.

### Řidič

Vidí své směny, přidělené vozidlo a trasu.

Potvrzuje přítomnost a začátek služby.

Může nahlásit technický problém nebo zpoždění.

### Cestující

Vyhledává spoje podle zastávky nebo linky.

Získává aktuální informace o zpoždění a výlukách.

Může si nastavit oblíbené trasy nebo sledované zastávky.

## Spravovaná data (Příklady)

Linky – číslo linky, trasa, typ (tramvaj, autobus, trolejbus).

Zastávky – název, GPS poloha, seznam linek, které zde zastavují.

Jízdní řády – časy odjezdů, intervaly, platnost.

Vozidla – typ, registrační značka, kapacita, technický stav.

Řidiči – jméno, ID, kvalifikace, rozpis směn.

Zpoždění a mimořádnosti – důvod, čas, trvání, dotčené linky.

Uživatelé (cestující) – volitelné účty s oblíbenými trasami a notifikacemi.

## Možné rozšíření systému

Mobilní aplikace pro cestující (zpoždění v reálném čase, notifikace o výlukách).

API pro napojení na web města Brna nebo Google Maps.

Automatická detekce zpoždění podle GPS dat vozidel.

Modul pro interní údržbu vozidel a servisní záznamy.

   ___SSTEBrno___
