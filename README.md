# 📚 FlashHaka

A simple web-based flashcard app for learning **Hiragana** and **Katakana**. Built with **HTML**, **CSS**, and **Vanilla JavaScript** — no build step or framework required.

---

## 🚀 Features

✅ **Kana Type Toggle**
Switch between **Hiragana** and **Katakana** instantly.

✅ **Responsive Grid Flashcards**

- Mobile: 1–2 columns
- Desktop: 4–6 columns
  Click or press **Enter** to flip cards.

✅ **Single Card View**

- Focus on one card at a time.
- Use **Next / Prev** to navigate.
- Mark cards as **Hafal (mastered)**.

✅ **Controls**

- 🔀 Shuffle cards
- ↺ Reset to original order
- ☑️ Filter unread (only show unmastered)
- 🌙 Dark mode toggle

✅ **Progress Tracking**
Shows how many characters you’ve mastered out of total (e.g. 10 / 46).

✅ **Smooth Animations**
CSS-based flip and transition animations.

✅ **Accessibility (A11Y)**

- Keyboard navigation (Tab, Enter, Arrow keys)
- ARIA labels for controls and cards
- Visible focus outlines

✅ **Offline Ready**
Works by simply opening the file — no internet or build step required.

---

## 🧠 Keyboard Shortcuts

| Action                         | Key       |
| ------------------------------ | --------- |
| Flip focused card              | **Enter** |
| Move focus                     | **Tab**   |
| Prev / Next card (Single view) | **← / →** |
| Activate button                | **Enter** |

---

## 💡 How to Use

1. **Open** `kana_learning_app.html` in your browser.
2. **Choose** between Hiragana or Katakana at the top.
3. **Click** or press **Enter** on any card to flip it.
4. **Shuffle**, **Reset**, **Filter unread**, or **Switch to single view** for focused study.
5. In single view, use **✓ Hafal** to mark cards as mastered.

---

## 🌓 Dark Mode

Click **🌙 Dark** in the top-right corner to toggle dark/light mode.

---

## 📈 Progress Indicator

Displays your learning progress and updates automatically when you mark cards as mastered.

---

## 🔉 (Optional) Audio Support

You can add pronunciation audio files in `assets/audio/` folder using the kana as the filename:

```
assets/
 └── audio/
      ├── あ.mp3
      ├── い.mp3
      ├── ア.mp3
      ├── イ.mp3
      └── ...
```

Then enable playback using the `playAudioFor(kana)` helper inside the code.

---

## 🧩 File Structure

```
kana_learning_app.html   # Main file (HTML, CSS, JS inline)
assets/
 └── audio/              # Optional audio files
```

---

## 🛠️ Technologies Used

- **HTML5** — structure and semantics
- **CSS3** — responsive layout, dark mode, flip animations
- **Vanilla JS (ES6)** — interactivity, state management, keyboard controls

---

## 📄 License

MIT License © 2025 — Created by Fakhrur Rijal

You’re free to modify, distribute, and use this for personal learning or educational purposes.

---

## 🌟 Future Improvements

- 🔒 Save progress in `localStorage`
- 🔉 Add built-in audio for pronunciation
- 📆 Spaced repetition mode
- 🧩 Add Dakuten & Combination kana sets

## How to use:

- Open this file in browser (no build step).
- Toggle Hiragana/Katakana at top.
- Click a card or press Enter when focused to flip it.
- Use Grid / Single buttons to switch layout. In Single view use Prev/Next to navigate.
- Shuffle shuffles card order. Reset restores original order and unmarks mastery.
- "Belum Hafal Saja" filter shows only unmastered cards.
- Mark a card as "Hafal" in single view to mark mastered.
- Dark mode toggles color scheme.

## Keyboard shortcuts:

- Tab to move focus between controls and cards.
- Enter to flip focused card or activate focused control.
- ArrowLeft / ArrowRight to navigate prev/next in single view.

## Notes:

- Includes example arrays for 46 hiragana and 46 katakana.
- Optional: small audio playback support if you add files under assets/audio/{kana}.mp3
