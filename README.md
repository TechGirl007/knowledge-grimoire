# knowledge-grimoire
A gamified reading tracker to turn books into power levels.

# 📖 Knowledge Grimoire
**Slay books. Absorb wisdom. Ascend your rank.**

Welcome to the **Knowledge Grimoire**, a gamified reading tracker designed to transform the act of reading from a chore into a quest. Instead of a simple list, your reading history becomes a journey of ascension, turning books into "Conquests" and readers into "Legends."

## 🌟 The Concept
The Knowledge Grimoire treats knowledge as a power level. Every book you finish increases your **Intellect Level**, allowing you to evolve through different **Archetypes**—from a humble Novice to the Transcendental Eternal.

### 🏆 The Hierarchy of Knowledge
| Books | Archetype | Status |
| :--- | :--- | :--- |
| 0-2 | **Novice** | Awakening |
| 3-9 | **Scholar** | Studious |
| 10-19 | **Sage** | Enlightened |
| 20-49 | **Archmage** | Omniscient |
| 50+ | **Eternal** | Transcendental |

## ✨ Key Features
- **Trophy Cards:** A dynamic, visual character card that evolves its color and rank as you read more.
- **Arcane Insights:** Beyond just logging a title, the Grimoire requires an "Arcane Insight"—one singular truth or enchantment taken from the book.
- **Soulstones (Data Persistence):** To ensure your legend is never lost, you can "Crystallize" your progress into a `.json` Soulstone file. This allows you to back up your data and restore it on any device without needing a cloud account.
- **Domain Tracking:** Organize your conquests by domains such as Philosophy, Science, and Graphic Novels.

## 🛠️ Technical Stack
This project is built with a "back-to-basics" approach, focusing on high-performance vanilla web technologies:
- **HTML5**: Semantic structure.
- **CSS3**: Custom properties (CSS variables), linear gradients, and glassmorphism for the "Arcane" aesthetic.
- **JavaScript (ES6+)**: 
    - `LocalStorage` for the Local Arcane Vault.
    - `Blob API` for Soulstone exportation.
    - `FileReader API` for Soulstone restoration.

## 🚀 How to Play
1. **Log a Conquest:** Enter the book title, author, and category.
2. **Record your Insight:** Write down the one thing that stood out most.
3. **Ascend:** Watch your Intellect Level rise and your Trophy Card evolve.
4. **Secure your Soulstone:** Download your `.json` backup to ensure your progress is safe from browser cache clears.

## 🤝 Contributing (Hacktoberfest 2026)
I am looking for fellow adventurers to help expand the Grimoire! I would love contributions in the following areas:
- **New Archetypes:** Suggest and design ranks for readers who have conquered 100+ books.
- **Visual Enhancements:** Help implement `html2canvas` to allow users to download their Trophy Card as a PNG image.
- **Feature Additions:** Implement a "Reading Streak" counter or a "Boss Battle" (Monthly Reading Goals).
- **UI/UX:** Improve the responsiveness for mobile devices.

**If you're interested, please open an issue or submit a Pull Request!**

---
*Built with ❤️ by [TechGirl007](https://github.com/TechGirl007) for the Dev.to Hacktoberfest Weekend Challenge.*
