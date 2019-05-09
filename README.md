## Magic mirror - Viðmótsforritun

Magic Mirror er raspberry pi sem er tengt við skjá sem er á bak við double sided mirror.
Það er hægt að nota það sem spegil og svo getur maður bætt við auka upplýsingum á skjáinn svo sem hvað klukkan er, veður, fréttir og fleira. Það er einnig hægt að bæta við leiðum til að get skipt á milli blaðsíða, falið eða sýnt upplýsingar með t.d motion control.

## Tæknileg atriði

### Raspberry pi
Til að starta magicmirror þar að gera
  
ef það virkar ekki þarf að reinstalla stýrikerfinu
### Myndavél
Myndavéla module-ið sem var notað: https://github.com/alexyak/camera<br>
Til að setja upp myndavélina þarf að clone myndavéla module inní modules folderinn í MagicMirror's code location með því að nota:
```
git clone https://github.com/alexyak/camera.git
```
Til að install-a node.js dependencies það að fara í camera sub folder: ```cd camera``` og gera 
```
npm install
```
### The Frame

