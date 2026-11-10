<p align="center"><a href="README.md">Русский</a> · <b>English</b></p>

<p align="center">
  <img src="assets/emberforge.png" width="96" alt="Emberforge" />
</p>

<h1 align="center">Emberforge</h1>

<p align="center">
  <b>Crafting assistant for Path of Exile 1 and 2</b>, in English and Russian.<br/>
  Craft faster without memorising mod texts and without fear of rerolling a good item.
</p>

<p align="center">
  <a href="https://github.com/GStoneG/emberforge-releases/releases/latest/download/Emberforge.exe"><b>⬇ Download Emberforge.exe</b></a>
  &nbsp;·&nbsp; Windows 10/11 · single file · no installation
</p>

![Emberforge interface](assets/screenshot-en.png)

<sub>Main screen mockup (English interface): a hit while rolling a T17 map, with the overlay shown above the game.</sub>

---

> ### 🛡️ Safe crafting, within the game rules
> In **safe mode** (on by default) Emberforge never presses anything by itself: **one key press from you is one action in the game**. That is exactly what Grinding Gear Games requires: “one key press, one server action”. The program does not read the game's memory, does not inject into the process and does not modify game files; it only helps you avoid mistakes and never ruin a good item.
>
> You craft faster without risking a ban for auto-clicking. Auto mode, which breaks the rules, is off and can only be enabled after explicitly accepting the risk.

## Why you need it

Crafting in Path of Exile means hundreds of identical actions: pick up an orb, click the item, read the mods, decide what to do next. It is slow and tiring, and it is easy to make a mistake: one extra click and the mod you spent fifty orbs on is gone.

**Emberforge takes over the routine.** You describe once what you want, and on every step the program:

1. **reads the item** the same way you do, by copying its text (Ctrl+C);
2. **checks** whether the wanted result appeared;
3. **decides** which orb to use next and applies it when you press the key;
4. **stops by itself** as soon as the target is reached, and never touches the good item again.

## Features

### 🎯 Targets without memorising mods
Start typing “life”, “cold res” or “attack speed”, and Emberforge shows the mods exactly as the game writes them. The database has **8,600+ PoE1 mods and 3,500+ PoE2 mods** with texts of both the English and the Russian client. Set the minimum value, whether the mod must be a prefix or a suffix and the required tier (T1, T2…). Mark mods “Required” and ask for any N of the rest: e.g. life required + any 2 of 5 resistances.

### 🗺️ Rolling T17 maps and Waystones
Set “Item Quantity ≥ 90%”, “More Currency”, “Pack Size” and a list of mods you never want (reflect, “players cannot regenerate”…). Emberforge chaoses the map until it is right. You can queue **several maps at once**: the program goes through them one by one.

### ⛓️ Real crafting chains
Not just spamming one orb, but a chain that thinks about every step:

> Transmutation → **Alteration ⇄ Augmentation** → **Regal Orb** → **Exalted ⇄ Annulment** → if the target is missed: Scouring or Chaos

- **Smart Augmentation:** looking for a suffix but Alteration only gave a prefix? Emberforge uses an Orb of Augmentation on the free slot instead of rerolling the item for nothing.
- **Regal Orb** when the magic item has the wanted mods and no junk.
- **Two lists: magic and rare item.** The “Magic item” list says what to roll before the Regal Orb: required mods plus “one of” the others (e.g. life + chaos **or** fire). The “Rare item” list is the finished item (e.g. life + any 2 of 5 resistances).
- **Reactions after the Regal Orb and Exalts:** wanted mod → go on, junk → Annulment, Scouring and restart, or stop (set separately for the Regal and for Exalts). You choose how many Exalted Orbs go into one item. If a required magic-item mod is lost, the chain starts over.
- **Chain diagram:** the stages are shown as blocks and the current one lights up while crafting.
- **Exalted Orb** while a missing mod can still land in a free slot; **Orb of Annulment** when a junk mod takes the space.
- **Limits** for every orb (e.g. “at most 5 Exalted”) so you never burn expensive currency.

Simple modes are there too: Chaos, Alteration, Essence or any other currency spam.

