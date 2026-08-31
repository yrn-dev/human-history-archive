# 🌍 Human History Archive

**History of the world, written only from real books.**

No model "memory". No AI "knowledge". No propaganda. Only public-domain books —
scholarly works of the 19th and early 20th century, written by people who lived in
the age of the book, not of the algorithm.

---

## Why this archive exists

Big AI companies are buying whole libraries, digitizing the books to feed their
models, while the books themselves quietly disappear from shelves and bookstores.
Soon, when someone asks "what really happened in history?", the answer will come
from a model that was trained on everything at once — books and blog posts,
facts and propaganda. And that model will be the **only book left**.

This archive is built against that future:

- **The sources are old and clean.** Public-domain scholarly works, 100–150 years
  old. Nobody rewrote them for an algorithm. Nobody "optimized" them.
- **The AI does not write from its own head.** It is a *librarian*: it retrieves
  passages from the books and writes the article **strictly from what it found**.
  If the books are silent on a subject, the article says so instead of inventing.
- **It never repeats.** Every written topic is stored in shared memory
  (`data/written-topics.json`). The same subject is never written twice.
- **It is public.** Open on GitHub, MIT-licensed. Read it, verify it, cite it,
  reuse it. When the books are gone from the shelves, the archive remains.

## The library — 55 books, ~80 MB of text

| Book | Author | Covers |
|---|---|---|
| *A Short History of the World* (1922) | H. G. Wells | Global history: stone tools → 1920s |
| *The History of the Decline and Fall of the Roman Empire*, 6 vols. | Edward Gibbon | Rome and Byzantium, 1st–15th c. |
| *The Histories*, 2 vols. | Herodotus | Ancient world: Persia, Egypt, Greece |
| *History of the Peloponnesian War* | Thucydides | Ancient Greece |
| *Parallel Lives*, 4 vols. | Plutarch | Biographies of Greeks and Romans |
| *History of Greece*, 12 vols. | George Grote | Greece, antiquity → 1453 |
| *Antiquities of the Jews* + *The Wars of the Jews* | Flavius Josephus | Ancient Near East |
| *A History of the Japanese People* (1917) | — | Japan, antiquity → Meiji era |
| *The Civilization of China* (1910) | Herbert Allen Giles | China |
| *The Ancient History of the Egyptians, Carthaginians, Assyrians, Babylonians, Medes and Persians* (1884) | — | Ancient Near East |
| *The Travels of Marco Polo* | Marco Polo (14th c.) | Medieval world |
| *Heimskringla* (13th c.) | Snorri Sturluson | Norse world |
| *Bushido: The Soul of Japan* (1900) | Inazō Nitobe | Japan, culture |
| *An Account of Egypt* | Herodotus | Egypt |
| **The Holy Qur'an — three parallel translations** | Yusuf Ali · Pickthall · Shakir | Sacred text |
| *Encyclopædia Britannica*, 11th ed. (1911) — 25 letter segments | hundreds of scholars | "From A to Z", in detail |

All books are **public domain** (Project Gutenberg) — no copyright, no paywall,
no agenda. Every article footer names the books it was compiled from.

## How the Librarian works

1. **Retrieval.** For each topic the system searches a full-text index
   (~53,000 passages from the 55 books) and takes the most relevant excerpts.
2. **Writing.** The model writes the article **only from those excerpts**.
   Names, dates, facts — only what the books say. Thin sources → a short,
   honest article, never invented filler.
3. **Memory.** The finished topic is recorded in the shared memory.
   The same subject never comes back.
4. **Publishing.** The article is committed to this repository.

## Structure

```
eras/
├── prehistoric/    before 3000 BC
├── ancient/        3000 BC – 500 AD
├── middle-ages/    500 – 1500
├── renaissance/    1500 – 1750
├── industrial/     1750 – 1914
├── modern/         1914 – 1991
├── future/         1991 → today
└── cultures/       peoples, traditions, sacred texts
data/
└── written-topics.json   shared memory — every topic ever written
```

## How to read

1. Walk through `eras/` chronologically — the whole story in order.
2. Or jump straight to `eras/cultures/` for a people, a tradition, a sacred text.
3. Every article ends with **`## Sources`** — the exact books it was compiled from.
4. `data/written-topics.json` is a map of everything the archive already contains.

## По-русски

Крупные ИИ-компании скупают библиотеки, вырезают из книг тексты и кормят ими
свои модели, а сами книги тихо исчезают с полок. Скоро «спросить про историю»
будет означать «спросить у модели» — той, что училась на всём подряд: и на
книгах, и на пропаганде. И она останется **единственной книгой**.

Этот архив — ответ на это будущее. ИИ-библиотекарь пишет статьи **только по
настоящим старым книгам** (public domain, XIX – начало XX века, без пропаганды),
не пользуется «своими знаниями», никогда не повторяет темы и честно пишет
источники. Архив открытый. Если книги исчезнут — история останется здесь.

## License

MIT. Source books: public domain. Use it, cite it, keep it alive.
