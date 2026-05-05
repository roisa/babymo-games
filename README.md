# 🐻 BabyMo Game World

**Islamic Early Learning Games for Kids — by BabyMo.id**

> Belajar Islam sambil bermain bersama Baby Mo!
> Learn Islam through play with Baby Mo!

---

## 🎮 Game Collection — 8 Games

| # | Game | File | Status | Ages | Link Type |
|---|------|------|--------|------|-----------|
| 1 | 🌙 Doa Harian | `babymo-doa-harian.html` | ✅ **PLAYABLE** | 3–7 | Same repo |
| 2 | 🃏 Dua Journey | `babymo-dua-game.html` | ✅ **PLAYABLE** | 3–6 | Same repo |
| 3 | 🔤 Kata Islam | `babymo-arabic-spelling.html` | ✅ **PLAYABLE** | 4–7 | Same repo |
| 4 | 🛌 Dreamtime | Separate repo | ✅ **LIVE** | 2–5 | External |
| 5 | ك Huruf Hijaiyah | `babymo-hijaiyah.html` | ⬆️ **UPLOAD** | 3–6 | Same repo |
| 6 | 🔍 Cari Baby Mo | `babymo-cari.html` | 🔜 Coming Soon | 3–6 | Same repo |
| 7 | 📖 Kata Arab Mudah | `babymo-kata-mudah.html` | 🔜 Coming Soon | 2–4 | Same repo |
| 8 | 🎯 Doa Situasi | `babymo-doa-situasi.html` | 🔜 Coming Soon | 4–8 | Same repo |

---

## 📁 Repository Structure

```
github.com/roisa/babymo-games/
│
├── index.html                    ← Game Hub (rename from babymo-gamehub.html)
├── babymo-doa-harian.html        ← ✅ Daily Duas with Sound
├── babymo-dua-game.html          ← ✅ Dua Journey Matching Cards
├── babymo-arabic-spelling.html   ← ✅ Arabic Spelling Drag Game
├── babymo-hijaiyah.html          ← ⬆️ Upload from other Claude chat
└── README.md                     ← This file
```

**Separate repo (already live):**
```
github.com/roisa/babymo-dreamtime/
└── index.html                    ← Bedtime game, live at:
                                     https://roisa.github.io/babymo-dreamtime/
```

---

## 🚀 Quick Setup — GitHub Pages (Step by Step)

### Step 1 — Create a new GitHub repository

1. Go to **github.com** → Log in as `roisa`
2. Click the **+** button (top right) → **New repository**
3. Repository name: `babymo-games`
4. Set to **Public** (required for free GitHub Pages)
5. ✅ Check **Add a README file**
6. Click **Create repository**

---

### Step 2 — Upload all game files

1. Open your new repo: `github.com/roisa/babymo-games`
2. Click **Add file** → **Upload files**
3. Drag & drop ALL these files at once:
   - `babymo-gamehub.html` → **rename to `index.html`** before uploading
   - `babymo-doa-harian.html`
   - `babymo-dua-game.html`
   - `babymo-arabic-spelling.html`
   - `babymo-hijaiyah.html` (from your other Claude chat)
   - `README.md` (this file)
4. Scroll down → write commit message: `Add BabyMo games`
5. Click **Commit changes**

> **Important:** Rename `babymo-gamehub.html` to `index.html` so the hub becomes the main page automatically!

---

### Step 3 — Enable GitHub Pages

1. In your repo, click **Settings** (top menu)
2. Scroll down → click **Pages** (left sidebar)
3. Under **Branch**, select `main` → folder `/root`
4. Click **Save**
5. Wait 1–3 minutes
6. Your site is live at: **`https://roisa.github.io/babymo-games/`**

---

## 🔗 How All Links Work

### Within babymo-games repo (relative links — already set up correctly)
```
index.html (hub) → ./babymo-doa-harian.html     ✅ works
index.html (hub) → ./babymo-dua-game.html        ✅ works
index.html (hub) → ./babymo-arabic-spelling.html ✅ works
index.html (hub) → ./babymo-hijaiyah.html        ✅ works (after upload)
```

### Each game back to hub (already set up in each file)
```
babymo-doa-harian.html     → ./index.html   (shows as ./babymo-gamehub.html in code)
babymo-dua-game.html       → ./index.html
babymo-arabic-spelling.html → ./index.html
```

> **Note:** The "← Kembali ke Game Hub" button in each game links to `./babymo-gamehub.html`.
> After renaming to `index.html`, this will STILL work because GitHub Pages serves both names.
> But to be safe, you can find-replace `babymo-gamehub.html` with `index.html` in each game file.

### Dreamtime (cross-repo absolute link — already set up)
```
index.html (hub) → https://roisa.github.io/babymo-dreamtime/   ✅ already live
```

---

## 🌐 Final URLs After Deployment

| Page | URL |
|------|-----|
| 🏠 Game Hub | `https://roisa.github.io/babymo-games/` |
| 🌙 Doa Harian | `https://roisa.github.io/babymo-games/babymo-doa-harian.html` |
| 🃏 Dua Journey | `https://roisa.github.io/babymo-games/babymo-dua-game.html` |
| 🔤 Kata Islam | `https://roisa.github.io/babymo-games/babymo-arabic-spelling.html` |
| ك Huruf Hijaiyah | `https://roisa.github.io/babymo-games/babymo-hijaiyah.html` |
| 🛌 Dreamtime | `https://roisa.github.io/babymo-dreamtime/` |

