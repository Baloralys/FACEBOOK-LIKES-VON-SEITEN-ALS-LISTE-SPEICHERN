# FACEBOOK-LIKES-VON-SEITEN-ALS-LISTE-SPEICHERN
## letzter Check 01.06.2017
Hier wird genau beschrieben, wie du alle Personen die "Gefällt mir" auf deiner Facebook-Seite geklickt haben in eine Komma getrennte Liste abspeichern kannst.

1. Öffne dazu deine Facebook-Seite: https://www.facebook.com/DEINEFACEBOOKSEITE/settings/?tab=people_and_other_pages

2. Scrolle bis ganz nach unten, damit die Personenliste vollständig geladen wird

3. Drücke jetzt (gleichzeitig)

Tastenkombination  | Browser
------------- | -------------
**STRG + SHIFT + J**  | Google Chrome
**STRG + SHIFT + K**  | Mozilla FireFox
**F12**  | Internet Explorer

Es wird sich ein Fenster mit einem Eingabebereich öffnen. 
Bei Google Chrome Browser und Internet Explorer muss man zusätzlich zuerst auf CONSOLE klicken.

###### Für Facebook-Seiten folgenden Code kopieren und einfügen. Danach auf Enter drücken:
```javascript
javascript:var inputs = document.getElementsByClassName('_3cb8'); var liste = []; for(var i=0; i<inputs.length;i++) { liste.push(inputs[i].innerText) }; liste.toString();
```

***

**Hinweis: Achte auch nach dem kopieren und einfügen bitte darauf, dass "javascript" ebenfalls eingefügt wurde. Beim Internet Explorer Logo Internet Explorer wird der Code (bei älteren Versionen) außerdem erst mit einem Klick auf den kleinen grünen Pfeil rechts ausgeführt.**
