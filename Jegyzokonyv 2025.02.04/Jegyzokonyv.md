# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.

## 1. A számítógép IP beállításainak lekérdezése
Parancs: `ipconfig`
[![IPCONFIG](PavlyasB/IPhalo/Képek/ipconfig-all.png)]
---
## 2. Az aktuális IP-cím eldobása
Parancs: `ipconfig /release`
[![release](PavlyasB/IPhalo/Képek/iprelease.png)]
---
## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`
[![renew](PavlyasB/IPhalo/Képek/iprenew.png)]
---
## 4. A routing tábla megjelenítése
Parancs: `netstat -a`
[![netstat-a](PavlyasB/IPhalo/Képek/netstat-a.png)]
## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`
[![microsoft](PavlyasB/IPhalo/microsoftcom.png)]
## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`
[![tracert](PavlyasB/IPhalo/Képek/traceipon.png)]
## 7. Használt portok listázása
Parancs: `netstat -f`
[![netstat-f](PavlyasB/IPhalo/Képek/netstat-f.png)]
## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`
[![netsh](-)]
## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`
[![flushdns](PavlyasB/IPhalo/Képek/dnsflush.png)]
## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`
[![netuse](PavlyasB/IPhalo/Képek/net use.png)]
## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`
[![Ipon](PavlyasB/IPhalo/Képek/ipon.png)]
## 12. Telefon rákapcsolódva a Wi-Fi-re
[![telcsati](PavlyasB/IPhalo/Képek/telefoncsati.PNG)]
## 13. Telefon pingelése laptopról
[![telping](PavlyasB/IPhalo/Képek/Telefon-ping.png)]
## 14. Router konfigurációk
[![routercon](PavlyasB/IPhalo/Képek/routerconfig.png)]
[![routercon1](PavlyasB/IPhalo/Képek/routerjelszo.png)]
[![routercon2](PavlyasB/IPhalo/Képek/pingletilt.png)]



## Összegzés
A tesztelés során a Linksys router megfelelően működött, a hálózati eszközök zökkenőmentesen kommunikáltak egymással. Az IP-konfigurációk kezelése, a routing tábla megjelenítése és a különböző hálózati parancsok futtatása sikeresen zajlott.