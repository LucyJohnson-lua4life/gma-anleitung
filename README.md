# gothic-multiplayer-adventures-server - Anleitung
Dieses Tutorial soll neuen Spielern die wichtigsten Features des Spiels beibringen. 

![GMA-Tutorial](GMA_Cover.png)
## Download und Installation

Es gibt 2 Arten wie ihr den Gothic-Multiplayer-Adventures downloaden könnt. In beiden Fällen braucht ihr eine saubere Installation von Gothic 2 (ggf. mit Systempackinstallation damit es auf neueren Rechnern läuft).


### **Über Spine**
Ihr könnt Gothic-Multiplayer-Adventures bei Spine downloaden. Dafür müsst ihr Spine downloaden, dort einen Account anlegen und dann Gothic-Multiplayer-Adventures downloaden. Öffnet Gothic-Multiplayer-Adventures und eine Serverliste müsste sich dann öffnen. Der Gothic-Multiplayer-Adventures Server sollte vorselektiert sein. Falls nicht dann sind das hier die aktuellen Serverdaten:

<br/>IP: 5.181.49.174
<br/>Port: 28654

<br/>

### **Über google drive links.**

Wenn ihr diesem Link folgt:

<br/>

https://drive.google.com/drive/folders/1WjgSMr0rypzp1U3lVuapNnHyAKTe-2Nh

<br/>

dann werdet ihr zu einem Google-Drive Ordner weitergeleitet welcher 2 Zip Dateien enthält.

<br/>

* GMA_mod.zip: Hierbei handelt es sich um die .mod Datei die ihr für das Betreten des Servers benötigt. Zieht die .mod Datei in den /Data Ordner eurer Gothic 2 Installation. Also zum Beispiel **C:/Programme/Gothic II/Data**. Wichtig! bitte denkt daran eine saubere Gothic 2 Installation zu verwenden wo allerhöchstens Standard Patches wie Systempack installiert sind und **keine** speziellen eigenen .vdfs .mods. mit neuen Animationen oder Ähnlichem. Ich hab die Sicherheitseinstellungen beziehungsweise den directory scan etwas runtergeschraubt, weil anscheinend Gothic 2 Installationen je nach Medium (CD/Steam) variieren und damals einige Nutzer Probleme hatten auf den Server zu kommen. Ich möchte ungern die Sicherheitseinstellungen wieder hochfahren müssen, wenn es zu crashes kommt weil jemand eine eigene Fremde .vdf einspielt.

* GMP_1.1.1.zip: Hierbei handelt es sich um den offiziellen Gothic Multiplayer Client mit dem ihr auch andere Server betreten könnt. Entpackt den Ordner und führt die gml.exe aus. Danach müsste sich eine Serverliste öffnen. Gegebenenfalls müsst ihr euren Gothic 2 Pfad einstellen. Geht dafür in die obere Menüleiste des Clients unter **"Settings" > "Options"** dort könnt ihr den Pfad zu eurer Gothic 2 Installation mit der GMA.mod angeben. Anschließen drückt ihr auf **apply**.


<br/>

![GMA-Tutorial](GMA_setup.png)

<br/>

Um euch mit der GMA-Server zu verbinden müsst ihr anschließend die Serverdaten eingeben. Kehrt dafür zur Serverliste zurück. Drückt auf "Add Server" und gebt die Serverdaten ein:

<br/>IP: 5.181.49.174
<br/>Port: 28654

<br/> Jetzt müsste der Server in der Liste erscheinen und ihr könnt mit Doppelklick euch auf den Server verbinden.



## Registrierung
Sobald ihr euch euch mit dem Server verbunden habt, könnt ihr euch Einloggen oder einen Account anlegen.

### Account anlegen.
* Drückt die Taste 'T' um die Chateingabe zu aktivieren.
* Tippt das Kommando **/register** ein um in den Registrierungs-Modus zu kommen.

<br/>

![GMA-Tutorial](GMA_register1.png)

<br/>

* Tippt das Kommando **_/visual_** ein um das Aussehen eures Charakters zu setzen. Jetzt öffnet sich eine Benutzeroberfläche von wo aus ihr eure Kopf- und Körpermodelle und Texturen einstellen könnt.

<br/>

![GMA-Tutorial](GMA_visual_selection.png)

<br/>

* Tippt das Kommando **/class** ein um eure Klasse auszuwählen. Genauere Eigenschaften bezüglich der Klassen findet ihr im Kapitel zu den Klassen.
* Wenn ihr zufrieden seit, wird es Zeit euren Account zu konkret anzulegen. Tippt **/register 'name' 'passwort'** (ohne Anführungszeichen) ein um euren Account anzulegen. 'name' ist euer Accountname und gleichzeitig der Name eures Charakters. 'passwort' ist das Passwort eures Accounts.

<br/>

![GMA-Tutorial](GMA_register2.png)

<br/>

### Einloggen
Sobald ihr einen Account angelegt habt, könnt ihr euch einloggen.
* Tippt das Kommando **/login 'name' 'passwort'** ein um euch unter euren Account einzuloggen.

![GMA-Tutorial](GMA_login.png)

<br>
<br>

## Klassen

In GMA existieren 5 Klassen. Jede hat ihre Stärken und Schwächen und nehmen eine bestimmte Rolle im Spiel ein.

