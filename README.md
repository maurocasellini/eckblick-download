# Eckblick

Claude right where you work: select text, press **⌃C**, and paste the short answer with **⌃V** exactly where your cursor is. In every program on your Mac. Optionally based on your own documents.

## Download

| | |
|---|---|
| **Mac with Apple chip** (M1, M2, M3, M4 …) | [Eckblick-Mac-AppleSilicon.zip](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-Mac-AppleSilicon.zip) |
| **Mac with Intel chip** (older Macs) | [Eckblick-Mac-Intel.zip](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-Mac-Intel.zip) |
| **Windows 10/11** (beta) | [Eckblick-Windows.zip](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-Windows.zip) |
| 📄 **Installation and use** | [Eckblick-Installation.pdf](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-Installation.pdf) |
| 📄 **How it works, costs** | [Eckblick-How-it-works.pdf](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-How-it-works.pdf) |

Which Mac? Apple menu  → “About This Mac” → line “Chip” (Apple M… = Apple chip, Intel = Intel).

## First: get an API key (once)

1. Open [platform.claude.com/settings/keys](https://platform.claude.com/settings/keys?ws=default) and sign in.
2. Add a small credit under “Billing” (e.g. 5 to 10 €).
3. “Create Key” → copy the key (starts with `sk-ant-`, shown only once).

## Install (about 3 minutes, no Terminal)

1. Download the ZIP, double-click it, then double-click **Eckblick**. macOS says it can’t be opened → **Done** (not Move to Trash).
2. Apple menu → **System Settings** → **Privacy & Security** → scroll all the way down → **Open Anyway** → password.
3. “Move to Applications?” → **Yes**.
4. In the settings, enter your **API key** → **“Speichern & testen”** (save & test).
5. **“Freigabe öffnen”** (open permissions) → turn on Eckblick under **Accessibility** and **Input Monitoring**.

Done. Eckblick sits at the top right of the menu bar and starts with your Mac from now on.

The app itself is in German. For **English answers**: settings → **“Antwortsprache”** → **“Englisch”** (or “Wie die Frage” = same language as the question).

## How to use

- Select text + **⌃C** → question to Claude
- **⌃V** → paste the answer at the cursor
- **⌃X** → open or close the panel (answer + field for your own question)
- Select **your own text** + **⌃R** → rewritten (spelling, grammar, clearer); **⌃V** replaces it
- **⌃S** → drag a screen area (chart, slide, error message …) → Claude explains it; **⌃V** pastes
- In **Mail/Outlook**, ⌃C also takes the selected email as context, so replies fit the conversation
- Hold **⌃** + move the mouse to the bottom left corner → panel too
- **⌃⇧H** → switch display mode (discreet / clearly visible)
- **Quit:** settings → at the very bottom “Beenden” (or menu bar icon → “Eckblick beenden”)

**Two answer styles:**
- **Discreet mode** → exam style: compact, professional, structured. Same everywhere.
- **Clearly visible mode** → fits the program you’re in: a ready-to-send reply in Mail, short chat lines in Slack/Teams/WhatsApp, full sentences in Word/Pages, slide bullets in PowerPoint/Keynote, just the value in Excel, just code in code editors. Details in the PDF “Installation”, section 3.

⌃ is the **Control key** at the bottom left, not ⌘. ⌘C and ⌘V keep working as usual.

**Updates:** Eckblick checks for new versions by itself and shows “Neue Version verfügbar” in the settings. One click on “Jetzt aktualisieren” installs it.

## Windows (beta)

Unzip **Eckblick-Windows.zip**, double-click **Eckblick.exe** → “Windows protected your PC” → **More info** → **Run anyway** → “Installieren?” → yes. Enter your API key. Shortcuts on Windows: **Ctrl+Alt+C** ask, **Ctrl+Alt+V** paste, **Ctrl+Alt+X** panel, **Ctrl+Alt+R** rewrite, **Ctrl+Alt+S** screen area (Ctrl+C/V stay normal). Same features as on the Mac, including answers that fit the program and text recognition for scanned PDFs. Not yet tested on real Windows PCs, feedback welcome.

**Uninstall completely:** settings → at the very bottom “Entfernen …” → confirm. Removes the app, settings, API key, knowledge base, auto-start and permissions. Manual steps in the PDF “Installation”, section 5.

**Your own documents:** connect a folder in the settings under “Wissensbasis” (knowledge base). It is read locally at no cost; each question then costs about 1 to 7 cents. Details in the PDF “How it works”.

<sub>Optional for Chrome, Edge, Brave, Arc: [Eckblick-Browser-Extension.zip](https://github.com/maurocasellini/eckblick-download/releases/latest/download/Eckblick-Browser-Extension.zip) (installation in the PDF, section 4). All versions: [Releases](https://github.com/maurocasellini/eckblick-download/releases).</sub>