### 🛡️ Protection from mistakes
- **Lock on hit.** Once the target appears, no more clicks happen however often you press.
- **Check before every action.** If you crafted something by hand, the program notices and will not ruin the item.
- **Lag protection.** If the item did not change after an action (lag, out of currency, a missed click), the program stops instead of throwing a second orb blindly.
- **Wrong item.** If a different item is under the cursor, crafting stops.
- **Emergency stop** with one key, even in the middle of an action.

### 🔍 Check without spending currency
Copy an item in the game (Ctrl+Alt+C) and press “Check item from clipboard”: matching mods turn green, forbidden ones red. Handy for tuning a target before spending orbs.

### 💰 Cost and odds
Currency prices come from poe.ninja for the chosen league (chaos in PoE1, exalts in PoE2), so you see what a session and a single hit cost. “Odds” estimates the chance per attempt and the average cost from the game's mod weights. For now PoE1 only and only for the Chaos, Alteration and Alteration + Augmentation strategies: the PoE2 game data has no real mod weights. “Search on trade” opens the official trade site with the base and the wanted mods to estimate the price.

### 🧩 Grid, history, sharing
To craft maps or rings in bulk, record two corner cells of the inventory or a stash tab and the program fills in every item position. History keeps each session (attempts, currency, cost and the items you got) and exports to CSV. A profile can be copied as one line and sent to a friend, and the program tells you on start when a new version is out.

### 🔮 PoE2: Omens and Essences
When the missing mods roll only as prefixes or only as suffixes, the chain suggests the matching Sinistral or Dextral Omen before an Exalted, Annulment, Regal or Chaos Orb. You activate it in the game and the program applies the orb on the next step (it never clicks Omens itself). An Essence can replace the Regal Orb.

### 🪟 Works above the game
A small translucent panel on the right of the game window shows the status, the number of attempts and hotkey hints. It does not catch the mouse and does not get in the way. Hotkeys work right inside the game.

### 🌐 English and Russian interface
On first launch the program asks for the language; you can switch it in Settings at any time, no restart needed. The interface language is independent of the game: Russian and English clients of PoE1 and PoE2 are supported. Each profile stores its game client (Russian or English); switching it translates the conditions taken from the mod database automatically.

### 📚 Catalog
Official English and Russian names of orbs, essences, fossils, resonators, Delirium orbs and base items, searchable in both languages, copied with one click.

## How it works

Emberforge does what you would do by hand: it moves the mouse, presses keys and reads the item text from the clipboard. It **does not read the game's memory, does not inject into the process and does not modify game files.**

**Safe mode (default):** one key press from you is one action in the game. This follows Grinding Gear Games' rule “one key press, one server action”.

> ⚠️ There is also an **auto mode** where the program clicks by itself. It directly breaks GGG's rules and can get you banned, so it is off by default and can only be enabled after explicitly accepting the risk. Use Emberforge at your own risk.

## Quick start

1. **Download** [Emberforge.exe](https://github.com/GStoneG/emberforge-releases/releases/latest/download/Emberforge.exe) and run it; choose English on the first screen.
2. Switch Path of Exile to **“Windowed”** or **“Windowed fullscreen”**.
3. **Target & profiles:** pick a ready profile (e.g. “T17 map: item quantity 90%+”) or find the mods you want with the search.
4. **Calibration:** press “Record” next to each currency, hover its stack in the game and press `F4`. Record the place of the item the same way.
5. In the game press **`F2`** until **“HIT!”** lights up. Swap the item and keep pressing `F2`. Emergency stop: `F10`.

## FAQ

**Windows says “Windows protected your PC”.**
The program has no paid code-signing certificate. Click “More info” → “Run anyway”. The checksum of every release is next to it in `Emberforge.exe.sha256`.

**Key presses do not reach the game.**
If the game runs as administrator, run Emberforge as administrator too: Windows does not let normal programs control elevated windows.

**I cannot see the panel above the game.**
Use windowed or windowed fullscreen mode: in exclusive fullscreen Windows does not show windows above the game.

**Does it support the English game client?**
Yes, PoE1 and PoE2. Each profile stores its game client (Russian or English) on the “Target & profiles” page: mods from the database are added exactly as your client shows them. If a profile is written for the other client, the program stops and tells you what to change.

**How do I update?**
The program tells you on start when a new version is out. Download the file from the same link: it always points to the latest version. Profiles, history and settings are kept in `%AppData%\Emberforge`.

---

<sub>Source code is closed. Emberforge is an independent project, not affiliated with Grinding Gear Games.</sub>
