### Fähigkeiten / Anforderungen der App

#### Funktionen

* Rollen (Werwolf, Seher, Dorfbewohner) zufällig verteilen.
* Anzahl der Spieler frei wählen (4–20 Spieler).
* Jede Rolle wird einzeln angezeigt, damit nur der jeweilige Spieler sie sehen kann.
* Nach der Rollenverteilung startet das Spiel.
* Funktioniert auch ohne Internetverbindung (Offline-Modus).

#### Steuerung

* **Zahlenfeld:** Anzahl der Spieler eingeben.
* **Schaltfläche „Rollen verteilen“:** Erstellt die zufälligen Rollen.
* **Schaltfläche „Nächster Spieler“:** Zeigt die Rolle des nächsten Spielers an.
* Die Bedienung erfolgt vollständig über gut sichtbare **Buttons** und Touch-Eingaben.

#### Ähnliche Apps/Spiele<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Werwolf Spiel</title>

    <link rel="manifest" href="manifest.webmanifest">
    <link rel="stylesheet" href="style.css">

    <meta name="theme-color" content="#1a1a2e">
</head>
<body>

    <div class="container">
        <h1>🐺 Werwolf Spiel</h1>

        <div class="card">
            <label>Anzahl Spieler:</label>
            <input type="number" id="spielerAnzahl" min="4" max="20" value="6">

            <button id="startBtn">Rollen verteilen</button>
        </div>

        <div class="card">
            <h2>Rollen</h2>
            <p id="rolleText">Noch keine Rollen erstellt.</p>

            <button id="naechsterBtn" disabled>Nächster Spieler</button>
        </div>
    </div>

    <script src="app.js"></script>
</body>
</html>

* Das bekannte Gesellschaftsspiel **Werwolf**.
* Ähnliche Apps sind **Werwolf Online**, **One Night Ultimate Werewolf** oder **Mafia**-Apps, bei denen ebenfalls geheime Rollen verteilt werden.

#### Design

* Dunkles Farbschema (Blau- und Grautöne) passend zur Nachtstimmung des Spiels.
* Große, gut lesbare Schrift für Smartphones.
* Einfache und übersichtliche Benutzeroberfläche.
* Abgerundete Buttons und Karten für eine moderne Optik.
* Responsives Design, sodass die App auf Smartphone, Tablet und PC gut funktioniert.
