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
> ⚠️ MagicMirror-Compliments is deprecated, please consider creating your own fork and using that url as ```remoteFile```.
```javascript
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://raw.githubusercontent.com/michadenheijer/MagicMirrorCompliments/main/nl.json"
    }
},
```
Change ```nl.json``` to your own language like ```en.json``` or ```fr.json```. The abbreviation of your language can be found above.

## Credits
Dutch and English languages by [Micha den Heijer](https://github.com/michadenheijer), 
German language by [fixing-it](https://github.com/fixing-it),
Chuvash language by [mirontoli](https://github.com/mirontoli).
# Visit MagicMirror!
[MagicMirror](https://github.com/MichMich/MagicMirror)
