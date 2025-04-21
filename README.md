# KeyDock

This is a project designed to prevent people from locking themselves out.

## Logic Flow
- You come home → you place your keys on the KeyDock (metal contact / magnet sensor).
- System goes into "armed" mode (ready to remind you next time).
- You open the door → reed switch detects the door opening.
- If the key is not docked at that moment → buzzer sounds for ~5-10 seconds.
- If the key is docked → no sound.

## Parts List
- MCP1700-3302E/TO-ND LDO regulator
- MSP430FR2111 MCU
- ORD211 Reed Switch
- TDK PS1240P02BT Active Buzzer
