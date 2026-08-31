# 🌍 Human History Archive

A living archive of world history written by an AI **librarian** that works
**exclusively from real public-domain books** — never from the model's own knowledge.

## How it works

1. The archive is fed by a digital library of large public-domain history books:
   H.G. Wells *A Short History of the World*, Edward Gibbon *The History of the
   Decline and Fall of the Roman Empire*, Herodotus *The Histories*,
   Thucydides *History of the Peloponnesian War*, Plutarch *Parallel Lives*
   (4 vols.), George Grote *History of Greece* (12 vols.), Flavius Josephus
   *Antiquities of the Jews* and *The Wars of the Jews*,
   *A History of the Japanese People*, *The Civilization of China*,
   *The Ancient History of the Egyptians, Carthaginians, Assyrians, Babylonians,
   Medes and Persians*, Marco Polo, Heimskringla, and segments of the
   **1911 Encyclopædia Britannica** (11th edition).
2. For each new topic the librarian **retrieves passages from these books**
   (RAG over a SQLite full-text index).
3. The article is written **strictly from the retrieved book text** and lists
   the books it was based on. No outside "knowledge", no repetition.
4. A **shared topic memory** (SQLite) stores every topic ever written, so the
   librarian never writes the same topic twice.

## Structure

- `eras/prehistoric/` — before 3000 BC
- `eras/ancient/` — 3000 BC – 500 AD
- `eras/middle-ages/` — 500 – 1500
- `eras/renaissance/` — 1500 – 1750
- `eras/industrial/` — 1750 – 1914
- `eras/modern/` — 1914 – 1991
- `eras/future/` — 1991 – today and beyond
- `eras/cultures/` — civilizations, peoples, traditions
- `data/timeline.json` — master timeline

## Sources

All source books are **public domain** (Project Gutenberg / 1911 Encyclopædia
Britannica) — factual, non-partisan, written by scholars of the 19th–early 20th
century. Every article footer names the books it was compiled from.

## License

MIT — see [LICENSE](LICENSE).
