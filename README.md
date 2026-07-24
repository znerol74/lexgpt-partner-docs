# LexGPT Partner API — Dokumentation

Öffentliche Dokumentation der **LexGPT Partner API**, gerendert mit
[Mintlify](https://mintlify.com) unter **[docs.lex-gpt.ai](https://docs.lex-gpt.ai)**.

Die API bietet Partner-Integrationen zwei Kern-Funktionen:

- **Rechtstipp generieren** — Thema rein, recherchierter Artikel mit verlinkten
  Paragraphen raus (österreichisches Recht).
- **Feedback** — Rückmeldung zu generierten Inhalten.

## Inhalt

| Datei | Zweck |
| --- | --- |
| `openapi.yaml` | Öffentlicher API-Contract (die 3 Endpunkte + Bearer-Auth) |
| `introduction.mdx`, `quickstart.mdx`, `authentication.mdx` | Einstieg |
| `guides/` | Anleitungen: Generierung, Optionen, Paragraphen-Links, Feedback |
| `docs.json` | Mintlify-Navigation & Konfiguration |

## Lokale Vorschau

```bash
npx mintlify dev
```

Öffnet eine Live-Vorschau mit Hot-Reload unter `http://localhost:3000`.

---

Diese Doku beschreibt ausschließlich die **öffentliche** Partner-Fläche.
