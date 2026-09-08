# Desktop Quest — Mouse & Keyboard Lab

A single-file browser game for the lesson **"Computer navigation and mouse/keyboard control."**
SWBAT identify basic Linux desktop features and demonstrate accurate mouse and keyboard control.

## Running it
Double-click `desktop-quest.html` for the lesson, or `exam.html` for the test — either opens in any
browser (Firefox, Chrome, Chromium).
No internet, no install, no server. To put it on lab machines, copy the one file
(e.g. to `/home/student/Desktop/desktop-quest.html`) or host it on the school share.
Best on a screen 1100px wide or more. Fullscreen with **F11**.

## QA test build
`desktop-quest.test.html` is a copy for testing — never hand this one to students.
It has a red **TEST BUILD** ribbon and a **⚡ QA: Skip login** button that logs in as
"QA" and opens the Teacher Panel automatically so you can jump straight to any part
(**▶ Part 1–5**, **▶ Exit ticket**) instead of playing through from the top each time.
Key Hunt's key-highlight hints and the Speed Typing round timers are also shortened so
each pass is quicker to click through. Everything else — content, translations, quest
logic — is identical to `desktop-quest.html`; re-copy it from that file after any future
lesson changes to keep the two in sync.

## The test — `exam.html` (no walkthrough)

`exam.html` is a **separate, assessment-only build** of the same navigation skills. It is not a copy of
the game with the hints turned off — it is written from scratch as a test:

- **No coach, no spotlight, no hints, no retry coaching.** A wrong answer says only *"Not correct."*
  The student has to work out what to try next.
- **12 items, 24 points.** 2 points if correct on the first try, 1 point after a wrong try, 0 if skipped.
- Each item is scored independently and the student can **Skip** anything they cannot do, so one stuck
  item never blocks the rest of the test.
- Runs about **5–8 minutes**.

| # | Skill tested |
|---|---|
| 1 | Identify the desktop (click the desktop, not an icon or a bar) |
| 2 | Select an icon with one click — without opening it |
| 3 | Open an application with a double-click |
| 4 | Close an application window |
| 5 | Find the App Launcher |
| 6 | Find the system menu (Wi-Fi, battery, clock) |
| 7 | Scroll to the bottom of a file list |
| 8 | Right-click to bring up a context menu |
| 9 | Keyboard — Enter |
| 10 | Keyboard — Shift for capitals |
| 11 | Keyboard — Backspace |
| 12 | Which key takes a screenshot (multiple choice) |

The desktop has eight icons, so every click item has real distractors — the test does not point at
the answer the way the lesson does.

**The report.** At the end the student gets a printable report with their name, the date, the score
and percentage, the total time, and one row per skill showing ✓/✗, points, number of wrong tries, and
seconds spent. There is a one-line copyable result (name, score, percent, time) for the gradebook, and
a footer noting what the test does *not* measure (arrow keys, the space bar). **🖨️ Print** produces a
clean page to hand in.

The test is bilingual EN/ES like the lesson, and is a single self-contained file with no internet, no
install and no server — same as the game.

## How the game maps to the lesson

| Lesson part | In the game |
|---|---|
| **0:00–0:08** Login & Warm-Up | Fake login (type name → type class password shown as dots → Enter), bubble-pop mouse warm-up, single-click an icon, double-click to open an app, close it with ✕ |
| **0:08–0:18** Teacher Modeling | 11-step guided tour with a spotlight: desktop, icons, App Launcher, system menu, click vs. double click, scrolling a file list, closing, returning to the desktop. Project it and have students mirror each step. |
| **0:18–0:38** Mouse & Keyboard Games | **Mouse Master** (pop = single click → select → double-click to open → right-click menu), **Scroll Quest** (wheel down for stars, then back up), **Key Hunt** — now three levels, see below |
| **0:38–0:46** Scavenger Hunt / Closure | 7-item hunt, exit question, certificate |
| **0:46–0:52** Screenshot & Hand-In | PrtScn lesson, take the screenshot, find it in Files → Pictures → Screenshots, practice upload, real Google Drive steps |

Run time is roughly **12–17 minutes** depending on the student.

## Key Hunt — three levels
1. **Find the keys** — 17 prompts: letters, numbers, Space, Enter, Backspace, Shift, all four arrows.
   The key lights up on the on-screen keyboard after 4 seconds (right away in Picture Mode).
