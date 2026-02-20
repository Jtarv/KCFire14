# 🔥 KC Fire 14-1 — Scheels Scavenger Hunt

A mobile-friendly, interactive scavenger hunt built for the KC Fire 14-1 volleyball team at Scheels in Wichita, KS.

## How to Use

1. **Share the link** with each team of 3 (open on one phone per team)
2. Hit **▶ START** to begin the 60-minute countdown
3. **Tap tasks** to mark them complete — points track automatically
4. Head back to the meeting spot when time's up!

## Publishing on GitHub Pages

1. Create a new repository on GitHub
2. Upload `index.html` and this `README.md`
3. Go to **Settings → Pages**
4. Under "Source," select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://yourusername.github.io/your-repo-name/`

Then just text that link to the teams!

## What's Included

| Section | Tasks | Points Each | Total |
|---------|-------|-------------|-------|
| 🔥 Warm-Up | 5 | 5 pts | 25 |
| ⚡ Main Event | 8 | 10 pts | 80 |
| 💛 Finish Strong | 3 | 15 pts | 45 |
| | | **Max Score** | **150** |

*Plus bonus creativity points.*

## Features

- ⏱️ 60-minute countdown timer (flashes warning at 5 min and 2 min)
- ✅ Tap-to-complete tasks with running score
- 🎊 Confetti celebration when timer hits zero
- 📱 Designed for mobile — no app install needed
- 🔥 KC Fire team colors

## Customization

Everything is in a single `index.html` file. To tweak:

- **Timer duration**: Change `60 * 60` in the `totalSeconds` variable
- **Tasks**: Edit the task card HTML blocks directly
- **Points**: Update the `onclick="toggleTask(this, X)"` values and the `MAX_SCORE` variable
- **Colors**: Modify the CSS variables at the top of the `<style>` block
