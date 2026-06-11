# Bug Report: UI Icon Desynchronization

**Game:** The Mermaid Mask
**Platform:** Windows / Steam *(Altere se foi no celular)*
**Category:** UI/UX, Component Desync, Front-end State
**Severity:** Minor / Moderate (Visual inconsistency and misleading feedback)

## 📝 Description
During gameplay, a component desynchronization issue occurs within the UI design. The visual state of specific icons fails to update or sync correctly with the actual internal state/actions of the game. This disconnect between the underlying logic and the UI rendering layer provides misleading visual feedback to the player.

## 🔄 Steps to Reproduce
1. Launch *The Mermaid Mask*.
2. Navigate to the section/menu where the specific UI icons are located.
3. Perform the sequence of interactions that triggers the state change.
4. Observe the icon's visual response compared to the actual expected state.

## ✅ Expected Behavior
The UI components and icons should rely on a precise state management system, updating immediately and synchronously to reflect the player's actions or the game's current status without visual delays or incorrect loops.

## ❌ Actual Behavior
The UI icons desynchronize, displaying an incorrect visual state that does not correspond to the real-time interaction or system logic.

## 🎥 Visual Evidence
https://github.com/user-attachments/assets/143eec8f-aec2-4902-a677-dfb8d484f666





