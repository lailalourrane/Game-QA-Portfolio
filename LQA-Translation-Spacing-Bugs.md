# Bug Report: Missing Translations & String Concatenation Error

**Game:** Momento
**Platform:** PC / Steam
**Language/Localization:** Portuguese (PT-BR)
**Category:** Localization QA (LQA), UI Text Formatting
**Severity:** Minor (Does not block gameplay, but affects immersion and polish)

## 📝 Description
During a full playthrough of the PT-BR localization, two distinct LQA issues were identified affecting the game's UI and narrative immersion:

1. **Untranslated Strings:** Several chat messages triggered during gameplay are missing their PT-BR localized strings, defaulting to English.
2. **String Concatenation/Spacing:** An item inspection UI element lacks a whitespace character between two distinct variables (Item Name and Author), causing the words to visually merge.

## 🔄 Steps to Reproduce
**For Bug 1 (Untranslated Strings):**
1. Set the game language to Portuguese (PT-BR).
2. Progress through the narrative until receiving social chat messages from contacts 'sal', 'salLada', or 'harpia'.
3. Observe the dialogue language.

**For Bug 2 (Spacing Error):**
1. Inspect the "Guia do astrônomo" item in the environment.
2. Read the UI pop-up displaying the title and author.

## ✅ Expected Behavior
All narrative text should be fully translated to PT-BR. Additionally, when variables are called in the UI (such as `[ItemName]` and `[Author]`), there must be a designated whitespace separating them to ensure proper readability (e.g., "Guia do astrônomo Por Dr. J. Harvi").

## ❌ Actual Behavior
Chat messages remain in English. The item UI displays concatenated text without a space ("Guia do astrônomoPor Dr. J. Harvi").

## 📸 Visual Evidence
<img width="384" height="97" alt="momento4" src="https://github.com/user-attachments/assets/bb0af10c-14f9-46cc-8352-1bb484ebf33c" />
<img width="473" height="456" alt="momento3" src="https://github.com/user-attachments/assets/9da01b56-16e5-408a-a6ab-fcdcd6916563" />
<img width="460" height="229" alt="momento2" src="https://github.com/user-attachments/assets/63fa7e8d-3cd2-47bf-94b8-661359f5abd7" />
<img width="525" height="462" alt="momento1" src="https://github.com/user-attachments/assets/f8269663-7e15-4c7c-810f-e1fe38a6bf3a" />
