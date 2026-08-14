# Biblioteka modlitw — Moja Lista Modlitw

Pliki JSON z modlitwami biblioteki aplikacji, po jednym na język:
`pl.json`, `en.json`, `es.json`, `de.json`, `fr.json`, `it.json`, `pt.json`, `uk.json`.

Format:
```json
{
  "version": 1,
  "prayers": [
    { "id": "ojcze-nasz", "libraryCategory": "basic", "title": "…", "text": "…" }
  ]
}
```

Kategorie: `basic`, `morning`, `evening`, `marian`, `rosary`, `chaplet`, `novena`.

Po każdej zmianie zwiększ `version` o 1. Aplikacja pobiera te pliki przy uruchomieniu —
zmiany docierają do użytkowników bez aktualizacji w Google Play.
