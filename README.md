**English** | [Русский](README_RU.md)

# Litematica Material Filter

Addon for **Litematica**

Allows filtering the material list by query and displaying only the necessary blocks in the **Info HUD** or in the Schematic Placement in the world - without manually clicking "Ignore" on every extra material.

---

<img width="1920" height="1017" alt="image" src="https://github.com/user-attachments/assets/ed9a828b-8f63-47c0-9816-7df50431e412" />


## Usage

1. Load the schematic in Litematica, then open **`Material List`**, where you will find the **`Open Filter`** button, or simply press **`N`** by default. The last used placement is loaded automatically.
2. In the **Material Filter** window:
    - Tabs **`HUD`** / **`Hologram`** / **`Both`** choose which list you are selecting blocks for. The number shows how many blocks are selected.
    - **Click** a row to select a block, **hold and drag** to select several in a row.
    - Search (`glass`, `oak`, `redst`…) by localized name and ID; **`Enter`** or **`Select found`** selects everything found.
    - **`Not built`** selects blocks that are not in the world yet; **`↻`** recounts from the world; **`Only selected`** shows only selected rows; **`Reset filter`** clears the current tab.
    - Color of the "Total" number: **yellow** — to collect, **green** — already collected (enough in the inventory, shulkers included), **red** — already placed.
3. Settings column on the right:
    - **Selected blocks: Show / Hide** — whitelist or blacklist.
    - **HUD panel**: Material list, Raw crafting materials (recipe tree in the list and in the HUD; the "Crafting stage" slider under the toggle sets how deep it opens), Raw only (the HUD tab list and the HUD show raw resources; the "Crafting stage" slider under this toggle sets how far to break them down; resources are counted for the blocks selected in the regular list, and the raw list picks which resources the HUD shows; none picked shows all), Hide collected. A block of the wrong type in a schematic position does not count as placed.
    - **Hologram**: Apply filter, Entities and fluids.
4. The HUD panel in the bottom right corner shows only what still has to be collected (total / stacks / shulkers). Pages are switched with **`Page Up`** / **`Page Down`** (rebindable in Controls).

<img width="576" height="287" alt="image" src="https://github.com/user-attachments/assets/8f1ddbc3-0ec1-4ee5-a74c-9be35072aeed" />

<img width="537" height="314" alt="image" src="https://github.com/user-attachments/assets/1e4848a1-7e18-4471-a6a3-f0b470240458" />
