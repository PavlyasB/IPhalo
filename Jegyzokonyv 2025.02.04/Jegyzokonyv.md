# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.

## 1. A számítógép IP beállításainak lekérdezése
Parancs: `ipconfig`
<details>
  <summary>Kép megtekintése</summary>
  ![IPCONFIG](PavlyasB/IPhalo/Képek/ipconfig-all.png)
</details>
---
## 2. Az aktuális IP-cím eldobása
Parancs: `ipconfig /release`
<details>
  <summary>Kép megtekintése</summary>
  ![release](PavlyasB/IPhalo/Képek/iprelease.png)
</details>
---
## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`
<details>
  <summary>Kép megtekintése</summary>
  ![renew](PavlyasB/IPhalo/Képek/iprenew.png)
</details>
---
## 4. A routing tábla megjelenítése
Parancs: `netstat -a`
<details>
  <summary>Kép megtekintése</summary>
  ![netstat-a](PavlyasB/IPhalo/Képek/netstat-a.png)
</details>
## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`
<details>
  <summary>Kép megtekintése</summary>
  ![microsoft](PavlyasB/IPhalo/microsoftcom.png)
</details>
## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`
<details>
  <summary>Kép megtekintése</summary>
  ![tracert](PavlyasB/IPhalo/Képek/traceipon.png)
</details>
## 7. Használt portok listázása
Parancs: `netstat -f`
<details>
  <summary>Kép megtekintése</summary>
  ![netstat-f](PavlyasB/IPhalo/Képek/netstat-f.png)
</details>
## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`
<details>
  <summary>Kép megtekintése</summary>
  ![netsh](PavlyasB/IPhalo/Képek/netshinterface.png)
</details>
## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`
<details>
  <summary>Kép megtekintése</summary>
  ![flushdns](PavlyasB/IPhalo/Képek/dnsflush.png)
</details>
## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`
<details>
  <summary>Kép megtekintése</summary>
  ![netuse](PavlyasB/IPhalo/Képek/netuse.png)
</details>
## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`
<details>
  <summary>Kép megtekintése</summary>
  ![Ipon](PavlyasB/IPhalo/Képek/ipon.png)
</details>
## 12. Telefon rákapcsolódva a Wi-Fi-re
<details>
  <summary>Kép megtekintése</summary>
  ![telcsati](PavlyasB/IPhalo/Képek/telefoncsati.PNG)
</details>
## 13. Telefon pingelése laptopról
<details>
  <summary>Kép megtekintése</summary>
  ![telping](PavlyasB/IPhalo/Képek/Telefon-ping.png)
</details>
## 14. Router konfigurációk
<details>
  <summary>Kép megtekintése</summary>
  ![routercon](PavlyasB/IPhalo/Képek/routerconfig.png)
</details>
<details>
  <summary>Kép megtekintése</summary>
  ![routercon1](PavlyasB/IPhalo/Képek/routerjelszo.png)
</details>
<details>
  <summary>Kép megtekintése</summary>
  ![routercon2](PavlyasB/IPhalo/Képek/pingletilt.png)
</details>


## Eszközök
A tesztelés során a következő eszközökkel dolgoztam:
- **Catalyst 2950 switch**: A hálózati eszközök közötti kapcsolatot biztosította.
- **Linksys router**: A hálózat központi irányítószerveként szerepelt.
- **ThinkPad laptop**: A teszteléshez használt számítógép, amelyről a ping tesztek és egyéb parancsok futtak.
- **Mobiltelefon**: Ezzel csatlakoztam a Linksys routerhez, hogy a laptop és a többi eszköz között pingelni tudjak.

## Összegzés
A tesztelés során a **Linksys router**, a **Catalyst 2950 switch** és a többi hálózati eszköz zökkenőmentesen működtek együtt. Az IP-konfigurációk kezelése, a routing tábla megjelenítése és a különböző hálózati parancsok futtatása sikeresen zajlott. A mobiltelefonnal való csatlakozás lehetővé tette a laptop és a többi eszköz közötti kommunikációt.