2. **Shortcut School** — a mini text document the student edits with real shortcuts:
   **Ctrl+A** select all → **Ctrl+C** copy → **Ctrl+V** paste → **Ctrl+X** cut → **Ctrl+Z** undo → **Ctrl+S** save.
   The document reacts to each one (text turns blue, clipboard chip appears, lines duplicate, "Saved ✓"),
   and the game insists on holding Ctrl first. The browser's own Ctrl+S / Ctrl+A / Ctrl+P are blocked
   so nothing pops up over the lesson. Picture Mode uses four shortcuts (A, C, V, S) instead of six.
3. **Speed Typing** — three timed rounds that get faster: **Warm Up** (12s a line), **Faster** (9s),
   **Speedy** (11s for full sentences). Letters turn green as they match and red when they don't,
   a bar counts the time down, and each round reports **words per minute**. Running out of time just
   retries the line — there is no way to fail. Picture Mode gets fewer lines and more seconds.

Three badges come out of it: ⌨️ Key Finder, 🎹 Shortcut Pro, ⚡ Speed Typer.

## Part 5 — screenshot the certificate and hand it in
After the exit question the certificate appears with a **📸 Save my certificate** button. That moves the
certificate into a window on the desktop and unlocks three more icons, then walks the student through:

1. **Screenshot Helper 📸** teaches the Linux keys — **PrtScn** (whole screen), **Shift+PrtScn** (pick a part),
   **Alt+PrtScn** (one window) — and where Linux saves them (**Pictures → Screenshots**).
2. **Take the screenshot.** A real PrtScn press counts when the browser sees it; otherwise they click the
   on-screen PrtScn key. A "🤔 Nothing happened" button explains the screenshot-window case some distros show.
3. **Find it in Files** — navigate Home → Pictures → Screenshots and see `certificate.png` waiting there.
4. **Cloud Upload ☁️** — a clearly labeled *practice* window that works like Google Drive: drag the file into
   the drop zone, or use **+ New → File upload**. After it uploads, the real drive.google.com steps appear.
5. The closing screen repeats those five real-world steps so students can do it for real on their own machine.

The practice window is deliberately not a copy of Google's interface — it says it is practice, and the real
steps are written out next to it.

## Español / English (🌐 button)
The whole game runs in Spanish or English — login, coach, quest list, all three games,
scavenger hunt, exit question, certificate, Helper Sheet, and the Teacher Panel.

- Students pick 🇺🇸 English or 🇲🇽 Español on the login screen, or press the 🌐 button any time.
- The teacher can also switch from the Teacher Panel.
- The choice is remembered on that computer.
- Switching mid-lesson re-labels everything immediately. A mini-game that is open restarts
  in the new language, so switch between activities when you can.
- **Key names stay in English** — `Enter`, `Backspace`, `Shift`, `Space` — because that is what
  is printed on the lab keyboards. Spanish adds the meaning in parentheses,
  e.g. `Backspace ⌫ (borrar)`, `Shift ⇧ (mayúsculas)`.
- Class password: `star` in English, `luna` in Spanish (`cat` / `sol` in Picture Mode).
- Spanish vocabulary taught: escritorio, icono, clic, doble clic, clic derecho, desplazar,
  aplicación, ventana, teclado, contraseña, atajo, portapapeles, captura de pantalla, subir.

## Picture Mode — SWIEP / ELL support (🖼️ button)
- Pins the **Helper Sheet**: mouse pictograms (which button to press) + vocabulary with icons
  — click, double-click, right-click, scroll, desktop, icon, App Launcher, Files, system menu, close, keys.
- Larger icon labels and larger coach text.
- Fewer targets in each game, keyboard hints highlighted immediately (instead of after 4 seconds).
- Shorter class password (`cat` instead of `star`).
- The setting is remembered on that computer.

## Passwords
Class password is `star` (`cat` in Picture Mode); in Spanish it is `luna` (`sol` in Picture Mode). Nothing is transmitted or stored anywhere —
the login is a practice routine that also teaches that a password shows as dots and stays private.

## Coaching built in
The robot coach corrects the two most common problems by itself: clicking too fast / off target
("Slow down — put the arrow ON the picture") and single-clicking when a double-click is needed
("One click only chooses. Click two times fast to open!").

## Exit question
"Show me one thing you can do with the mouse and one thing you can do with the keyboard."
Students pick one of each; their answers print on the certificate (🖨️ Print).

## Links

| | URL |
|---|---|
| **Lesson** (guided walkthrough) | https://mesacs-0-2.onrender.com/ |
| **Test** (no walkthrough) | https://mesacs-0-2.onrender.com/exam.html |
