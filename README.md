# VocabFlow — English Vocabulary Web App

## Run
Open `index.html` in any modern browser. No server or installation is needed.

## Included
- Curated starter vocabulary with Roman Urdu meanings
- 3 examples per word, each labelled with a tense and Roman Urdu translation
- Part of speech, category and difficulty filters
- Search, saved words, learned progress and mini quiz
- JSON/CSV import for expanding the library
- Responsive mobile and desktop layout
- Progress and saved words stored in browser localStorage

## About the 20,000-word goal
This delivery is a quality-focused starter pack, not a falsely-labelled 20,000-entry dictionary. The app is built to accept a large JSON array (20k+ entries) through Import vocabulary. Each imported object can use this structure:

```json
{
  "word": "negotiate",
  "meaning": "baat-cheet se shart tay karna",
  "pos": "verb",
  "category": "Work & goals",
  "level": "Advanced",
  "examples": [
    {"tense":"Present Simple","en":"We negotiate the price.","ur":"Hum qeemat par baat-cheet karte hain."},
    {"tense":"Past Simple","en":"They negotiated the terms.","ur":"Unhon ne sharaait tay ki thin."},
    {"tense":"Future Simple","en":"I will negotiate tomorrow.","ur":"Main kal baat-cheet karunga/karungi."}
  ]
}
```

CSV import expects headers: `word,meaning,pos,category,level`. For high-quality 20k entries with accurate Roman Urdu translations and natural examples, import a reviewed dataset in this format. CSV import is best for basic entries; JSON supports full example objects.
