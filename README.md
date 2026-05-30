# ☣ DEAD QUERY — Learn SQL & Survive the Outbreak

A beginner-friendly **SQL learning game** with a zombie-apocalypse theme. The dead
have risen, the power's flickering, and the only way to keep your camp alive is to
query the survival database. You learn real SQL by completing 12 missions — from
your very first `SELECT` to a final boss `JOIN` + `GROUP BY` showdown.

No setup. No installs. Just open the page and play.

## ▶ How to play

**Option A — open the file**
1. Download / clone this repo.
2. Double-click `index.html` (it opens in your browser).
3. You need an internet connection the **first time** (it downloads the SQL engine).

**Option B — live link (no download)**

👉 **https://griffinjoshua.github.io/the-first/**

This is published automatically with GitHub Pages every time `main` updates.

## 🧟 How it works

- You write **real SQL** in the editor and press **Run** (or `Ctrl/Cmd + Enter`).
- A genuine SQLite database runs **inside your browser** (via [sql.js](https://sql.js.org), SQLite compiled to WebAssembly) — nothing is sent anywhere.
- Each mission checks your results. Solve it to unlock the next one.
- Stuck? Every mission has a **Hint** and a **Show solution** button.
- Your progress is saved automatically in your browser.

## 🎓 What you'll learn

| Mission | SQL concept |
|--------:|-------------|
| 1 | `SELECT *` — get everything |
| 2 | `SELECT col1, col2` — pick columns |
| 3 | `WHERE` — filter rows |
| 4 | `>` `<` `>=` `<=` — compare numbers |
| 5 | `ORDER BY ... DESC` — sort |
| 6 | `AND` / `OR` — combine conditions |
| 7 | `LIKE '%...%'` — pattern match text |
| 8 | `IN (...)` — match a list |
| 9 | `COUNT(*)` — count rows |
| 10 | `GROUP BY` — summarize per group |
| 11 | `JOIN ... ON` — connect tables |
| 12 | **Boss:** `JOIN` + `SUM` + `GROUP BY` + `ORDER BY` |

## 🗄️ The database

Three tables you'll query throughout the game:

- **`survivors`** — `id, name, role, level, ammo, camp`
- **`weapons`** — `id, name, type, damage, weight`
- **`raids`** — `id, survivor_id, weapon_id, rounds` (which survivor used which weapon)

Good luck out there. 💀
