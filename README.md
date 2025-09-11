iOS-WLAN-Profile-Generator

Ein JSON-Tool als NodeRed Flow zur Generierung von .mobileconfig-WLAN-Profilen für iOS-Geräte. 🇩🇪 Deutsch

🔐 Motivation & Hintergrund
iOS speichert bekannte WLANs inkl. Klartext-Passwort im Einstellungsmenü („Bekannte Netzwerke“). Dadurch besteht ein Risiko der Passwortweitergabe durch Nutzer.
Mit dem iOS-WLAN-Profile-Generator wird ein .mobileconfig-Profil erstellt:

✅ Keine manuelle Eingabe von SSID/Passwort auf dem Gerät erforderlich
✅ Passwort bleibt für Dritte unsichtbar
✅ Verbindung nur für Geräte möglich, die das Profil importieren
✅ Andere Nutzer können ausschließlich das Gastnetzwerk verwenden

✨ Features

🌐 SSID / Passwort Eingabe
⚙️ Optionen: AutoJoin, Hidden, Private-WLAN-Adresse ausschalten, IP-Tracking nicht beschränken
🛠️ DNS & Proxy Konfiguration
👀 XML-Vorschau des generierten .mobileconfig
💾 Export als .mobileconfig

Benötigte Paletten:

npm install node-red-dashboard
npm install node-red-node-email
