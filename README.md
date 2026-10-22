# AMF Alfa

En fristående, interaktiv lärplattform för arbete med folksamling på Alfa-nivån.

**Kursmål:** Studenten skall ha kunskap och förståelse om hur man arbetar med folksamling i ”Alfa-nivån”.

## Innehåll

- Sex kunskapsavsnitt med reflektionsfrågor och egen studiemarkering.
- 60 quizfrågor med källhänvisningar, blandade svarsalternativ och förklaringar.
- Sökbara frågor och svar samt repetitionskort från samma frågebank.
- Sex fiktiva scenarier med återkoppling och exempel på resonemang.
- 27 lagkort med länkar till officiell författningstext.
- Interaktiva förklaringar av konfliktreducerande principer, lägesbarometern och olika roller i en folksamling.

Sidan är anpassad för mobil och dator. Framsteg sparas i webbläsarens localStorage. Ingen inloggning, analysmätning eller extern tjänst krävs för övningarna.

## Källor och avgränsning

Bearbetade sammanfattningar utifrån sex tillhandahållna kursfiler. Originalfilerna ingår inte i det offentliga repot. Källförteckningen och rättelser av motsägelser eller äldre rättsuppgifter finns på sidan under **Källor**.

Lagavsnitt och juridiska facit kontrollerades mot publicerade författningstexter den **22 oktober 2026**. Kontrollera senare ändringar innan uppgifterna används på nytt. Innehållet är studiestöd, inte officiell polisiär vägledning, praktisk behörighet eller ett examinationsfacit.

Huvudillustrationen är AI-genererad och visar en fiktiv situation. Inga myndighetslogotyper eller originalbilder från kursmaterialet används.

## Drift

Statisk HTML, CSS och JavaScript utan byggsteg eller externa beroenden. GitHub Pages publicerar från `main`, katalog `/ (root)`.

Öppna via en vanlig lokal HTTP-server för förhandsvisning. Filen `release.json` anger version och SHA-256 för publicerade webbassets.

## Filer

- `index.html` – sidans ram, metadata och navigering.
- `styles.css` – responsiv design, fokusmarkering och utskriftsregler.
- `data.js` – kunskapsavsnitt, rättskällor, lagkort och rättelser.
- `questions.js` – frågor, svar och scenarier.
- `app.js` – interaktioner och lokal lagring.
- `assets/` – egen illustration och ikon.

Version 1.0.0.
