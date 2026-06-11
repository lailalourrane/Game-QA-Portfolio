# Bug Report: UI Text Overlap & Broken Hierarchy in Terminal

**Game:** The White Door (Rusty Lake)
**Platform:** Windows
**Language/Localization:** Portuguese (PT-BR)
**Category:** UI/UX, Localization QA (LQA)
**Severity:** Moderate (Breaks UI readability and layout)

## 📝 Description
While playing the game localized in Portuguese (PT-BR), a severe UI design issue occurs when interacting with the in-game computer terminal. The translated text lacks a well-constructed visual hierarchy, causing different text elements to overlap directly on top of each other and completely breaking the interface layout. 

Additionally, some text strings are pushed entirely out of the screen bounds, leaving only a few green pixels visible at the top edge of the terminal monitor.

## 🔄 Steps to Reproduce
1. Launch *The White Door* on Windows.
2. Set the game language to Portuguese (PT-BR) in the settings.
3. Progress to the day/section requiring interaction with the computer terminal.
4. Open the terminal interface and observe the text rendering.

## ✅ Expected Behavior
The UI hierarchy and text containers should be elastic and responsive. They must properly accommodate localized string lengths to prevent overlapping, ensuring all text remains clearly readable and within the visual screen bounds of the terminal.

## ❌ Actual Behavior
Localized text overflows its designated container, overlaps with other text elements, and is pushed outside the visible screen area, rendering the terminal interface broken.

## 📸 Visual Evidence
![The White Door Bug Evidence]
https://cdn.discordapp.com/attachments/1429533649417539818/1508158997843153049/image.png?ex=6a2aef85&is=6a299e05&hm=20916c14832fc6e80f167679b0eb3e8986db59ebe9c1e5ac18815f1987f6a2ba&
https://cdn.discordapp.com/attachments/1429533649417539818/1508158795677700106/image.png?ex=6a2aef55&is=6a299dd5&hm=0e730ec10ef2866e7d676a971a65567e0664c2845540d73e506aab87d8b4f3f8&
https://cdn.discordapp.com/attachments/1429533649417539818/1508168423623098478/image.png?ex=6a2af84c&is=6a29a6cc&hm=74ec4f87e81caa983722ade32e0a8b5db6f4dbf367a82f6f377239176c56d956&
