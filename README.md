# Zenppuccin
## My personal amazingly clean theme.

![447375677-5ab83816-e6ad-41ec-a254-9c508c436297](https://github.com/user-attachments/assets/ddb76635-7c32-478f-b4bf-d9028aa90735)



## ✨**What is Zenppuccin?**
Zenppuccin is a comprehensive theme pack for Zen Browser that fuses four signature styles into one cohesive UI overhaul:

* **Bubble-Clean:** A minimalist, decluttered look with smooth, rounded elements and streamlined iconography.
* **Nebula:** a minimal theme made for Zen Browser which adds a lot of new animations, glass-like blur, UI changes, and more. It is inspired by glassmorphism and minimal gradients.
* **Zen-Catppuccin:** made by me, cool animations, glow effects, Better font, text contrast, and more.
* **Arcline:** Arc-like theme adds new icons, tab folders, copy link button, translate button, and more.


This theme customizes virtually every corner of Zen—tabs, toolbar, sidebar, context menus, pinned extensions, group tabs, the mini-player, URL bar, workspace buttons, and more—while still letting you tweak or disable any part if you prefer a lighter touch. ❤️

---

## 🚀 **Installation Guide** (Windows, macOS, and Manual Linux)

1. 📁 **Create the Chrome Folder**
   If you haven’t already, follow the \[Zen Live Editing Guide] to locate or create your `chrome/` directory inside your Zen profile.

2. 📦 **Download & Extract**

   * Download the `zenppuccin.zip` from the latest release.
   * Extract it so you have a top-level `Zenppuccin/` folder plus two CSS files:

     ```
     userChrome.css
     userContent.css
     ```
   * Move **both** the `Zenppuccin/` folder and those two CSS files into your `chrome/` directory.

3. 🧩 **Apply the Theme**
   You have two options:

   **Option A – Manual Imports**

   * Open your existing `userChrome.css` and add:

     ```css
     /* Zenppuccin core modules */
     @import "Zenppuccin/bubble-clean/bubble-clean.css";
     @import "Zenppuccin/Nebula/Nebula.css";
     @import "Zenppuccin/Zen-Catppuccin/Zenppuccin.css";
     @import "Zenppuccin/arcline/Arcline.css";
     ```
   * Open (or create) your `userContent.css` and add:

     ```css
     /* Nebula content tweaks */
     @import "Zenppuccin/Nebula/Nebula-content.css";

     /* Zenppuccin color & transparency fixes */
     @import "Zenppuccin/Zen-Catppuccin/Zenppuccin-content.css";
     ```

   **Option B – Use the Provided Files**

   * Simply replace your existing `userChrome.css` and `userContent.css` in the `chrome/` folder with the ones from the ZIP, which already include all necessary imports.

4. 🔄 **Restart Zen**
   Close and reopen Zen Browser to see all the new UI changes in action.

---

## ⚙️ **Enable Transparent Tabs**
To let the background bleed through your tabs (for that true glass effect):

1. In the address bar, go to `about:config`.
2. Search for `browser.tabs.allow_transparent_browser`.
3. If it appears, double-click to set it to **true**.

---

## **Customization Tips**

* Prefer fewer animations? In `Nebula.css`, comment out or reduce the animation durations in the `@keyframes` sections.

Enjoy your freshly “zen-ified” browser! If you’d like further tweaks—whether lighter, darker, or more playful—just dive into the CSS or ask ChatGPT for custom snippets. 😊

