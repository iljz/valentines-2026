# Valentine's Day Proposal 2026

## 🎯 How to Add Your Custom GIF

### Location in `index.html`:

Find this section (around line 493-500):

```html
<div class="intro-gif-container">
    <!-- PLACEHOLDER: Replace this src with your GIF -->
    <img src="https://media.giphy.com/media/xT9IgDEI1iZyb2wqo8/giphy.gif" alt="Intro animation">
    <!-- To use your own GIF, replace with: -->
    <!-- <img src="your-gif-filename.gif" alt="Intro animation"> -->
</div>
```

### Steps:

1. **Save your GIF** in the project folder (same level as `index.html`) or in a subfolder
2. **Replace the src** with your GIF path:
   - If in same folder: `src="your-gif.gif"`
   - If in subfolder: `src="images/your-gif.gif"`
3. **Save the file**

### Example:
```html
<img src="side-part-hair.gif" alt="Intro animation">
```

---

## 🎵 Music Files

The project uses three audio files located in the `music/` folder:

1. **SIKE.mp3** - Intro sound effect (plays first)
2. **i_need_girl.mp3** - Background music (Taeyang)
3. **lemonade.mp3** - Celebration music (plays when "Yes" is clicked)

---

## 🎬 Experience Flow

1. **Political Quiz** → User fills out fake political survey
2. **"See My Results"** → Black screen appears with your GIF (3 seconds)
3. **Music starts** → SIKE.mp3 plays, then i_need_girl.mp3
4. **Scrolling text** → Romantic message reveals line by line
5. **The Question** → "Will you be my Valentine?"
6. **Yes/No buttons** → No button jumps away on hover
7. **Celebration** → Lemonade plays + confetti animation

---

## ✨ Features

- Disguised as a political compass quiz
- Black screen transition with custom GIF
- Music synchronization
- Scroll-triggered text animations
- Interactive escaping "No" button
- Growing "Yes" button (2x every 5 attempts)
- Attempt counter
- Celebration animation with music change

---

## 🚀 How to Use

Simply open `index.html` in any modern web browser. No build process required!
