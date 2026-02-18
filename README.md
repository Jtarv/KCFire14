# 🔥 KC Fire 14-1 — Scheels Scavenger Hunt

A mobile-friendly, interactive scavenger hunt built for the KC Fire 14-1 volleyball team to use at Scheels in Wichita, KS.

## How to Use

1. **Share the link** with each team of 3 (open on one phone per team)
2. Hit **▶ START** to begin the 45-minute countdown
3. **Tap tasks** to mark them complete — points track automatically
4. Head back to the meeting spot when time's up!

## Publishing on GitHub Pages

1. Create a new repository on GitHub
2. Upload both files (`index.html` and this `README.md`)
3. Go to **Settings → Pages**
4. Under "Source," select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://yourusername.github.io/your-repo-name/`

Then just text that link to the girls!

## What's Included

| Section | Tasks | Points Each | Total |
|---------|-------|-------------|-------|
| 📸 Photo Challenges | 6 | 5 pts | 30 |
| 🧩 Riddles & Finds | 3 | 10 pts | 30 |
| ⚡ Team Challenges | 6 | 10 pts | 60 |
| 🌟 Bonus Round | 3 | 15 pts | 45 |
| | | **Max Score** | **180** |

*Plus various bonus point opportunities awarded by coaches.*

## Features

- ⏱️ 45-minute countdown timer (flashes warning at 5 min and 2 min)
- ✅ Tap-to-complete tasks with running score
- 🎊 Confetti celebration when timer hits zero
- 📱 Designed for mobile — no app install needed
- 🔥 KC Fire team colors (black, red, orange, white)

## Customization

Everything is in a single `index.html` file. To tweak:

- **Timer duration**: Change `45 * 60` in the `totalSeconds` variable
- **Tasks**: Edit the task card HTML blocks directly
- **Points**: Update the `onclick="toggleTask(this, X)"` values and the `MAX_SCORE` variable
- **Colors**: Modify the CSS variables at the top of the `<style>` block
