# diagsis.com

UAB „Diagnostinės sistemos“ internetinė svetainė – lietuvių (`index.html`) ir anglų (`en.html`) kalbomis.

## Struktūra

- `index.html`, `en.html` – puslapiai (tekstai keičiami abiejuose)
- `css/style.css` – bendras stilius
- `js/main.js` – meniu, žemėlapis, animacijos
- `img/` – įmonės logotipas, `img/gamintojai/` – partnerių logotipai
- `fonts/` – Inter šriftas (laikomas vietoje, be Google Fonts)

## Peržiūra

```
powershell -NoProfile -ExecutionPolicy Bypass -File tools/serveris.ps1
```

Atsidaryti http://localhost:8098
