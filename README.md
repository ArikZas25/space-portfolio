```
╔══════════════════════════════════════════════════════════════╗
║          ARIK.DEV // SPACE PORTFOLIO                         ║
║          neural_net.exe --mode=interactive                   ║
╚══════════════════════════════════════════════════════════════╝
```

> **A fully playable browser game disguised as a developer portfolio.**  
> Dodge ERR packets. Collect nodes. Unlock the profile.

---

## `$ ./boot.sh`

```
[INIT]  loading portfolio...
[OK]    canvas renderer         ✓
[OK]    hazard spawner          ✓
[OK]    7 portal nodes          ✓
[OK]    boss node               ✓
[OK]    neural net background   ✓
[READY] epoch_1.sh — training begin
```

No frameworks. No build tools. One `.html` file.  
Open it in a browser and play.

---

## `$ cat GAMEPLAY.md`

| Action | Input |
|---|---|
| Move ship | Mouse / drag (touch) |
| Activate node | Click / tap while hovering |
| Survive | Don't touch the `ERR` packets |

**The loop:**
- Survive escalating waves of homing `ERR` corruption packets
- Navigate the scrollable world to find all **7 portfolio nodes**
- Collect every node → **Boss Node spawns**
- Activate the Boss Node → **WIN**

```
NODES:  LINKEDIN · GITHUB · KEYBOUND · DUNKING BALL
        LIAV.DEV · WHATSAPP · EMAIL · [BOSS]
```

---

## `$ cat FEATURES.md`

```diff
+ Fully playable space dodger — built entirely in vanilla JS
+ Scrollable world (4× screen height) with radar & depth bar
+ 7 interactive portal nodes — each opens a real link
+ Homing ERR packets that track your ship from epoch 3+
+ Boss waves every 3 epochs — 8 packets flood the screen
+ Boss Bio Node: massive hexagon with live resume data
+ Win screen triggers after all nodes collected
+ CRT scanlines + phosphor vignette + glitch-on-hit effect
+ Matrix rain · neural net · circuit traces background
+ Mobile touch support
+ Zero dependencies · single HTML file
```

---

## `$ cat TECH.md`

```
RENDERER   — HTML5 Canvas 2D API
LANGUAGE   — Vanilla JavaScript (ES6+)
FONTS      — Google Fonts: Orbitron · Share Tech Mono
ASSETS     — None (100% procedural)
DEPS       — Zero
SIZE       — ~1 700 lines
```

---

## `$ ./install.sh`

```bash
# Option 1: just open it
open space-portfolio.html

# Option 2: serve locally
npx serve .
# → http://localhost:3000

# Option 3: deploy to GitHub Pages
# Drop the file into your repo root, enable Pages — done.
```

---

## `$ cat WIN_CONDITION.md`

```
[1/8]  Activate LINKEDIN      +500 pts
[2/8]  Activate GITHUB        +500 pts
[3/8]  Activate KEYBOUND      +500 pts
[4/8]  Activate DUNKING BALL  +500 pts
[5/8]  Activate LIAV.DEV      +500 pts
[6/8]  Activate WHATSAPP      +500 pts
[7/8]  Activate EMAIL         +500 pts
       >> BOSS NODE SPAWNS <<
[8/8]  Activate BOSS NODE     +2000 pts
       >> ALL NODES UNLOCKED — SYSTEM COMPLETE <<
```

---

## `$ whoami`

```
arik@portfolio:~$ whoami

  ROLE      Data Science & AI — BSc student
  STACK     Python · C++ · C# · JavaScript
  ML/AI     sklearn · numpy · pandas · PyTorch
  DEV       Unity · OOP · REST · Git · CI/CD
  PROJECTS  KeyBound · DunkingBall · Liav.dev
  CONTACT   arik2510@gmail.com
```

→ **[github.com/arikzas25](https://github.com/arikzas25)**

---

```
$ exit
Connection to arik.dev closed.
```
