# PSP-3000 Custom Firmware & PS1 Game Guide (No Headaches Needed)

Welcome! 🎮  
This guide is for anyone with a PSP-3000 who just wants to play old-school PS1 games (like JoJo, Tekken, Final Fantasy) without getting a tech degree. If you're new to all this, don't worry — I wrote this in plain English with no scary words. Let's go!

---

## ✅ What You’ll Need

- A **PSP-3000** (or 2000/Go also works)
- A **Memory Stick** (or SD card with adapter)
- A USB cable or SD card reader
- A PC or Mac
- A bit of patience

---

## 🔓 Step 1: Install Custom Firmware (CFW)

We're going to install **ARK**, a custom firmware that lets us run PS1 games and homebrew.

### 1. Download the files:
You’ll need:
- **ARK installer**
- **Firmware 6.61** (in case you aren’t on it already)

> You can find ARK on [Wololo.net](https://wololo.net) or trusted forums.

### 2. Get the `ARK_Launcher` on your PSP:
- Connect your PSP to your computer.
- Create a folder: `PSP/GAME/ARK_Launcher`
- Copy the `EBOOT.PBP` from ARK into that folder.

### 3. Run it:
- Safely unplug your PSP.
- Go to `Game > Memory Stick` and run **ARK Launcher**.
- Your screen might flash — that’s normal.

That’s it! You're now running **ARK** CFW.

> 🔁 If you ever turn your PSP off completely (not sleep mode), just run ARK Launcher again to get back into CFW.

---

## 🕹️ Step 2: Play PS1 (PSX) Games Using ARK

### What you need:
- A PS1 game in **EBOOT.PBP** format  
- Optional: **POPSloader plugin** (for better compatibility with some games)

### 1. Add the PSX game:
- Create a folder like this on your PSP:  
  `PSP/GAME/YourGameName/`
- Inside that folder, place the **EBOOT.PBP** of your PSX game.

### 2. Run it!
- On your PSP, go to `Game > Memory Stick`
- Your game should show up with a cover and everything.
- Select it and play! 🎉

> If it says “Corrupted Data,” check that the folder and file are named correctly and not double-zipped or incomplete, it HAS to be PSP-->GAME--->Gamename--->the eboot file, if you have ANY MORE or ANY LESS folders in the middle, it won't work.

---

## 📦 Optional: Use POPSloader Plugin (for tricky games)

Some PS1 games need a special PS1 emulator plugin called **POPSloader** to work right.

### How to install:
1. Download **POPSloader**
2. Put the `popsloader` folder into your PSP's `seplugins/` folder
3. Add this to `pops.txt`:
Or `ef0:/seplugins/...` if you're using a Memory Stick adapter.
4. Run a PS1 game, then hold **R** when launching to pick a different version of POPS.

---

## 💡 FAQ (Stuff I Wish I Knew Earlier)

- **Why does my game show as “Corrupted Data”?**  
→ Your folder might be named weird or missing the EBOOT file.

- **Why does my game loop at the intro screen?**  
→ Mash a few buttons (especially Start, X or O) — many PSX games wait for input, i tried and it worked for me in many games

- **Can I use an SD card adapter instead of a real Memory Stick?**  
→ Yes, just make sure you use `ef0:/` in plugin paths instead of `ms0:/`.

- **Can I run PS2 or newer games?**  
→ Nope. The PSP isn’t strong enough for PS2 or modern console games.

---

## 🎮 Recommended Retro Games (They Work Great)

- **JoJo’s Bizarre Adventure (PSX)**
- **Final Fantasy VII - IX**
- **Crash Bandicoot**
- **Tekken 6**
- **Pokemon (with GBA emulator)**
- **Castlevania: Symphony of the Night**

---

## ❤️ Final Words

I made this because I spent HOURS trying to figure it all out. Hopefully, this helps you save time and just play your favorite games already.

Feel free to fork, star ⭐️, or add to this guide if you find a better way!

---

> 📝 Made with frustration and love by a fellow PSP nerd.
