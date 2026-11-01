# apps

## Dein erstes Minecraft-Texture-Pack

In diesem Tutorial erstellst du deine erste eigene Blocktextur. Eine Textur ist das kleine Bild, das Minecraft auf einen Block malt. In neueren Minecraft-Versionen heißt ein Texture-Pack oft **Resource Pack**.

> **Wichtig:** Dieses Tutorial beschreibt die **Java Edition auf PC oder Mac**. Bei der Bedrock Edition (zum Beispiel auf Handy, Tablet oder Konsole) sind Aufbau und Import anders. Dazu findest du weiter unten einen kurzen Hinweis.

### Das brauchst du

- Minecraft Java Edition und deine Minecraft-Version
- Ein Bildbearbeitungsprogramm, das PNG-Dateien speichern kann
- Eine passende Java-Resource-Pack-Vorlage für deine Minecraft-Version

Bitte lade Vorlagen nur von vertrauenswürdigen Seiten herunter und frage einen Erwachsenen, wenn du unsicher bist.

### Schritt 1: Vorlage für deine Version besorgen

Pack-Dateien können sich zwischen Minecraft-Versionen unterscheiden. Verwende deshalb eine Vorlage, die genau zu deiner Version passt. Sie enthält eine Datei namens `pack.mcmeta`; diese Datei sagt Minecraft, um welche Pack-Version es sich handelt.

Entpacke die Vorlage, falls sie als ZIP-Datei vorliegt. Behalte den Pack-Ordner für die nächsten Schritte.

### Schritt 2: Die Textur finden und verändern

1. Öffne den Vorlagenordner und gehe zu `assets/minecraft/textures/block/`.
2. Suche die Datei `dirt.png`. Das ist die Textur für Erde.
3. Öffne sie im Bildbearbeitungsprogramm und male sie nach deinen Ideen um.
4. Speichere sie wieder als PNG unter genau demselben Namen: `dirt.png`.

Viele Blocktexturen sind nur **16 × 16 Pixel** groß. Zoome beim Zeichnen stark hinein und verändere die Pixel einzeln. Lass die Bildgröße unverändert.

### Schritt 3: Den Pack-Aufbau prüfen

Dein Pack sollte ungefähr so aussehen:

```text
MeinErstesPack/
├── pack.mcmeta
└── assets/
    └── minecraft/
        └── textures/
            └── block/
                └── dirt.png
```

Wichtig ist, dass `pack.mcmeta` direkt im Ordner `MeinErstesPack` liegt und die Textur am richtigen Ort ist. Verwende die `pack.mcmeta` aus der passenden Vorlage, statt eine Versionsnummer zu raten.

### Schritt 4: Pack in Minecraft importieren

1. Starte Minecraft Java Edition.
2. Öffne **Optionen → Ressourcenpakete**.
3. Klicke auf **Pack-Ordner öffnen**.
4. Kopiere den Ordner `MeinErstesPack` in den geöffneten Ordner.
5. Gehe zurück ins Spiel. Dein Pack sollte in der Liste erscheinen.
6. Klicke auf den Pfeil am Pack, um es zu aktivieren, und wähle **Fertig**.
7. Schau dir einen Erdblock in deiner Welt an. Deine neue Textur sollte jetzt angezeigt werden.

Du kannst den Pack-Ordner auch als ZIP-Datei in den Ressourcenpaket-Ordner legen. Achte darauf, dass `pack.mcmeta` direkt im obersten Ordner der ZIP-Datei liegt.

### Wenn es nicht klappt

- **Das Pack erscheint nicht:** Prüfe, ob `pack.mcmeta` direkt im Pack-Ordner liegt und der Ordner im richtigen Ressourcenpaket-Ordner ist.
- **Die Erde sieht noch wie vorher aus:** Prüfe den Dateinamen `dirt.png` und den Ordnerpfad. Aktiviere das Pack erneut oder starte Minecraft neu.
- **Minecraft zeigt eine Warnung:** Wahrscheinlich passt die Vorlage nicht zu deiner Minecraft-Version. Suche eine passende Vorlage und probiere es damit erneut.

### Kurzer Hinweis zur Bedrock Edition

Bei Bedrock brauchst du ein anderes Pack-Format mit einer `manifest.json`. Viele Pack-Editoren oder Bedrock-Vorlagen helfen dir dabei, das Pack als `.mcpack`-Datei zu exportieren. Öffne die `.mcpack`-Datei auf deinem Gerät, damit Minecraft sie importiert, und aktiviere sie anschließend in den Einstellungen deiner Welt unter **Ressourcenpakete**. Auf Konsolen ist der Import eigener Dateien oft eingeschränkt.

Ändere am besten nur Texturen, die du selbst erstellt hast, und teile keine fremden Packs ohne Erlaubnis.