## Interagieren mit NPC's


In GMA könnt ihr mit verschiedenen NPC's interagieren. Die Interaktion erfolgt dabei über Kommandos. Um mit einem NPC zu interagieren fokussiert den NPC und tippt das Kommando **/i** ein.


<br>

![GMA-Tutorial](GMA_NpcInteraction1.png)

<br>

Je nach NPC erscheint ein Dialog im Chat. Manchmal findet ihr dabei 2 Arten von speziellen Teilsätzen.

* Eckige Klammern: Manchmal findet ihr Teilsätze in \<eckigen Klammern\>. Wörter in eckigen Klammern sind Schlüsselwörter, womit ihr den Dialog weiterführen könnt. Tippt das Kommando **/i 'Teilsatz'** (Ohne Anführungzeichen) ein um den Dialog fortzuführen.


<br>

![GMA-Tutorial](GMA_NpcInteraction2.png)

<br>


* In Anführungszeichen: Teilsätze in 'Anführungszeichen' sind Welt-Schlüsselwörter. Wörter in Anführungszeichen sind Schlüsselwörter die auf andere NPC's angewendet werden können.
Während eckige Klammern nur einen Dialog beim selben NPC auslösen, so könnt ihr versuchen Wörter in Anführungszeichen bei anderen NPC's zu feuern und schauen ob eine besondere Reaktion kommt. Tippt dafür das Kommando **/i 'Teilsatz'** (ohne Anführungszeichen) ein um den Dialog auszulösen.

<br>

![GMA-Tutorial](GMA_NpcInteraction3.png)

<br>



<br>
<br>


## Handeln und Item-ID's

Während des Spielens habt ihr vielleicht bemerkt, dass an Itemnamen mittlerweile ID's dranhängen. Da in GMA viel mit Kommandos gearbeitet wird, wurden items nun id's vergeben damit diese besser in Kommandos verarbeiten kann. Wenn ihr bei NPC's Sachen kaufen wollt, werdet ihr sehen, dass ihr Item-ID's angeben müsst statt den Itemnamen.

<br>

![GMA-Tutorial](GMA_BuyItem.png)

<br>

### Spielerhandel
Wollt ihr untereinander handeln, werden auch Kommandos verwendet. Fokussiert dafür den Spieler an, dem ihr ein item geben wollt und Tippt folgendes ein **/give 'item-id' 'Anzahl'**.
Also z.B **/give 3000 1**. Dieser Kommando wird dem fokussierten Spieler 1x das item mit der id 3000 (Heilpflanze) aus eurem Inventar übergeben.

## Kochen, Alchemie, Schürfen
Mit manchen Mobs in der Welt könnt ihr nur interagieren wenn ihr die entsprechenden Gegenstände im Inventar habt. Wollt ihr Gold Schürfen, so braucht ihr eine Spitzhacke.
Wollt ihr Tränke an einem Alchemietisch brauen, so braucht ihr Pflanzen und Laborwasserflaschen. Wollt ihr an einem Kochtopf kochen, so braucht ihr Lebensmittel und einen Kochlöffel.

### Kochen und Alchemie
Kochen und Alchemie funktionieren ziemlich ähnlich. Sobald ihr mit dem entsprechenden Mob interagiert (Labortisch oder Kochtopf) so werden euch die Kommandos angezeigt die ihr eingeben könnt um etwas zu erstellen. Insgesamt müsst ihr 3 Gegenstände in den Kochtopf, oder die Laborwasserflasche reintun. Je nach Eingaben bekommt ihr dann euer Gericht/Trank.
Sobald ihr eine Zutat in den Kochtopf, oder die Laborwasserflasche reingetan habt, verschwindet sie aus eurem Inventar. Also seit vorsichtig, dass ihr die richtigen Zutaten zusammenmischt!

<br>

![GMA-Tutorial](GMA_brew.png)

<br>

<br>

![GMA-Tutorial](GMA_brew2.png)

<br>


<br>
<br>

## Was passiert wenn mein Charakter stirbt?

Sollte dein Charakter sterben, so verliert er sein gesamtes Inventar bis auf die Rüstung, Waffe und Fernkampfwaffe die er beim Tod ausgerüstet hatte. Beim Respawn wird er zusätzlich mit der Grundausrüstung ausgestattet. Sollte dein Charakter mit der Grundausrüstung ausgerüstet sterben, so wird er nur mit der Grundausrüstung respawned.

<br>
<br>

## Bekannte Bugs

* Der Bereich zwischen Constantinos Hütte und Coragons Taverne ist verbuggt. Wenn ihr den Bereich betretet, kann es vorkommen, dass euer Client crasht. Bisher wurde noch keine universell einsetzbare Lösung für den Fehler gefunden. Spieler haben aber berichtet, dass seit dem sie den DX11 Renderer verwenden, die Crashes aufgehört haben.

* Der Bereich zwischen dem Kloster und der Taverne zur roten Harpie ist verbuggt. Wenn ihr den Bereich betretet, kann es vorkommen, dass euer Client crasht. Bisher wurde noch keine universell einsetzbare Lösung für den Fehler gefunden. Spieler haben aber berichtet, dass seit dem sie den DX11 Renderer verwenden, die Crashes aufgehört haben.
