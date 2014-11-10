# contao redirect

## Weiterleitungs-Module für SSL, Benutzersprache und Anmeldung

Diese Erweiterung stellt fünf verschiedene Frontend Module zur Weiterleitung zur Verfügung:

SSL Weiterleitung: Dies ist das SSL-Redirect Modul von Eric Bartels. Leiten Sie einen Benutzer auf die verschlüsselte Version Ihrere Seite um.
Nicht-SSL Weiterleitung: Dies ist das Gegenteil; leiten Sie den Besucher auf die nicht-verschlüsselte Version Ihrer Seite um.
Weiterleitung wenn angemeldet: Leiten den Benutzer weiter wenn er angemeldet ist. Auf diese weise kann z.B. der Zugriff auf die Registrierungs-Seite geschützt werden.
Weiterleitung von Browsern und Browserversionen: Erlaubt z.B. die Umleitung eines iPhone- oder Internet-Explorer-6-Besuchers auf eine bestimmte Seite (kann durch Cookies auch nur einmal geschehen)
Weiterleitung von Betriebssystemen: Erlaubt die interne und externe Weiterleitung von Betreibssystemen (z.B. Windows, iOS, Android, ...)

### WICHTIGE ÄNDERUNGEN BEIM WECHSEL AUF VERSION 1.5:

Die Abhängigkeit von changelanguage wurde entfernt. Die Funktion zur Weiterleitung auf die Benutzersprache wurde in changelanguage integriert!

### WICHTIGE ÄNDERUNGEN BEIM WECHSEL AUF VERSION 1.4:

Läuft nur noch mit Contao 2.10.x!
Die abhängige Erweiterung browserdetection kann gelöscht werden.
Wenn Browsererkennung über RegEx genutzt wird: Ab sofort muss der Delimeter und Modifier mit ergänzt wreden. Um das bisherige Verhalten zu bekommen bitte /.../i ergänzen, also beispielsweise wird aus "chrome" nun "/chrome/i". (Noch besser ist es natürlich die vorhandene Browsererkennung zu nutzen!)
