# 🌍 Human History Archive

**History of the world, written only from real books and official documents.**

No model "memory". No AI "knowledge". No invented facts. Only public-domain
books (100–150 years old) and official public records — written by people, not
optimized for an algorithm.

---

## Why this archive exists

Big AI companies are buying whole libraries, digitizing the books to feed their
models, while the books themselves quietly disappear from shelves and
bookstores. Soon, when someone asks "what really happened in history?", the
answer will come from a model trained on everything at once — books and blog
posts, facts and propaganda. And that model will be the **only book left**.

This archive is built against that future:

- **The sources are real documents.** Public-domain scholarly books of the 19th
  and early 20th century, plus official public records (court and government
  documents released into the public domain). Nobody rewrote them for an
  algorithm. Nobody "optimized" them.
- **The AI does not write from its own head.** It is a *librarian*: it
  retrieves passages from the sources and writes the article **strictly from
  what it found**. If the sources are silent on a subject, the article says so
  instead of inventing.
- **It never repeats.** Every written topic is stored in shared memory
  (`data/written-topics.json`). The same subject is never written twice.
- **It is public.** Open on GitHub, MIT-licensed. Read it, verify it, cite it,
  reuse it. When the books are gone from the shelves, the archive remains.

## An honest word about the sources

We will not promise that this archive is "100% free of propaganda". That would
be a lie. We can only promise **transparency**:

- Some sources are the **perspective of a participant**. Winston Churchill's
  war memoirs describe the war from *his* side. An old book of 1900 carries the
  biases of its author's country and century. The archive keeps them **as
  sources with a named author**, not as "the truth".
- Some sources are **official documents of a government** (for example, the
  U.S. Department of Justice's public disclosures in the Jeffrey Epstein case).
  An official document is a raw record — dates, names, decisions — but it is
  still a document *of* a government. The archive does not add its own
  judgment; you read the document and decide.
- What the archive **does** guarantee:
  1. Every article names its exact sources (`## Sources` at the end).
  2. The AI adds nothing that is not in those sources — no rumors, no
     "as some say", no outside opinions.
  3. You can open the cited source yourself and check every claim.

The strength of this archive is not neutrality. It is that **you always know
whose words you are reading**.

## The library — 67 books and document sets, ~110 MB of text

| Source | Author / origin | Covers |
|---|---|---|
| *A Short History of the World* (1922) | H. G. Wells | Global history: stone tools → 1920s |
| *The Outline of History* (1920) | H. G. Wells | Global history → 1920 |
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
| *The World Crisis* (1923), vol. 1 of 6 | Winston Churchill | WWI — *the participant's own account* |
| *With the German Armies in the West* (1917) | — | WWI from the German side |
| *The Somme, Vol. 2: The Second Battle of the Somme* (1918) | Michelin (firm) | WWI, front-line record |
| *Days to Remember: The British Empire in the Great War* (1919) | Buchan & Newbolt | WWI, contemporaneous record |
| *World's War Events, Vol. 3* (1917) | Reynolds & Churchill | WWI, contemporaneous record |
| *A Short History of Belgium* (1918) | Léon van der Essen | WWI, occupied Europe |
| **Jeffrey Epstein case — official U.S. DOJ disclosures** (41 documents) | U.S. Department of Justice | FBI files, Maxwell interviews (2025), DOJ memoranda, letters to Congress (2025–2026) |

All sources are **public domain or officially released public records**
(Project Gutenberg, DOJ public disclosures) — no copyright paywall.

## How the Librarian works

1. **Retrieval.** For each topic the system searches a full-text index
   (~61,000 passages from the 67 sources) and takes the most relevant excerpts.
2. **Writing.** The model writes the article **only from those excerpts**.
   Names, dates, facts — only what the sources say. Thin sources → a short,
   honest article, never invented filler.
3. **Memory.** The finished topic is recorded in the shared memory.
   The same subject never comes back.
4. **Publishing.** The article is committed to this repository with its
   source list.

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
3. Every article ends with **`## Sources`** — the exact sources it was
   compiled from. Read those first if you want to check.
4. `data/written-topics.json` is a map of everything the archive already contains.

## По-русски

Крупные ИИ-компании скупают библиотеки, вырезают из книг тексты и кормят ими
свои модели, а сами книги тихо исчезают с полок. Скоро «спросить про историю»
будет означать «спросить у модели» — той, что училась на всём подряд: и на
книгах, и на пропаганде. И она останется **единственной книгой**.

Этот архив — ответ на это будущее. ИИ-библиотекарь пишет статьи **только по
настоящим источникам**: старым public-domain книгам (XIX – начало XX века)
и официальным публичным документам (например, раскрытые материалы дела
Эпштейна от Министерства юстиции США). Не пользуется «своими знаниями»,
никогда не повторяет темы.

**Честно о «без пропаганды»:** мы не обещаем, что архив на 100% свободен от
пропаганды — это была бы ложь. Мемуары Черчилля — это *его* версия войны.
Официальный документ правительства — это запись *этого* правительства. Старая
книга несёт взгляды страны и века своего автора. Зато мы гарантируем:

1. В каждой статье подписаны точные источники (`## Sources`).
2. ИИ ничего не выдумывает и не добавляет «а ещё говорят...» — только то,
   что в источнике.
3. Любой источник можно открыть и проверить самому.

Сила архива — не в «нейтральности», а в том, что **ты всегда видишь,
чьими словами читаешь**.

## License

MIT. Sources: public domain / officially released public records.
Use it, cite it, verify it, keep it alive.
