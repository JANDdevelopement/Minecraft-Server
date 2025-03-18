# ChestShop: Ver- /Kaufen leicht gemacht
ChestShops sind wie der Name es schon sagt Shops an Kisten, wer hätte das gedacht?  
Mit dem ChestShop Plugin könnt ihr einfach und sicher Items verkaufen und kaufen.  

## Adminshop
Der erste Schritt zur neuen Wirtschaft ist der Adminshop am Spawn.  
Dort könnt ihr Diamanten für 5$ pro Stück verkaufen. So kommt ihr Momentan auch ohne Interaktion mit Spielern an Geld.  

## Eigenen ChestShop erstellen
So erstellt ihr euren eigenen Shop:

1. **Kiste/Barrrel platzieren**  
   - Unterstützt werden: **Chests**, **Trapped Chests** und **Barrels**.  
2. **Kiste befüllen**  
   - Packt die Items hinein, die ihr verkaufen möchtet (außer bei Ankaufs-Shops).  
3. **Schild platzieren**  
   - Platziert ein Schild direkt an der Kiste.  
4. **Item festlegen**
   - Ist die letzte Zeile bei euch ein "?", rechtsklickt das Schild mit dem Item in der Hand das Ver-/ Gekauft werden soll.

### Schild-Beschriftung
Das Schild muss so formatiert sein:
```
[Die erste Zeile bleibt frei] 
64 <- Anzahl der Items pro Handel 
B 10 : 5 S <- B = Verkauf | S = Ankauf | Preise getrennt durch : 
? <- Name des Items (wird automatisch erkannt)
```
### Beispiel:  
Ein Shop, der 64 Cobblestone für 10$ verkauft und für 5$ ankauft:
```
[leer] 
64 
B 10 : 5 S 
Cobblestone
```

## Wichtige Hinweise
- Pro Shop wird ein Pfand von 10$ fällig, das ihr beim Abbau zurückerhaltet.  
- Mit **Shift + Klick** verkauft ihr direkt alle passenden Items im Inventar.  
- **1% Verkaufsgebühr** geht an den Server (kann sich ändern).  