## 🧠 **Aufgabe: "Browser Dashboard" (Ein interaktives Dashboard für den Benutzer)**

### 🎯 **Ziel:**

Baue eine kleine Web-Anwendung ("Browser Dashboard"), die Informationen über den aktuellen Browserzustand anzeigt, reagiert auf bestimmte Fensterereignisse und einfache Interaktionen mit dem `window`-Objekt erlaubt.

---

### 📋 **Funktionen, die du umsetzen sollst:**

1. ### **Anzeigen von Fensterinformationen**

   * Zeige dem Nutzer Informationen wie:

     * Fensterbreite und -höhe (`innerWidth`, `innerHeight`)
     * Aktuelle Scrollposition
     * Aktuelle URL und Protokoll (`location`)
     * Ob der Nutzer online oder offline ist
     * User-Agent-String

2. ### **Fenster-Events beobachten**

   * Reagiere auf folgende Ereignisse:

     * `resize`: Aktualisiere die Anzeige der Fenstergröße in Echtzeit.
     * `scroll`: Zeige dem Nutzer die aktuelle Scrollposition.
     * `online` / `offline`: Zeige visuell an, wenn sich der Verbindungsstatus ändert.
     * `beforeunload`: Zeige dem Nutzer eine Warnung, wenn er die Seite schließen will.
     * Optional: `focus` / `blur`, um anzuzeigen, ob die Seite gerade aktiv im Vordergrund ist.

3. ### **Popup-Funktion**

   * Baue einen Button, mit dem ein neues Fenster oder Tab geöffnet wird (`window.open()`), das eine eigene kleine Info-Seite zeigt.
   * Bonus: Ermögliche es, das Fenster gezielt zu schließen oder zwischen Haupt- und Popup-Fenster zu kommunizieren.

4. ### **Timing-Funktionen**

   * Füge einen Bereich ein, der:

     * Alle 10 Sekunden eine Nachricht ausgibt (z.B. „Du bist seit X Sekunden hier“).
     * Einen Button enthält, der einen Countdown mit `setTimeout()` startet.

5. ### **Speicher und Navigation**

   * Ermögliche es, durch das Verwenden von `window.history` oder `location` die Seite neu zu laden, zurückzugehen oder zu einer anderen Seite zu navigieren.
   * Optional: Experimentiere mit dem `sessionStorage` oder `localStorage`, um Einstellungen des Nutzers (z. B. Dark Mode) zu speichern.

---

### 💡 **Erweiterungsideen (Optional, für später):**

* Ein Dark-/Light-Mode, der sich je nach `window.matchMedia()` automatisch an das System anpasst.
* Eine Anzeige, wie viele Tabs/Fenster du offen hast (nur experimentell möglich über `window.name`-Tricks oder Broadcast Channels).
* Ein kleines Spiel oder eine Interaktion, die auf Fenstergrößen oder Scroll-Position basiert.

---

### 🎓 **Lernziele**

Nach dieser Aufgabe solltest du:

* Die wichtigsten Methoden und Properties von `window` kennen
* Wissen, wie Events auf Fenster-Ebene funktionieren
* Wissen, wie man mit `window.open`, `setTimeout`, `setInterval`, `location`, `history`, `navigator`, etc. umgeht
* Den Unterschied zwischen globalen Variablen und dem `window`-Objekt verstehen

---

