> ⚠️ Komplimente für den Magic Mirror auf Deutsch

# MagicMirror-Compliments [![No Maintenance Intended](https://unmaintained.tech/badge.svg)](https://unmaintained.tech/)
Die deutsche Version für Magi Mirror-Kopmlimente.

## How to add the compliments to your MagicMirror
### Step 1: Check for supported languages
At the moment there is just one language: 
- German ```de.json```

### Step 2: Change config
Open your config:
```bash
sudo nano ~/MagicMirror/config/config.js
```
Scroll till you can see the compliments module. It looks something like this:
```javascript
{
    module: "compliments",
    position: "lower_third"
},
```
Change it to:

```javascript
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://raw.githubusercontent.com/SchVinzenz/MagicMirrorCompliments/refs/heads/main/de.json"
    }
},
```
Change ```nl.json``` to your own language like ```en.json``` or ```fr.json```. The abbreviation of your language can be found above.

## Credits
[https://michadenheijer.github.io/MagicMirrorCompliments](https://michadenheijer.github.io/MagicMirrorCompliments)
# Visit MagicMirror!
[MagicMirror](https://github.com/MichMich/MagicMirror)
# Visit also:
[https://technik.schächner.de/blog/2025/01/17/magic-mirror-leitfaden/](https://technik.schächner.de/blog/2025/01/17/magic-mirror-leitfaden/)
