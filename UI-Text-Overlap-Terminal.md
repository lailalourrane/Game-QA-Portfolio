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
![Evidência do Bug](<img width="924" height="1060" alt="image2" src="https://github.com/user-attachments/assets/1c508ff3-02e7-483d-9c08-29487958923d" />)
![Evidência do Bug](<img width="960" height="1079" alt="image1" src="https://github.com/user-attachments/assets/399f733e-d834-437f-a170-1cef27163b7f" />)
![Evidência do Bug](<img width="990" height="1079" alt="image3" src="https://github.com/user-attachments/assets/10cea654-2fb9-4b24-b57a-f4d588a8fda6" />)


