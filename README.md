# 📘 CSS Flexbox — `flex: 1 1 auto` vs `flex: 1 1 0`

### 🗓️ Date: July 31, 2025

---

## 🔍 Topic
Understanding how the `flex-grow` and `flex-basis` values influence flex item sizing, especially when using shorthand like `flex: 1 1 auto` vs `flex: 1 1 0`.

---

## 💡 Key Insight

- `flex: 1 1 auto` distributes space **based on content size**.
  - Each item **grows equally**, but the **initial content size** matters.
  - Items with more content will appear **larger**, even with the same flex-grow factor.

- `flex: 1 1 0` distributes space **equally**, ignoring content size.
  - All items **start at 0** width.
  - Since all have the same grow factor, they **expand equally**.
  - Result: **Equal-width** flex items regardless of content.
