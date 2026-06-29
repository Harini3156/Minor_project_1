# # GroupDNA — WhatsApp Chat Analyzer 📊

GroupDNA is a terminal-styled text-mining and behavioral analytics tool built to parse raw WhatsApp chat export files and generate an executive profile overview. Think of it as **"Spotify Wrapped, but for your friend group."**

The project extracts insights from conversational data, building timeline metrics, finding peak volume hours, analyzing vocabulary, calculating response velocity, and using rule-based thresholds to assign unique personality archetypes to group members.

## 🛠️ The Constraint Discipline (Page 16 Regulations)
To demonstrate a strong foundation in core software engineering and algorithmic optimization, this project was built **completely from scratch without standard library shortcuts**.
- **Forbidden:** `pandas`, `re` (Regular Expressions), `collections.Counter`, `defaultdict`, `matplotlib`, `seaborn`.
- **Utilized:** Pure Python primitives (Strings, Lists, Dictionaries, Tuples), conditional loops, and multi-dimensional **NumPy** arrays for density matrix aggregation.

---

## 🚀 Key Features

- **Feature 1: The Chat Parser** — Safely reads messy plain-text data line-by-line, reconstruction-mapping multi-line message continuations and isolating structural edge cases like `<Media omitted>` and retraction stubs.
- **Feature 2 & 3: Volumetric & Time Peaks Summary** — Evaluates communication distributions and isolates the absolute busiest calendar day and hour block.
- **Feature 4: Activity Heatmap Matrix** — Populates a strict $6 \times 24$ NumPy grid to map individual messaging intensity across different hourly bins, rendering a shade-blocked visual terminal map.
- **Feature 5: Top Vocabulary Chart** — Cleans and tokenizes text payloads, strips trailing punctuation, filters out custom stop words, and draws text-based bar charts.
- **Feature 6: Response Patterns & Silent Streaks** — Uses native `datetime` logic to capture reply gaps between alternating senders and charts continuous individual inactivity stretches.
- **Feature 7: Archetype Allocation Engine** — Applies rule-based quantitative scoring logic to award behavioral badges (e.g., *The Spammer*, *The Night Owl*, *The Storyteller*, *The Ghost*).
- **Feature 8: Styled Executive Dashboard** — Packs all performance metrics into an aligned, box-bounded visual printout.