---

## ⬆️ Adding Huruf Hijaiyah (from Other Chat)

1. Open the **Claude chat** where you built Huruf Hijaiyah
2. Download the HTML file (`babymo-hijaiyah.html`)
3. Go to `github.com/roisa/babymo-games`
4. Click **Add file** → **Upload files**
5. Upload `babymo-hijaiyah.html`
6. The hub already has the card ready — it will instantly link!

> The Huruf Hijaiyah card in the hub says **"Upload babymo-hijaiyah.html"** as a reminder.

---

## 🔧 How to Add a New Game

When Claude builds a new game (e.g., `babymo-cari.html`):

### 1. Download the file from Claude
Claude gives you the `.html` file — download it.

### 2. Upload to GitHub
- Go to `github.com/roisa/babymo-games`
- **Add file** → **Upload files** → drag the file → **Commit changes**

### 3. Update the hub (index.html)
Find the card for that game in `index.html` and change:
```html
<!-- BEFORE (coming soon) -->
<div class="sbtn">🔒 Segera Hadir</div>

<!-- AFTER (playable) -->
<a href="./babymo-cari.html" class="pbtn">🔍 Mainkan!</a>
```
Also change the card class from `game-card coming` to `game-card playable`.

### 4. Update stats bar
In `index.html`, update the count chips:
```html
<div class="stat-chip"><div class="sdot dg"></div><span>5 Bisa Dimainkan</span></div>
<div class="stat-chip"><div class="sdot dc"></div><span>2 Segera Hadir</span></div>
```

---

## 📋 Template for New Game Cards

When Claude builds a new game, copy this template into `index.html`:

```html
<!-- NEW GAME CARD -->
<div class="game-card playable">
  <div class="ciw"><span class="ci">🔍</span><span class="cbadge bnew">Baru!</span></div>
  <div class="cbody">
    <div class="ctitle">Nama Game</div>
    <div class="csub">Deskripsi singkat game ini untuk orang tua dan anak.</div>
    <div class="ctags">
      <span class="tag">Tipe</span><span class="tag">3–6 tahun</span>
    </div>
    <div class="cmeta"><span class="cage">⭐ Deskripsi Level</span><span class="cstars">🌟🌟</span></div>
    <a href="./babymo-namagame.html" class="pbtn">▶ Mainkan!</a>
  </div>
</div>
```

---

## 🔄 Embedding on babymo.id (Webflow or Website)

To embed any game on your main website:

```html
<!-- Embed the Game Hub -->
<iframe 
  src="https://roisa.github.io/babymo-games/" 
  width="100%" 
  height="700px" 
  frameborder="0"
  style="border-radius: 20px;"
></iframe>

<!-- Or embed a specific game -->
<iframe 
  src="https://roisa.github.io/babymo-games/babymo-doa-harian.html" 
  width="100%" 
  height="700px" 
  frameborder="0"
></iframe>
```

---

## 🐛 Troubleshooting

| Problem | Solution |
|---------|----------|
| Links between games not working | Make sure ALL files are in the SAME repo folder (not subfolders) |
| Hub not showing as main page | Rename `babymo-gamehub.html` to `index.html` |
| GitHub Pages not updating | Wait 3–5 minutes after uploading, then hard-refresh (Ctrl+Shift+R) |
| Game opens but styling is broken | Check internet connection — fonts load from Google Fonts |
| Arabic text not showing correctly | Normal on some old browsers — use Chrome or Safari |
| Sound (Doa Harian) not working | Tap the 🔊 button manually — auto-play is blocked by some browsers |
| Dreamtime link not working | Make sure the babymo-dreamtime repo has GitHub Pages enabled too |

---

## 📱 Testing Your Games

After uploading, test each URL on your phone:

1. Open Chrome on your Android or Safari on iPhone
2. Go to `https://roisa.github.io/babymo-games/`
3. Test each game:
   - 🔊 Does Doa Harian speak Arabic? (may need to tap play first on iOS)
   - 🃏 Do Dua Journey cards flip?
   - 🔤 Does drag-and-drop work on mobile?
   - 🛌 Does Dreamtime link open correctly?

---

## 💡 Claude Build Prompts — Ordering New Games

When you need a new game, use this prompt template in Claude:

```
Build a mobile HTML5 game for BabyMo.id:
- Game: [Cari Baby Mo / Kata Arab Mudah / Doa Situasi]
- File name: babymo-[name].html
- Brand: Dark green (#0B1C12), gold (#C89040), Baby Mo bear character
- Mobile-first, no frameworks, single HTML file
- Back to hub link: ./index.html
- Consistent with existing BabyMo games (same design system)
```

---

## 📂 Complete File Checklist

Before going live, confirm these files are in `github.com/roisa/babymo-games`:

- [ ] `index.html` (hub — renamed from babymo-gamehub.html)
- [ ] `babymo-doa-harian.html`
- [ ] `babymo-dua-game.html`
- [ ] `babymo-arabic-spelling.html`
- [ ] `babymo-hijaiyah.html` (from other chat)
- [ ] `README.md`

GitHub Pages enabled: **Settings → Pages → Branch: main**

---

## 👩‍💼 Maintained by

**BabyMo.id** — Islamic Early Learning for Indonesian Muslim Families

- Website: babymo.id
- GitHub: github.com/roisa
- Games built with ♥ using Claude by Anthropic

---

*بِسْمِ اللَّهِ الرَّحْمٰنِ الرَّحِيْمِ*
